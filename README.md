# MaintAI: Maintenance Failure Mechanism Classification

## Overview

MaintAI is an industry capstone project developed in collaboration with RMIT University and the Sir Lawrence Wackett Defence & Aerospace Centre (SLWDAC).

The system automatically classifies unstructured aircraft maintenance records into engineer-defined failure mechanisms such as leaking, corroded, cracked, and failed using Explainable Artificial Intelligence (XAI) and Unsupervised Machine Learning techniques.

Unlike traditional supervised approaches, MaintAI does not require large labelled training datasets and can be deployed immediately using user-defined categories and keywords.

---

## Key Features

* Unsupervised failure mechanism classification
* Explainable AI with confidence scores and keyword evidence
* Human-in-the-loop review and validation workflow
* Active learning for category refinement
* Scalable processing of 170,000+ maintenance records
* Web-based interface for upload, classification, review, and export

---

## Technologies Used

### Machine Learning & NLP

* Python
* FastText
* TF-IDF
* Ensemble Learning
* ECOC (Error-Correcting Output Codes)
* Natural Language Processing (NLP)

### Backend

* Flask REST API
* Docker
* Async Processing

### Frontend

* React 19
* Vite
* JavaScript
* Tailwind CSS

### Tools

* Git & GitHub
* Agile/Scrum Development
* Microsoft Teams

---

## Machine Learning Pipeline

MaintAI combines multiple classification approaches:

1. TF-IDF Token Matching
2. Equipment-Based Classification
3. FastText Semantic Similarity
4. UMEC Ensemble Learning

The UMEC Ensemble combines the strengths of all classifiers to improve prediction accuracy and robustness.

---

## Architecture

User Upload
↓
Data Preprocessing
↓
Token Matching
↓
Equipment-Based Classification
↓
Semantic Similarity
↓
UMEC Ensemble
↓
Engineer Review & Validation
↓
Export Results

---

## Project Outcomes

* Processed over 170,000 maintenance records
* Achieved 77.3% classification accuracy
* Reduced manual review effort by approximately 85%
* Delivered explainable and auditable predictions
* Developed a deployable full-stack web application

---

## My Contributions

As Machine Learning Developer, I contributed to:

* TF-IDF Token Matching Classifier
* FastText Semantic Similarity Classifier
* Data preprocessing pipeline
* Token generation functionality
* Model evaluation and performance analysis
* Active learning workflow design
* Technical documentation and reporting

---

## Industry Partner

Sir Lawrence Wackett Defence & Aerospace Centre (SLWDAC)

Industry Capstone Project
RMIT University
Master of Data Science
2026

---

## Repository Structure

frontend/ – React application

backend/ – Flask REST API

src/umec/ – Machine learning models and ensemble framework

configs/ – Configuration files and mappings

docs/ – Technical documentation

docker-compose.yml – Deployment configuration

---

## Future Enhancements

* Continual learning from engineer feedback
* CMMS integration
* Automated keyword generation
* Predictive maintenance analytics
* Fine-tuned transformer models using accumulated labelled data
