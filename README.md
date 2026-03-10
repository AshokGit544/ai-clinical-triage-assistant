# AI Clinical Triage Assistant

AI-powered healthcare triage system that analyzes patient symptoms and suggests urgency level, possible conditions, and recommended next steps.

This project simulates how AI can support digital healthcare platforms and telemedicine services.

## Features

- Large Language Model powered reasoning
- Vector similarity search using FAISS
- Clinical knowledge retrieval
- Symptom-based triage recommendations
- OpenRouter LLM integration

## Technologies Used

Python  
Sentence Transformers  
FAISS Vector Database  
Large Language Models (LLM)  
OpenRouter API  
Pandas / NumPy

## Architecture

User Symptoms  
↓  
Embedding Model (MiniLM)  
↓  
Vector Search (FAISS)  
↓  
Retrieve Relevant Conditions  
↓  
LLM Reasoning  
↓  
Clinical Triage Recommendation

## Example Input

Symptoms: fever cough fatigue breathing difficulty  
Age: 65  
Medical History: diabetes

## Example Output

Urgency Level: High

Possible Conditions:
COVID-19
Pneumonia

Recommended Action:
Seek urgent medical evaluation.

## Project Motivation

This project demonstrates how AI systems can assist clinicians by analyzing symptoms and retrieving relevant medical knowledge before generating recommendations using large language models.

## Future Improvements

- Integration with real medical datasets
- Electronic Health Record (EHR) analysis
- Risk prediction models
- Deployment as an API
- Streamlit healthcare dashboard

## Author

Ashok 
AI / ML Engineer
