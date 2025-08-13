# TDS-May-2025-Project-1-Virtual-TA 

This project implements a RAG-based virtual TA for the IITM TDS course, combining course content and Discourse posts.

## Deployment

- Built with Flask and Google Ai api
- Hosted on Render

## Environment Variables

GEMINI_API_KEY ="your api key here"

## Endpoints

- POST `/api/` with:
  ```json
  {
    "question": "...",
    "image": "base64string (optional)"
  }

