# NutriScan-AI-Calorie-Estimation-and-Personalized-Nutrition-Guide

📖 Project Overview

Gemini Health Tracker is a user-friendly AI-powered health management application that utilizes Google Gemini Pro Vision API to analyze food images, estimate calorie intake, and provide personalized nutrition insights. Designed with Streamlit for a seamless UI experience, this app is ideal for individuals aiming to track their calorie consumption and maintain a balanced diet.

🚀 Features

Calorie Estimation: Predicts the total calorie count from food images using AI-powered analysis.

Itemized Calorie Breakdown: Provides detailed calorie information for each food item in the image.

Nutrition Insights: Offers personalized dietary suggestions based on image analysis.

User-Friendly Interface: Built using Streamlit for an intuitive and responsive user experience.

Google Gemini Pro Integration: Leverages state-of-the-art AI for image recognition and nutrition estimation.

🛠 Tech Stack

Python: Core programming language

Streamlit: For building the interactive UI

Google Generative AI (Gemini Pro): For image analysis and generating results

dotenv: For managing API keys securely

Pillow (PIL): For image handling

PyPDF2: For PDF parsing (if needed in future)

pdf2image: Optional for converting PDFs to images

Langchain: For LLM-based text generation (if further expansion required)

ChromaDB: For vector storage

FAISS-CPU: For efficient similarity search

🧑‍💻 Usage

Upload an image of food using the "Choose an image" button.

Provide an optional input prompt if needed.

Click "Tell me the total calories" to get the analysis.

View the estimated calorie count and detailed breakdown.

