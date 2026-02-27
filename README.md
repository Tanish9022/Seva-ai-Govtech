# SevaAI — GovTech Intelligence Platform

Transforming official Indian government scheme documents 
into structured, personalized eligibility intelligence 
for every citizen.

## Problem
Millions of eligible Indian citizens miss government 
welfare schemes due to complex bureaucratic documents, 
fragmented PDFs, and zero personalization on government 
portals.

## Solution
SevaAI answers three core citizen questions:
1. Am I eligible for this scheme?
2. What documents do I need?
3. What are my next steps?

Every answer cites the exact official source document 
and page number. Zero hallucination guaranteed.

## Tech Stack
- Backend: FastAPI + FAISS + Sentence Transformers
- LLM: Google Gemini 1.5 Flash (free tier)
- Frontend: Next.js 14 + TypeScript + Tailwind CSS
- Infrastructure: AWS EC2, S3, RDS, Amplify, Cognito

## Architecture
- EC2 t3.medium: FastAPI backend + FAISS in-memory index
- S3: Official scheme PDFs + index backups
- RDS PostgreSQL: User profiles + query history
- Amplify: Next.js frontend with CI/CD
- Cognito: Citizen authentication

## Status
🚧 Active Development — Prototype submission March 4, 2026
