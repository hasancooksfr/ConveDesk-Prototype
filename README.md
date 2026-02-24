# ConveDesk Core - Open Conversational Booking Engine

> ⚠️ This project is currently under active development as part of FOSS Hack 2026. Features and integrations are being implemented iteratively during the hackathon period (March 1–31, 2026).

ConveDesk Core is an open-source, self-hostable conversational booking engine that enables small businesses to convert chat-based customer inquiries into structured bookings and payment requests using locally deployed AI.

---

## Problem Statement

Small businesses in India receive the majority of their customer inquiries through conversational platforms such as messaging applications and email. However, managing these inquiries manually often results in delayed responses, unstructured follow-ups, and missed booking opportunities.

Existing CRM tools are not optimized for conversational lead intake and often depend on proprietary APIs or closed ecosystems, limiting accessibility and control for small businesses.

---

## Proposed Solution

ConveDesk Core is an open-source conversational automation engine designed to help small businesses automatically convert customer inquiries into confirmed service bookings.

The system uses locally deployed AI models to:

- Understand incoming user queries  
- Collect required booking details  
- Check service availability  
- Confirm appointment slots  
- Generate payment requests  

All core functionalities operate without reliance on proprietary APIs or closed-source software.

---

## Key Features

- Self-hostable conversational AI interface  
- Automated booking workflow  
- Local intent detection  
- Slot availability management  
- SQLite-based booking storage  
- Mock UPI payment request generation  
- Configurable service definitions  

---

## Intended Users

- Coaching Institutes  
- Clinics  
- Gyms  
- Freelancers  
- Service Providers  
- Local Businesses  

---

## Technology Stack

### Frontend
- React (Vite)
- TailwindCSS

### Backend
- FastAPI (Python)
- Uvicorn

### AI Layer
- Ollama (Local Inference)
- Mistral / LLaMA (Open Source LLM)

### Database
- SQLite

### Payment Simulation
- Mock UPI Payment Link Generator

### DevOps
- Docker
- Docker Compose

---

## Installation

### Prerequisites

- Docker
- Docker Compose
- Ollama (Local LLM Runtime)

---

### Setup Instructions

```bash
git clone https://github.com/hasancooksfr/ConveDesk-Prototype/
cd convedesk-core
docker compose up
