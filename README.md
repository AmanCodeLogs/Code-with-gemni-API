CivicMind AI 🏙️

Google Gen AI Academy APAC Edition Hackathon Prototype

CivicMind AI is a real-time Decision Intelligence platform designed to bridge the gap between citizen feedback and rapid municipal response. By leveraging the power of Google Gemini 2.5 Flash, the platform transforms unstructured, natural language complaints from citizens into structured, prioritized, and actionable data payloads for city officials.

🚀 The Problem

Modern communities generate large volumes of unstructured feedback (complaints, social media posts, emails). Transforming this information into actionable insights remains a significant challenge, often resulting in delayed responses to critical civic issues like broken infrastructure or safety hazards.

💡 The Solution

CivicMind AI introduces "Zero-Friction Input." Citizens simply type what they see naturally. The application uses a serverless architecture communicating directly with the Gemini API to instantly:

Categorize the issue (e.g., Infrastructure, Public Safety).

Score Severity to automatically flag Critical/High priority alerts.

Extract Entities to pinpoint locations.

Generate Action Plans providing a 2-sentence recommendation for immediate resolution by city workers.

🛠️ Technology Stack

Frontend: HTML5, Tailwind CSS, Vanilla JavaScript

AI Engine: Google Gemini 2.5 Flash API (Utilizing Structured JSON Prompting)

Architecture: Serverless, client-side processing for ultra-low latency.

⚠️ Note for Judges regarding API Key

For security purposes, the hardcoded Google Gemini API key has been removed from the deployed index.html file to prevent unauthorized usage via public GitHub scraping. The provided Demo Video demonstrates the fully functional application running with the active key.

Built for the Google Gen AI Academy Hackathon (APAC Edition).
