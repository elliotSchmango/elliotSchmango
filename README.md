<!--**elliotSchmango/elliotSchmango** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->
# Elliot Hong

## About Me
I'm a computer science student at UVA Engineering with a strong interest in ML security, edge-to-cloud architectures, and building software tools that help people. Here's my personal website! https://elliotschmango.github.io/elliothong_aboutme/

### Current Academic & Career Interests
- Machine Learning Sec (esp. LLMs & analytics)
- Cloud engineering (AWS/GCP)
- Mobile/Webdev development with React Native/Expo, React JS, Django, Flask
- Computing research in various fields

### Hobbies & Personal Interests
- Weightlifting & golf ⛳
- Motorsports & sim racing 🏎️
- Guitar
- Cooking

---

## Completed Projects

### WWTP-ADS (Waste Water Treatment Plant - Anomaly Detection System) (HRSD, Repository Private)
Offline, edge-based industrial anomaly detection system for water infrastructure monitoring
- Built with NVIDIA Jetson Orin Nano, PyQt5, and ONNX/TensorRT for real-time inference without cloud dependency
- Designed a modular, configurable pipeline integrating an unsupervised autoencoder for anomaly detection and a MobileNetV2 classifier for semantic labeling (Corrosion, Leak, Fire, Human, Unknown)
- Implemented servo-controlled 3×3 pan/tilt zone scanning with live status feedback via touchscreen GUI
- Fully offline and field-deployable, meeting strict security requirements for industrial environments

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

## Projects I'm Currently Working On

### STOMP (https://github.com/elliotSchmango/STOMP)
**S**calable **T**elemetry & **O**perations **M**L **P**latform is a secure, containerized microservices platform for anomaly detection and alerting in telemetry data. Inspired by mission-critical systems used in defense, utilities, and autonomous ops.
- Modular microservice architecture enables independent scaling and high availability
  - Built with FastAPI services for authentication (JWT) and strict role-based access control (RBAC)
  - Simulates real-time telemetry streams (process failures/custom metrics) with injected anomalies
  - Uses ML-based anomaly detection to flag abnormal patterns in operational data
  - Includes Prometheus monitoring, Grafana dashboards, email alerts, and centralized logging (Fluentd)
- Cloud-compatible with Dockerized services, AWS deployment, and load balancing support

### Streaming-Service (https://github.com/elliotSchmango/Streaming-Service)
A mock streaming platform built with React and Django, developed by a team using Agile and sprint-based workflows
- Simulates Netflix-style features including video browsing, playback, and user profiles
- Includes auth, watch history, favorites, and role-based admin controls
- Developing with a 6-sprint Agile process and clearly defined roles (Scrum Master, DevOps, Testing, Requirements)
- AWS used for cloud storage (S3) and deployment, with CI/CD pipeline integration

---

## Certificates
- GCP Associate Cloud Engineer - In Progress
- AWS Certified Solutions Architect - Associate: In Progress
- AWS Certified Cloud Practitioner - In Progress
- PCEP Certified Entry-Level Python Programmer: 2023

---

Thanks for visiting my profile! Feel free to explore my repos or reach out.
