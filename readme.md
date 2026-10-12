# 🩺 AI Health Assistant

## 📌 Project Overview
The **AI Health Assistant** is a Python-based web application built using Streamlit. It collects basic user information, such as age, gender, allergies, and other health-related details, to provide personalized health insights.

The application calculates **BMI (Body Mass Index)** and **BMR (Basal Metabolic Rate)** and uses a Large Language Model (LLM) to generate AI-powered health guidance based on the information provided by the user.

The goal is to make basic health information easier to understand through a simple and interactive interface.

## 🚀 Features
- **User Input:** Collects age, gender, allergies, and other health-related information.
- **BMI Calculation:** Calculates Body Mass Index based on height and weight.
- **BMR Calculation:** Estimates Basal Metabolic Rate using user details.
- **AI-Powered Insights:** Uses an LLM to generate personalized health-related guidance.
- **Interactive Interface:** Provides a simple and user-friendly experience with Streamlit.

## 🛠️ Tech Stack
- **Python** – Core programming language.
- **Streamlit** – Builds the interactive web application.
- **LLM (Large Language Model)** – Generates AI-based health insights.
- **BMI and BMR Formulas** – Calculate basic health and metabolic indicators.

## ⚙️ How It Works
1. The user enters their basic information and health-related details.
2. The application processes the input and calculates BMI and BMR.
3. The collected information is used to generate a prompt for the LLM.
4. The LLM provides relevant health-related insights based on the supplied information.
5. The results are displayed through the Streamlit interface.

## 💻 Installation and Setup

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd <your-project-folder>
```

### 2. Create a Virtual Environment (Optional)
```bash
python -m venv venv
```

Activate it on Windows:
```bash
venv\Scripts\activate
```

### 3. Install Dependencies
If your project contains a `requirements.txt` file, run:
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
streamlit run app.py
```

Replace `app.py` with your main Python file name if it is different.

## 🎯 Project Objective
The objective of this project is to combine Python, Streamlit, and Large Language Models to create an interactive health assistant that helps users understand basic health indicators and access AI-generated health information.

## ⚠️ Disclaimer
This application is intended for informational and educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. BMI and BMR are estimates and should not be treated as medical diagnoses.

## 👨‍💻 Author
**Your Name**

Developed as a Python and AI project to explore health data processing, calculations, and Large Language Model integration.
