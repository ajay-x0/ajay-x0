# Hi, I'm Ajay Raghuwanshi 👋

### Backend Engineer | Java & Spring Boot | AWS | AI/ML Engineering

I’m a software engineer interested in building **backend systems, cloud applications, and AI-powered tools**. I work with **Java, Spring Boot, Python, REST APIs, SQL, and AWS**, and I enjoy learning through hands-on projects and Data Structures & Algorithms practice.

---

## 🚀 What I Work On

* 🔹 Backend development with **Java and Spring Boot**
* 🔹 REST APIs, microservices, and event-driven systems
* 🔹 Cloud applications using **AWS**
* 🔹 Database design, SQL, and data processing
* 🔹 **Machine learning, LLMs, and RAG** applications
* 🔹 Data Structures & Algorithms

---

## 🛠️ Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-17%20%7C%2021-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring%20MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20APIs-02569B?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Databases & Messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)

### AI & Data Engineering

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/LLMs-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C1C1C?style=for-the-badge)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)

---

## 🚀 Featured Projects

### 🏦 Distributed Banking Ledger & Payment System

**Java 21 · Spring Boot · PostgreSQL · Kafka · Redis · Docker Compose · GitHub Actions**

A locally runnable, production-inspired **banking transfer simulator** built with six Spring Boot services. It models payment authorization, idempotent requests, account operations, and double-entry ledger entries across a distributed workflow.

The payment flow uses a **durable saga** for coordination, while PostgreSQL transactions protect local ledger updates. An **outbox/inbox pattern**, Kafka events, and consumer deduplication handle asynchronous delivery. A Lite Docker Compose configuration was smoke-tested on an 8 GB Windows laptop.

**Focus:** Distributed Systems · REST APIs · Transactional Integrity · Idempotency · Event-Driven Architecture

→ **[View Project](https://github.com/ajay-x0/distributed-banking-ledger)**


### 🥗 Digi-Diet — IoT Nutrition Tracking System

**ESP32-CAM · Python · AWS IoT Core · AWS Lambda · DynamoDB · Amazon S3**

An IoT nutrition tracking prototype that sends food information through **AWS IoT Core (MQTT)** and uses **Lambda and DynamoDB** to process nutritional data. It combines an ESP32-CAM prototype, cloud services, and a dashboard for viewing results.

**Focus:** IoT · AWS Cloud · Serverless Architecture · Data Processing

→ **[View Project](https://github.com/ajay-x0/digi-diet)**

### 💬 Full-Stack Real-Time Chat Application

**Java 17 · Spring Boot · Spring Security · JWT · Spring Data JPA · MySQL · React · Vite**

A full-stack chat application with a **Spring Boot backend and React frontend**, supporting user registration, login, and real-time messaging. REST APIs and **Spring Security with JWT** handle authenticated requests; **Spring Data JPA and MySQL** store application data.

**Focus:** Full-Stack Development · REST APIs · Authentication · WebSockets · Database Design · React

→ **[View Project](https://github.com/ajay-x0/blink-backend)**

### 🏠 House Price Predictor

**Python · scikit-learn · Pandas · Streamlit · Joblib**

A machine learning project that predicts house prices from **synthetic housing data**. It compares **Linear Regression and Random Forest** using separate training, validation, and test sets, then saves the selected preprocessing and model pipeline for reuse.

A **Streamlit interface** lets users enter property details and generate predictions in the browser. Results are a demonstration of the modeling workflow, not estimates validated against real property sales.

**Focus:** Regression · Data Preparation · Model Evaluation · Reusable Pipelines · Interactive ML Apps

→ **[View Project](https://github.com/ajay-x0/house-price-predictor)**

### 🤖 Adaptive RAG — Agentic AI Chatbot

**Python · FastAPI · LangGraph · Qdrant · MongoDB · OpenAI**

A retrieval-augmented chatbot that routes queries between **document retrieval, general knowledge, and web search** workflows. It uses **LangGraph** for orchestration, **Qdrant** for vector search, **MongoDB** for session storage, and **FastAPI** to expose the backend.

**Focus:** Agentic AI · RAG · LLM Applications · Vector Search · API Development

→ **[View Project](https://github.com/ajay-x0/adaptive-rag-agent)**



---

## 💼 Experience

### Assistant System Engineer — Tata Consultancy Services (TCS)

**Pune, India · January 2025 – Present**

**Java · Spring Boot · REST APIs · SQL · Python · React.js · AWS · Agile/Scrum**

* Collaborate with a **5+ member distributed Agile team** and stakeholders to define API contracts, implement features, and deliver changes across weekly sprint cycles.
* Develop and enhance **Java/Spring Boot backend services and REST APIs**, contributing to both new functionality and improvements to existing enterprise applications.
* Optimized **Java service-layer processing and SQL queries**, including indexing improvements, achieving up to **12.5% reduction in processing time** in development and test environments.
* Improved database query performance and indexing strategies, resulting in approximately **7% faster response times** during development/testing and contributing to more efficient backend operations.
* Co-developed and enhanced a **Python-based automation framework using OpenPyXL** that converts Excel specifications into CAPL scripts, reducing a repetitive **5–6 hour manual process to minutes** for applicable workflows.
* Worked within established **coding, QA, version-control, and Agile practices**, collaborating with developers and stakeholders throughout the development lifecycle.

---

## 🏆 Certifications

* **AWS Certified Developer – Associate**
* **AWS Certified Solutions Architect – Associate**
* **Claude Certified Developer – Foundations**

---

## 🧩 Problem Solving

I regularly practice **Data Structures & Algorithms** and document my solutions on GitHub.

`Arrays` · `Strings` · `Hashing` · `Two Pointers` · `Sliding Window` · `Binary Search` · `Linked Lists` · `Trees` · `Graphs` · `Dynamic Programming`

→ **[View my LeetCode solutions](https://github.com/ajay-x0/leetcode-repo)**

---

## 📫 Let's Connect

I'm interested in **backend engineering, cloud, AI/ML systems, data engineering, and software projects**.

<p align="left">
  <a href="https://github.com/ajay-x0">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/ajay-raghuwanshi-79770724b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

<p align="center">
  <i>Building. Learning. Solving.</i>
</p>
