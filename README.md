# AI-Powered-Healthcare-Intelligence-System

🤖 Building Intelligent Web Applications with AI and Machine Learning to Make Healthcare Information More Accessible 🩺.

# Description

AI-Powered Healthcare Intelligence System – An integrated Streamlit application combining machine learning, NLP, and AI to predict diseases from symptoms, recommend similar medicines, assess heart disease risk, provide AI-powered medical assistance, and help users locate nearby hospitals.

# Overview

This project brings together different areas of software development, data science, machine learning, and artificial intelligence. It represents practical exploration of how these technologies can be combined to build an interactive healthcare-focused application.
Built with Python, Machine Learning, NLP, and Streamlit.

# 📌 About the Project

The AI-Powered Healthcare Intelligence System is a multi-feature healthcare application built using Python, Machine Learning, Natural Language Processing (NLP), and Streamlit. The idea behind this project is to bring several useful healthcare features together in one place, making it easier for users to explore health-related information and receive data-driven insights through a simple, interactive interface.

Instead of building separate applications for different healthcare needs, this project combines disease prediction, medicine recommendations, heart disease risk assessment, an AI-powered medical chatbot, and hospital discovery into a single platform.

Throughout the development process, the focus was on applying machine learning concepts to practical healthcare-related problems while creating an accessible and user-friendly experience.

# 🚀 Key Features

1. Disease Prediction and Medical Recommendations
Predicts possible diseases based on user-selected symptoms using a trained Random Forest classifier.
Displays disease-related descriptions and precautions.
Provides associated medication, diet, and workout information.

2. AI-Based Drug Recommendation System
Allows users to search and select medicines.
Uses NLP techniques and CountVectorizer to process medicine-related text.
Applies cosine similarity to identify and recommend the top five similar medicines.
Displays medicine descriptions and provides external purchase links.

4. Heart Disease Risk Assessment
Analyzes demographic information, medical history, and lifestyle factors.
Uses an Easy Ensemble classifier with LightGBM for risk prediction.
Applies SHAP-based explainability to highlight influential health factors.
Presents risk scores and visual insights to help users understand model predictions.

4. AI Medical Chatbot – Medibot
Provides an interactive interface for healthcare-related questions.
Uses semantic similarity techniques to identify relevant disease information.
Includes predefined health tips and multilingual response translation.
The repository also contains FAISS-based vector-search resources and LLM integration scripts.

5. Hospital Recommendation
Allows users to enter their city or location.
Supports different hospital categories, including government, private, and multispeciality hospitals.
Uses Google Maps search to help users explore nearby hospital options.

# 🛠️ Technologies Used

Programming Language: Python
Frontend & Application Framework: Streamlit, HTML, CSS
Machine Learning: Scikit-learn, Random Forest, LightGBM, Easy Ensemble Classifier
Data Analysis: Pandas, NumPy, Matplotlib, Seaborn, Plotly
Natural Language Processing: CountVectorizer, Sentence Transformers, Cosine Similarity
AI & Language Models: Mistral-7B, Hugging Face, LangChain
Model Explainability: SHAP
Vector Database: FAISS
Development Tools: Jupyter Notebook, Google Colab, VS Code, Git, GitHub

# 📂 Project Structure

home.py – Main Streamlit application and navigation page.
pages/ – Individual application modules for disease prediction, drug recommendations, heart disease assessment, Medibot, and hospital recommendations.
models/ – Saved machine learning models, encoders, and similarity resources.
data/ – Healthcare datasets, medicine information, symptoms, precautions, diets, and workout recommendations.
utils/ – Styling resources, images, and supporting application assets.
Disease Prediction and recommendation/ – Disease prediction Jupyter Notebook and documentation.
Drug Recommendation/ – Drug recommendation notebook and documentation.
heart_disease_risk_assessment/ – Data preprocessing, exploratory analysis, and model development notebooks.
medibot/ – Medical chatbot resources and supporting scripts.
requirements.txt – Python package dependencies.

# 🎯 Project Objectives

Explore practical applications of machine learning in healthcare.
Understand how predictive models can analyze symptoms and health-related information.
Apply NLP and similarity-based techniques to medicine recommendations.
Explore model interpretability through SHAP.
Integrate multiple AI-driven features into a single interactive application.
Build a user-friendly platform that makes healthcare information easier to explore.

# 🔮 Future Improvements

Improve model validation and prediction reliability.
Integrate verified medical knowledge sources.
Enhance chatbot capabilities with improved conversational memory.
Improve multilingual support.
Introduce secure user profiles and health history management.
Deploy the application with improved scalability and performance.

# ⚠️ Disclaimer

This project is developed for educational and demonstration purposes. Its predictions, medicine suggestions, chatbot responses, and health-related information are not a substitute for professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare professional before making medical decisions.

# Contributing

Feel free to fork this repository, submit issues, or send pull requests. I’d love to collaborate and improve this application!



