# 🏸 BillShop – AI-Powered Badminton E-Commerce Platform

BillShop is a full-stack e-commerce platform specialized for badminton products, integrating **modern web technologies** with **AI-powered features** to enhance the online shopping experience.

The system is designed as a **multi-repository architecture**, where each repository has a clear and independent responsibility.

---

## 🎯 Project Objectives

The main objectives of the BillShop project are:

- Build a scalable e-commerce system for badminton products
- Apply AI technologies to product consultation and user interaction
- Design a clean separation between frontend, backend, and AI services
- Explore multi-agent AI systems in real-world applications
- Improve usability and decision-making in online shopping

---

## 🏗️ System Overview

BillShop is composed of **four main repositories**, each representing a major system component:

### 1. Frontend (Next.js)
- Customer-facing user interface
- Product browsing and checkout
- AI chatbot interaction (UI layer)
- VR Shirt Try-On experience

### 2. Backend API (NestJS)
- Core RESTful API
- User management and authentication
- CRUD operations for core entities
- Database interaction and validation

### 3. Admin & AI Orchestrator (ExpressJS)
- Admin dashboard and management system
- Order and inventory operations
- Multi-agent AI orchestration
- AI-assisted admin and customer workflows

### 4. AI SQL Service (FastAPI)
- SQL database access for AI agents
- Natural language to SQL workflows
- LangChain SQLDatabase integration
- Controlled and safe query execution

## 📦 Repositories

The BillShop system is organized into the following repositories:

- **Frontend (Next.js)**  
  👉 https://github.com/thangle300403/Bill_nextjs_1410.git

- **Backend API (NestJS)**  
  👉 https://github.com/thangle300403/Bill_nestjs_1410.git

- **Admin & AI Orchestrator (ExpressJS)**  
  👉 https://github.com/thangle300403/Bill_expressjs_1410.git

- **AI Chatbot**  
  👉 https://github.com/thangle300403/AI_Chatbot_LG_TS.git

Each repository includes its own README with setup and implementation details.

---

## 🧠 AI Architecture Summary

The AI system is designed using a **multi-agent approach**, where:

- Each agent focuses on a specific task (consultation, policy, order handling)
- LangGraph is used for agent orchestration and control flow
- AI agents communicate with backend services through well-defined APIs
- Database access for AI is isolated in a dedicated service

This architecture improves **modularity**, **safety**, and **maintainability**.

---

## 🧩 Technology Stack

| Layer | Technology |
|------|-----------|
| Frontend | Next.js, React, Tailwind CSS |
| Backend API | NestJS, TypeScript, MySQL |
| Admin & AI | ExpressJS, LangChain, LangGraph |
| AI Services | FastAPI, LangChain, SQLAlchemy |
| Database | MySQL |
| AI Models | OpenAI / Gemini |

---

## 🔐 Security & Design Principles

- JWT-based authentication
- Role-based access control
- Environment-based configuration
- Separation of concerns across repositories
- Controlled AI access to system resources

---

## 🎓 Academic Context

BillShop is developed as a **Software Engineering graduation project**, focusing on:

- Full-stack system design
- AI integration in web applications
- Microservice-oriented architecture
- Practical application of multi-agent AI systems

---

## 📌 Repository Structure

Each repository contains its own:

- README documentation
- Environment configuration
- Installation and run instructions

This README serves as a **high-level overview** of the entire system.

---

## 👨‍💻 Author

**Lê Quốc Thắng**  
Software Engineering – Graduation Project  
Ho Chi Minh City University of Technology and Education
