# P.A.S.T. — Personalized Assessment System for Tutoring

## Project Overview
**P.A.S.T.** is an AI-powered tutoring assistant designed to reduce academic stress and improve self-guided learning by dynamically generating multiple-choice questions and personalized feedback based on any topic the student inputs.

This tool helps students:
- Practice subject material in an interactive way
- Receive AI-generated feedback on their answers
- Reinforce understanding through guided correction

This project was developed as part of the **AI Remove Barriers** term project to demonstrate how artificial intelligence can assist learners in overcoming educational challenges like test anxiety, poor feedback access, and inconsistent study methods.

---

## How It Works

1. The student selects a **topic** (e.g., "World War II", "Binary Search", "Photosynthesis")
2. The system uses **Google's Gemini API** to generate a **multiple-choice question** with four answer options.
3. The student selects an answer (A–D).
4. Gemini evaluates the response and gives **personalized, constructive feedback**, including a helpful tip.

---

## Tech Stack

| Component       | Technology                     |
|----------------|---------------------------------|
|  Interface    | Google Colab (Python)           |
|  AI Engine     | Gemini Pro 1.5 (via API)        |
|  Language      | Python 3.11+                    |
|  Libraries     | `google-generativeai`, `getpass`|

---

## 🔧 Setup Instructions

1. Clone or download this repo / ZIP

2. Open the `tutor_app_colab.ipynb` file in [Google Colab](https://colab.research.google.com)

3. Install dependencies (if not already installed):
```python
!pip install -U google-generativeai
