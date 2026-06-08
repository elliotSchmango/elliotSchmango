<!--**elliotSchmango/elliotSchmango** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->
# Elliot Hong

## About Me
Alum from UVA Engineering with a strong interest in AI security, edge-to-cloud architectures, and building software tools that help people.

### Current Academic & Career Interests
- AI Safety/Security
- Machine Learning Sec

### Hobbies & Personal Interests
- Weightlifting & golf ⛳
- Cars, motorsports, & sim racing 🏎️
- Guitar
- Cooking

---

## Projects I'm Currently Working On

### FUDGE-Suite (https://github.com/elliotSchmango/FUDGE-Suite)
A standardized benchmarking framework for evaluating Federated Unlearning algorithms against diverse attack vectors.

- Modular Architecture: Engineered a highly extensible PyTorch and Flower (flwr) pipeline, enabling researchers to seamlessly hot-swap custom aggregation strategies, unlearning algorithms (e.g., PGA), and threat models.
- Decoupled Metrics Framework: Implemented an AISI Inspect-inspired telemetry architecture that entirely decouples evaluation scorers (e.g., Attack Success Rate, Clean Accuracy) from task execution, ensuring standardized benchmarking across arbitrary attacks.
- Advanced Threat Modeling: Features a dynamic "Dual-Injection" threat engine that computes adversarial camouflage in-memory using Projected Gradient Descent (PGD) to evaluate vulnerabilities to active exploits like BadFU.
- Robust In-Memory Execution: Overhauled legacy multi-process bottlenecks into a deterministic, single-process architecture, ensuring exact reproducibility and rapid iteration times across Ray-orchestrated virtual clients.

---

## Completed Projects

### WWTP-ADS (HRSD, https://github.com/elliotSchmango/wwtp-anomaly-detection-system)
**W**aste **W**ater **T**reatment **P**lant - **A**nomaly **D**etection **S**ystem for water infrastructure monitoring
- Deploy-Everywhere Architecture: Refactored from a rigid Jetson prototype to a fully Dockerized stack capable of running on standard x86/ARM hardware (JetPack, Linux, Windows, etc).
- Hybrid AI Pipeline: Features a novel "Edge-to-Cloud" inference engine using a local SSIM-Denoising Autoencoder for real-time detection and Gemini 3 Pro for zero-shot anomaly classification.
- Modern Tech Stack: Replaced legacy PyQt5/I2C controls with a reactive Streamlit web dashboard and universal ONVIF/RTSP standards for commercial security cameras.
- Advanced Reliability: Implemented thread-safe state management and a rigorous "One-Shot" benchmarking framework for validating detection sensitivity in dynamic water environments.

### Dermadvisor (https://github.com/elliotSchmango/Dermadvisor)
A mobile skin condition classifier app built with React Native + AWS + Express
- Uses AWS SageMaker-hosted ResNet18 model to diagnose skin conditions from photos  
- React Native app built with Expo; supports camera & image uploads
- Uses AWS DynamoDB for APA-style sources and dynamic, inclusive UI for condition explanations 

### Technology CLA - Catalog Lending App (https://github.com/elliotSchmango/tech-lending-app)
Technology lending system for a library  
- Worked as the requirements manager in an agile development scrum-based team.
- Built with Django backend and Tailwind frontend  
- Led requirements gathering and stakeholder interviews  
- Implemented ticketing logic and borrowing workflows

### Virginia Population Analysis (https://github.com/elliotSchmango/Virginia-Population-Analysis)
Data science project analyzing population trends across Virginia counties  
- Collected and cleaned multi-year demographic data from the Virginia Open Data Portal  
- Built regression and time-series models (LSTM, polynomial regression) to forecast county-level population shifts  
- Used PCA for dimensionality reduction and K-Means clustering for pattern discovery across regions  
- Visualized trends and anomalies using Matplotlib and Seaborn to inform future infrastructure planning

### WaterBot (HRSD, https://github.com/elliotSchmango/HRSD_LLM)
Multimodal assistant for water plant engineers
- Built with React (Vite) frontend and Django backend, integrated via REST API
- Uses Llamafile’s Llama3.2-3B model for local inference with no external API calls for security
- Supports Retrieval-Augmented Generation (RAG) and iterative Co-RAG querying for improved contextual understanding
- Uses BLIP-2 for chart interpretation and AWS Amazon Textract for OCR
- Integrates with Microsft Azure for authentication/company security

### HR Dashboard (Internship, Save The Children International, Repository Private)
Role-based HR dashboard to optimize personnel assignment across projects
- Tech Stack: React.js, Django, and MongoDB
- Designed and implemented a custom algorithm inspired by bipartite matching
- Matched staff to initiatives based on Level of Effort (LOE), hiring status, and project budgets
- Built dynamic dashboards with secure login, LOE tracking, and administrative controls
  
### SnapSave Banking (https://github.com/elliotSchmango/snapsave_banking)
Finance-tech project for managing personal and business expenses
- Built with Next.js and React frontend for responsive user experience
- Integrated Plaid API for secure banking data aggregation
- Implemented Appwrite Authentication and Sentry for security and error monitoring
- Designed for extensibility with future transaction categorization and budgeting tools

### Querious (https://github.com/elliotSchmango/Querious)
A local document-based chatbot built with Streamlit, Ollama, and LangChain
- Lets users upload and query their own PDFs using a fully local RAG pipeline
- Uses LangChain to chunk and embed documents into a vector store for semantic search
- Runs a locally hosted LLM via Ollama to generate context-aware responses
- Prioritizes offline use and privacy with no cloud dependencies

---

## Certificates
- GCP Associate Cloud Engineer - In Progress
- AWS Certified Solutions Architect - Associate: In Progress
- AWS Certified Cloud Practitioner - In Progress
- PCEP Certified Entry-Level Python Programmer: 2023

---

Thanks for visiting my profile! Feel free to explore my repos or reach out.
