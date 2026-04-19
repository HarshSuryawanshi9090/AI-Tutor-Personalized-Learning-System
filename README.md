# 🎓 AI Tutor – Personalized Learning Recommendation System

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Flask](https://img.shields.io/badge/Flask-3.0.0-green)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28.0-red)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.0-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📖 Overview
AI Tutor is an intelligent, multi-modal recommendation system that provides personalized learning paths for students by analyzing their performance history, learning style, and similarity to peers. The system identifies weak concepts, recommends appropriate learning resources, and creates structured study plans using machine learning algorithms.

---

## 🎯 Core Features

- 📊 Performance Analysis - Real-time tracking of student mastery across concepts
- 👥 Student Clustering - Groups students based on learning behavior patterns
- 🔍 Similarity Engine - Identifies peers with similar learning profiles
- 🎯 Smart Recommendations - Provides personalized learning resource suggestions
---

## 🛠️ Tech Stack

### Backend & Data Science
- **Python 3.9+**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical computing
- **Scikit-learn**: Machine learning algorithms (K-Means, Linear/Logistic Regression, Cosine Similarity)
- **Flask**: REST API framework
  
### Frontend & Visualization
- Streamlit: Interactive web dashboard
- Plotly & Matplotlib: Data visualization and charts
---

### 📦 Installation

- Clone the repository
```bash

git clone https://github.com/yourusername/ai-tutor.git
cd ai-tutor
```
- Create virtual environment 
```bash
python -m venv venv
venv\Scripts\activate
```
- Install dependencies
``` bash
pip install -r requirements.txt
```
---
### 🚀 Usage
```bash
cd AI-Tutor-Personalized-Learning-System-main
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
streamlit run dashboard.py
```

### ☁️ Deploy to Streamlit Cloud
1. Push the repository to GitHub.
2. Open Streamlit Cloud and connect your GitHub repository.
3. Set the app file to `dashboard.py`.
4. Ensure `requirements.txt` and the `data/` folder are included in the repo.

---
### 🏗️ System Architecture

```text
Student Performance Data
        ↓
Data Preparation & Feature Engineering
        ↓
Performance Analysis
        ↓
Student Clustering (K-Means)
        ↓
Similarity Engine (Cosine Similarity)
        ↓
Recommendation Engine
        ↓
Personalized Learning Plan
```
---
### Data Flow

- Input: Student performance data and metadata
- Processing: Feature engineering, clustering, similarity analysis
- Analysis: Concept mastery calculation, trend prediction
- Recommendation: Content-based + collaborative filtering
- Output: Personalized learning plan with explanations
---
### 📊 Dashboard Preview

<img width="1826" height="924" alt="Screenshot 2026-01-05 125400" src="https://github.com/user-attachments/assets/08f26935-fb85-443a-abf9-e4797777f8e0" />

---
## 📈 Weak Skills Detection

The system detects weak skills using a hybrid approach combining statistics and machine learning.

### Concept Mastery Score (0–100)
- Accuracy & Response Efficiency
- Trend Prediction (improving / declining)

### Techniques Used
- Logistic Regression (mastery classification)
- Linear Regression (trend prediction)
- Rule-based thresholds for prioritization

### Skill Priority
- **High:** Mastery < 50 or declining trend
- **Medium:** Mastery 50–65
- **Strong:** Mastery > 65
---
## 🎯 Recommendation System
A hybrid recommendation strategy is used:
- Content-Based Filtering – Weak concepts → relevant resources
- Collaborative Filtering – Resources successful for similar students
- Rule-Based Logic – Prerequisites and learning style matching
---
## 📚 Supported Learning Domains

### Mathematics
- Linear Algebra  
- Calculus  
- Probability & Statistics  
- Distance Metrics  

### Machine Learning
- Regression (Linear, Logistic)
- Tree-Based Models (Decision Trees, Random Forests)
- Instance-Based Models (KNN)
- Support Vector Machines

### Deep Learning
- Neural Network Fundamentals
- CNNs, RNNs, LSTMs
- Attention & Transformers
- Autoencoders & GANs

## ✅ Result

The AI Tutor system successfully analyzes student performance data and generates personalized learning recommendations. The system demonstrates effective identification of weak concepts, accurate student grouping, and meaningful resource suggestions.

### Key Outcomes
- Accurate **concept mastery scoring** for each student
- Clear identification of **weak and strong learning areas**
- Meaningful **student clusters** based on learning behavior











