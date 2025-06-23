# 🤖 LLM Battle Arena

**LLM Battle Arena** is a Streamlit-based web application that lets you pit multiple Large Language Models (LLMs) against each other in fact-checking tasks.  
It supports diverse audiences, temperature settings, judges, and categories. You can compare model responses, visualize performance, and export results for further analysis.

---

## 🚀 Features

- **Model Comparison:**  
  - Battle any two LLMs (e.g., Mistral-7B, Llama-3-70B, DeepSeek-67B) and objectively compare their fact-checking abilities.
- **Flexible Configurations:**  
  - Choose from a predefined fact database or input your own statements.
  - Select the audience: Kid, Teenager, or Adult.
  - Tune the temperature: Low (0.3), Mid (0.7), or High (1.0).
  - Pick a judge LLM to evaluate the responses.
  - Filter by fact category (Science, Nature, Health, etc.).
- **Multiple Run Modes:**  
  - Single battle: Test one statement between two models.
  - Category batch: Run all facts in selected categories.
  - Full combinatorial: Test all possible model, judge, statement, audience, and temperature combinations.
- **Evaluation Metrics:**  
  - Correctness of response (True/False).
  - Quality of explanation (scale 1–5).
  - Justification provided (Yes/No).
  - Language appropriateness and tone neutrality.
- **Visualizations:**  
  - Interactive bar, radar, and line charts to analyze and compare results.
- **Export Options:**  
  - Download results and summary tables as CSV files.
- **Debugging Support:**  
  - Detailed logging to diagnose API or evaluation issues.

---

## 🧰 Prerequisites

- **Python 3.8+**
- **Together AI API Key:**  
  - Required to access LLM inference endpoints.
  - [Get your API key here](https://platform.together.xyz/)

---

## 📦 Installation

1. **Clone the repository (or copy the code):**

   ```bash
   git clone <your-repo-url>
   cd <project-folder>
