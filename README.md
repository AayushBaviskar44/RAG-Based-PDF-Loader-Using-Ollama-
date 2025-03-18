**RAG-Based Resume & JD Question Generator**

**Overview**

This project implements a Retrieval-Augmented Generation (RAG) model to generate interview questions based on job descriptions (JD) and resumes. It incorporates a weighted logic system to balance inputs dynamically and provides fallback mechanisms when JD and Resume data are unavailable.

**Features**
	•	Dynamic Question Generation: Generates relevant interview questions based on the provided JD and resume.
 
	•	Weighted Logic System: Adjusts question relevance dynamically when either the JD or resume is missing.
 
	•	Fallback Mechanisms: Fetches preset or API-generated questions when JD and resume are unavailable.
 
	•	Multi-Role Support: Automates question generation for roles including:
	•	Software Development Engineer (SDE)
	•	Data Scientist
	•	Front-End Developer
	•	Back-End Developer
	•	Data Analyst
	•	Digital Marketing
 
	•	Technology Stack: Utilizes Ollama, LLaMA models, and Python for efficient document processing and question generation.

Installation

Prerequisites

Ensure you have the following installed:
	•	Python 3.8+
	•	Ollama
	•	LLaMA models
	•	OpenAI API (optional, for fallback question generation)
