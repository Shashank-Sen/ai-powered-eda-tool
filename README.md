 📊 LLM-Powered EDA Tool using Gradio + Mistral

 # 📊 LLM-Powered Exploratory Data Analysis (EDA) Tool

A powerful AI-driven EDA application built with **Gradio**, **Pandas**, and **Seaborn**, enhanced by **LLM-powered insights** using **Ollama's Mistral-7B**. This tool allows you to upload any CSV dataset and instantly receive visualizations, missing value reports, descriptive statistics, and intelligent AI-generated insights.

---

## 🚀 Features

✅ Upload any `.csv` dataset and perform instant EDA  
✅ AI-powered insights using Mistral-7B via [Ollama](https://ollama.com/)  
✅ Automatic handling of missing values (numeric + categorical)  
✅ Visualizations: histograms + correlation heatmaps  
✅ Clean, interactive Gradio interface  
✅ Works locally and supports public sharing via Gradio

---

---

## 🧠 How It Works

1. The user uploads a CSV file
2. The app:
   - Cleans missing values (median for numeric, mode for categorical)
   - Displays `df.describe()` and missing value report
   - Sends the summary to Mistral-7B (via Ollama) for natural language insights
   - Generates histograms and a correlation heatmap
3. All output is displayed in a clean Gradio interface

---
**Screenshots :**

<img width="800" height="500" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/0034d602-b5ca-4b02-a724-3de36795e7d0" />
<img width="600" height="400" alt="Age_distribution" src="https://github.com/user-attachments/assets/3dbd19ed-c17f-4e42-a2d0-edd2bd608cfe" />

---

📦 Example Use Cases
Quick EDA for data science projects

Business analysts exploring new datasets

Teaching automated data analysis

Insight generation using LLMs for non-technical users

---

Make sure you have Ollama installed and the Mistral model available:

**ollama run mistral**

---

Run the App:
**python app.py**

---
🔗https://www.linkedin.com/in/shashank-sen-
🔗 https://github.com/Shashank-Sen
