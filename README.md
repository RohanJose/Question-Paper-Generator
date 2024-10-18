# Question-Paper-Generator
This project is designed to dynamically generate C programming question papers using Generative AI. 

This repository implements a C Programming Question Paper Generator using Retrieval-Augmented Generation (RAG). The goal is to generate high-quality C programming questions with accurate answers by combining retrieval-based models with generative capabilities.

## Features
Automatically generate C programming questions.
Incorporates RAG for improved accuracy and relevance of generated questions.
Covers various difficulty levels: Beginner, Intermediate, Advanced.
Ability to retrieve existing question patterns and augment them with generative models.
Supports custom input and dataset for specific question generation.

## Technologies Used
RAG Model: Combines retrieval and generation to create relevant questions.
LangChain: Framework to streamline the use of LLMs with retrieval mechanisms.
Python: Backend logic and RAG model integration.
C Programming Knowledge Base: Custom dataset of C programming questions and answers.

## How It Works
Data Retrieval: The system first retrieves similar questions from a predefined C programming question bank.
Generation: The generative model augments the retrieved information to create unique questions.
Output: The generated questions are presented in a structured format, ready for use in exams or quizzes.

Here's the modified installation section for your GitHub project:

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/C-Programming-Question-Generator.git
   cd C-Programming-Question-Generator
   ```

2. **Set up the Python environment**:
   ```bash
   conda create -n c-question-gen python=3.9
   conda activate c-question-gen
   pip install -r requirements.txt
   ```
   
## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.

