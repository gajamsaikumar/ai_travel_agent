# AI Travel Agent

A production-style AI backend system integrated with a full DevOps pipeline, demonstrating deployment, monitoring, and scalable infrastructure using modern cloud and container technologies.

---

## Overview

This project goes beyond a standard AI application by combining backend development with DevOps practices. It demonstrates how an AI-powered system can be deployed, monitored, and managed in a production-like environment.

The system processes documents, generates structured responses, and is deployed using containerisation and orchestration tools.

---

## Tech Stack

### Backend
- Python
- Flask
- REST APIs

### AI / NLP
- Text processing
- Document understanding

### DevOps & Infrastructure
- Docker (containerisation)
- Kubernetes (deployment & orchestration)
- Jenkins (CI/CD pipeline)
- AWS / GCP (cloud infrastructure)

### Monitoring & Logging
- Prometheus (monitoring)
- ELK Stack (Elasticsearch, Logstash, Kibana)

---

## Features

- AI-based document processing and summarisation  
- REST API backend for real-time interaction  
- Containerised application using Docker  
- CI/CD pipeline using Jenkins  
- Kubernetes-based deployment  
- Centralised logging using ELK Stack  
- Monitoring with Prometheus  

---

## System Architecture

1. Backend processes documents and handles API requests  
2. Application is containerised using Docker  
3. CI/CD pipeline automates build and deployment  
4. Kubernetes manages scaling and deployment  
5. Logs are collected and visualised using ELK  
6. Metrics are monitored using Prometheus  

---

## Project Structure

/app  
├── routes/  
├── services/  
├── models/  
├── utils/  
└── main.py  

/devops  
├── docker/  
├── kubernetes/  
├── jenkins/  
└── monitoring/  

---

## Running the Project

```bash
git clone https://github.com/gajamsaikumar/ai_travel_agent
cd ai_travel_agent
docker build -t ai-agent .
docker run -p 5000:5000 ai-agent
