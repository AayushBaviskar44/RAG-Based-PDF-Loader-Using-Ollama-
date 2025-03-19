**Overview**
This project implements a Retrieval-Augmented Generation (RAG) model using the Llama model to automate the process of generating interview questions. The model scrapes data from resumes and job descriptions (JDs) to generate tailored, role-specific questions. If resumes or job descriptions are unavailable and the candidate only provides the role title, the model uses preset job descriptions and integrates with ChatGPT to generate relevant questions.

**Key Features**
Data Scraping: Extracts information from resumes and job descriptions for processing.
Question Generation: Automatically generates relevant interview questions based on scraped data.
Fallback Mechanism: If no resume or job description is provided, the model uses preset JDs based on role titles to generate questions.
ChatGPT Integration: Uses ChatGPT to create meaningful and contextually appropriate questions when only the role title is available.

**Technologies Used**
Llama: Used for fine-tuning and model training.
ChatGPT: Integrated for context-based question generation.
Python: Core programming language for implementation.
NLP (Natural Language Processing): For data extraction and question generation.
Machine Learning: For model training and optimization.

