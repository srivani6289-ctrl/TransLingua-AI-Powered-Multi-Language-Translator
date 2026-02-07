# 🌐 AI-Based Multilingual Language Translator

## 📖 Overview

This project is a basic AI-powered multilingual language translator developed using
:contentReference[oaicite:0]{index=0} and the :contentReference[oaicite:1]{index=1} API.
It allows users to input text, select the source and target languages, and receive
instant translations powered by a generative AI model.

The application is designed with a simple and user-friendly interface, making it ideal
for beginners who want to learn how to integrate AI models into web-based applications.
This project was developed as part of an internship to gain hands-on experience with
AI-powered tools and modern web frameworks.

## ✨ Features
- AI-driven text translation using the Google Gemini Flash model
- User-friendly and interactive Streamlit interface
- Support for multiple language selection
- Secure handling of API keys using environment variables
- Lightweight and easy-to-understand project structure

## 🧰 Tech Stack

The technologies used in this project include:

- Python programming language
- :contentReference[oaicite:0]{index=0} framework
- :contentReference[oaicite:1]{index=1} (Gemini API)
- python-dotenv for environment variable management

## 📁 Project Structure

The project is organized as follows:

translingua/
│── translang.py        # Main Streamlit application file
│── requirements.txt   # List of required Python libraries
│── .env                # File used to store the API key securely

## 🔧 Installation

### Step 1: Download the Project
Clone the repository or download the project files and navigate to the project directory.

git clone <your-repository-link>
cd translingua
### Step 2: Set Up a Virtual Environment
Create and activate a virtual environment to manage dependencies efficiently.

python -m venv venv
venv\Scripts\activate

### Step 3: Install Required Libraries
Install all necessary dependencies listed in the requirements file.

pip install -r requirements.txt

## 🔐 Environment Setup

Create a `.env` file inside the project folder and add your Gemini API key for authentication.

GOOGLE_API_KEY=your_api_key_here

## ▶️ Run the Application

Launch the application using Streamlit. Once started, the app will automatically open
in your default web browser.

streamlit run translang.py

You can now enter text, select languages, and view the translated output instantly.

## 🧪 How It Works

1. The user enters the text to be translated.
2. The user selects the source language and the target language.
3. The application sends the translation request to the Gemini AI model.
4. The translated output is generated and displayed on the screen.

This process ensures fast and accurate translations using generative AI.

## ⚠️ Notes

- Do not upload the `.env` file to GitHub for security reasons.
- API usage may result in charges based on the Gemini usage limits.
- The available language options are currently fixed and can be extended by modifying the main Python file.

## 🚧 Future Improvements

- Add dynamic language selection support
- Implement speech-to-text functionality
- Enable text-to-speech output
- Store translation history for user reference
- Improve error handling and input validation
