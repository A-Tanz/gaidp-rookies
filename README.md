# 🚀 PRO-FILER

## 📌 Table of Contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction

Data Profiling using Gen-AI Regulatory reporting in the banking sector invloves compiling vast amounts of data to meet Compliance requirements. Data Profiling ensures that the reported data aligns with regulatory reporting instructions. This involves manually defining profiling rules, perform adaptive risk scoring, and suggest remediation actions based on regulatory reporting instructions.

## 🎥 Demo

🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots:

![image](https://github.com/user-attachments/assets/aac9fa9f-2eb7-4852-92e7-3ebb3130af66)
<br><br>
![image](https://github.com/user-attachments/assets/a27b2c08-cfe3-403d-8aca-81b6b653aa04)
<br><br>
![image](https://github.com/user-attachments/assets/ce34372d-eaf2-47b6-8cdd-afd6ac2c93f2)
<br><br>
![image](https://github.com/user-attachments/assets/639962fb-d50e-4f67-918e-d117d009d715)
<br><br>
![image](https://github.com/user-attachments/assets/43bcf508-5319-48c7-809f-36d7f3b7cdcf)


## 💡 Inspiration

We have automated the profiling process to make it more efficient. Previously, users had to manually code all the profiling rules. Now, with the power of generative AI, you can simply provide profiling rules in natural language, and the system will automatically generate the necessary rules and perform the profiling.

## ⚙️ What It Does

* Generates code for profiling rules based on natural language input.
* Assigns risk scores and facilitates the flagging process.
* Continuously improves profiling rules for better accuracy and performance.
* Assists in developing comprehensive remediation plans.

## 🛠️ How We Built It

To build the solution, we integrated advanced Natural Language Processing (NLP) models like OpenAI's GPT to convert natural language descriptions into structured code, simplifying the rule creation process. Machine learning models were employed to analyze large datasets, assign risk scores, and flag potential issues. A user-friendly web interface, built with Django and Flask, allows non-technical users to input rules and receive feedback. The backend, powered by Python, processes data and interfaces with AI models, supporting scalable profiling tasks. Additionally, AI-generated automated remediation plans guide users in mitigating risks, and a continuous feedback loop ensures ongoing system improvement and adaptability to new data.

## 🚧 Challenges We Faced

One of the main challenges was ensuring the accuracy of the AI models when converting natural language descriptions into structured code. We had to fine-tune the NLP models to correctly interpret diverse ways users might express rules. Another challenge was integrating machine learning models with large datasets while maintaining system performance and scalability. Ensuring that the models assigned accurate risk scores and flagged issues reliably required extensive training and validation on historical data. Additionally, creating a user-friendly interface that could simplify complex processes for non-technical users, while still offering advanced features, posed a design challenge.

## 🏃 How to Run

1. Clone the repository

2. Demo Regualatory Rules word and data.csv is present in artifacts/demo

3. Add your Open-AI API Key  at [app.py](https://github.com/ewfx/gaidp-rookies/blob/main/code/src/app/app.py#L26)

4. Navigate to directory
   ```sh
   cd code/src/app
   ```
   
5. Install dependencies
   ```sh
   pip install -r requirements.txt
   ```
6. Run the project
   ```sh
   python app.py
   ```

## 🏗️ Tech Stack

## Tech Stack

- **Backend**:  
  - **Django**: A high-level Python web framework used to power the backend, manage server-side logic, and handle user authentication and data processing.
  - **Flask**: A lightweight Python framework used to build APIs and integrate AI models for profiling and risk analysis.

- **AI & NLP**:  
  - **OpenAI GPT**: Used for natural language processing (NLP) to convert natural language descriptions into structured profiling rules.

- **Deployment**:  
  - **Docker**: Used for containerizing the application to ensure consistent and efficient deployment across different environments.

- **Version Control**:  
  - **Git**: For version control and tracking changes in the codebase.
  - **GitHub**: A platform for hosting the project repository, collaborating with other developers, and managing code.

## 👥 Team

- **Afraz Tanvir** - [GitHub](https://github.com/A-Tanz) | [LinkedIn](https://www.linkedin.com/in/afraz-tanvir/)
- **Prakhar Sharma** - [GitHub](#) | [LinkedIn](#)
- **Uday Goel** - [GitHub](#) | [LinkedIn](#)
- **Priyal Mittal** - [GitHub](#) | [LinkedIn](#)
- **Aayushi** - [GitHub](#) | [LinkedIn](#)
