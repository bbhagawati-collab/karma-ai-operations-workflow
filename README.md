# Karma AI Resort Operations Workflow

## Overview

This project demonstrates an AI-powered Resort Operations Recommendation Workflow built using **n8n**, a **self-hosted Ollama (Llama 3.2)** model running on a **Hostinger VPS**, and the **Open-Meteo Weather API**.

The workflow combines live weather information with resort operational context to generate AI-driven operational recommendations for resort managers. The recommendations are automatically stored in Google Sheets for reporting and analysis.

---

## Workflow Architecture

Manual Trigger

↓

Open-Meteo Weather API

↓

Business Context (Occupancy, Season, Special Event)

↓

AI Prompt Generation

↓

Self-hosted Ollama (Llama 3.2 on Hostinger VPS)

↓

Code Node (JSON Parsing)

↓

Google Sheets

---

## Technologies Used

- n8n
- Self-hosted Ollama (Llama 3.2)
- Hostinger VPS
- Docker
- Open-Meteo Weather API
- JavaScript (Code Node)
- Google Sheets

---

## Local AI Infrastructure

Instead of using a hosted AI service, this workflow uses a self-hosted Ollama instance deployed on a Hostinger VPS.

### Configuration

- Hosting: Hostinger VPS
- Runtime: Docker
- AI Server: Ollama
- Model: Llama 3.2
- Integration: n8n Ollama Node
- Output: Structured JSON
- Storage: Google Sheets

This approach demonstrates how enterprise AI workflows can run on private infrastructure without relying on external AI APIs.

---

## Features

- Live weather data retrieval
- Business context enrichment
- AI-powered operational recommendations
- Structured JSON output
- Automatic Google Sheets reporting
- Self-hosted LLM inference

---

## Sample Output

The workflow generates:

- Staffing Recommendation
- Guest Experience Recommendation
- Operations Recommendation
- Marketing Recommendation
- Risk Level
- Daily Operational Summary
