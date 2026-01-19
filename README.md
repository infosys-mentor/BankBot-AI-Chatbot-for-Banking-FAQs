# BankBot – AI Chatbot for Banking FAQs

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![AI](https://img.shields.io/badge/AI-NLP-green)
![LLM](https://img.shields.io/badge/LLM-Transformer--Based-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## Project Description

An AI-powered chatbot built using Streamlit and LangChain to answer frequent banking questions. It handles customer queries and displays responses via a simple UI.


---

## Features

- AI-powered responses
- Easy UI with Streamlit
- Secure authentication
- Modular architecture

---

## Techniques Used

### Natural Language Processing (NLP)

* Text preprocessing and normalization
* User intent understanding
* Context preservation across queries

### Prompt Engineering

* Domain-specific prompt design for banking use cases
* Controlled and safe response generation
* Prompt templates for consistent outputs

### LLM-based Text Generation

* Transformer-based text generation
* Instruction-following conversational AI
* Scalable and model-agnostic design

---

## Tech Stack

### Programming Language

* **Python**

### Libraries / Frameworks

* `transformers`
* `torch`
* `nltk`
* `sentencepiece`
* `streamlit` / `flask` (for UI or API layer)
* `pandas`
* `numpy`

### AI / ML Technologies

* Natural Language Processing (NLP)
* Large Language Models (LLMs)
* Transformer architecture
* Prompt Engineering

---

## LLM Details

* Uses **transformer-based Large Language Models**
* Supports models such as:

  * GPT-style models
  * Instruction-tuned transformer LLMs
* **LLM is fully configurable**:

  * Model name
  * Token length
  * Temperature
  * Inference parameters

This design allows easy replacement or upgrade of the LLM without changing core application logic.

---

## Project Structure

```
BankBot-AI-Chatbot-for-Banking-FAQs/
│
├── app.py                  # Main application entry point
├── chatbot/
│   ├── prompt_engine.py    # Prompt engineering logic
│   ├── llm_handler.py      # LLM integration
│   ├── nlp_utils.py        # NLP preprocessing utilities
│
├── data/
│   └── banking_faqs.json   # Banking FAQ knowledge base
│
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── LICENSE                 # License information
```

---

## Installation Steps

1. **Clone the repository**

   ```
   git clone https://github.com/infosys-mentor/BankBot-AI-Chatbot-for-Banking-FAQs.git
   ```

2. **Navigate to the project directory**

   ```
   cd BankBot-AI-Chatbot-for-Banking-FAQs
   ```

3. **Create a virtual environment (optional but recommended)**

   ```
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
   ```

4. **Install dependencies**

   ```
   pip install -r requirements.txt
   ```

---

## How to Run the Project Locally

1. Ensure all dependencies are installed
2. Run the application:

   ```
   python app.py
   ```
3. Interact with the chatbot via terminal or web interface (based on implementation)

---

## Certification Use Case

This project is **ideal for Infosys Certification and Evaluation** because it:

* Demonstrates real-world AI application development
* Uses industry-standard NLP and LLM techniques
* Follows clean coding and modular design principles
* Supports explainability and scalability
* Aligns with modern GenAI and Agentic AI concepts

It can be showcased as:

* AI/NLP Capstone Project
* Enterprise-ready Conversational AI System
* GenAI Proof of Concept (PoC)

---

## License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this project for educational and professional purposes.

---

### ⭐ If you find this project useful, please consider giving it a star on GitHub!
