
# 🚀 AI-Powered Student Learning Behavior Analyzer

### *A Multi-Agent System for Automated Educational Data Analysis*

**Kaggle × Google — AI Agents Intensive Capstone Project**

---

## 📌 Overview

The **AI-Powered Student Learning Behavior Analyzer** is a multi-agent system designed to help educators, institutions, and data practitioners analyze student behavior patterns, identify learning gaps, and predict academic outcomes with minimal manual effort.

This project automates an entire data workflow using intelligent agents — from data cleaning to SQL query generation to reporting. By leveraging the LearnLytics 2.0 dataset, the system demonstrates how AI agents can collaborate to solve real educational challenges.

This project is submitted under the **Agents for Good** track.

---

## 🎯 Problem Statement

Educational institutions collect大量 data on students — attendance, study habits, parental background, performance, and more.
Yet **analyzing this data manually is time-consuming, inconsistent, and prone to human error**.

Teachers and administrators often struggle to:

* Identify at-risk students early
* Understand performance drivers
* Detect learning behavior patterns
* Generate insights quickly
* Build reports consistently

This project solves these problems by creating an **AI Data Analyst** that automates the entire process.

---

## 🤖 Why Agents?

A single AI model can’t handle the entire workflow effectively.
But **multi-agent systems** allow specialization:

* One agent cleans the data
* One agent finds insights
* One agent writes SQL
* One agent generates a report
* One orchestrator agent manages the workflow

Agents collaborate just like a team of data analysts — making the solution scalable, modular, and easy to extend.

---

## 🧠 System Architecture

```
User → Orchestrator Agent → (Cleaning Agent, Insights Agent, SQL Agent, Report Agent)
                            ↘ Memory Store ↙
               Dataset → Cleaning Agent → Insights → SQL → Report → Final Output
```

> Full detailed architecture diagram included in `/assets/architecture.png` (add once created).

---

## 🗂️ Folder Structure

```
├── notebook.ipynb                # Full Kaggle notebook
├── README.md                     # This file  
├── student_data.csv (optional)   # Dataset reference link
├── assets/                       # Architecture diagrams, images
    ├── architecture.png
    └── thumbnail.png
    └── visualizations.png

```

---

## 📊 Dataset — LearnLytics 2.0

**Student Learning Behavior Dataset (`student_data.csv`)**

Contains student attributes such as:

* Demographics
* Study behavior
* Attendance
* Assignments
* Parental background
* Past grades
* Final grade (target)

This dataset is perfect for showcasing agent-driven analysis.

---

## 🔧 Features (Core Agent Capabilities)

### 1. 🧹 Data Cleaning Agent

* Standardizes column names
* Handles missing values
* Cleans inconsistent entries
* Logs cleaning decisions to memory

### 2. 🔍 Insights Agent

* Finds trends and correlations
* Identifies performance patterns
* Detects behavior-based segments

### 3. 📝 SQL Query Agent

* Converts natural language → SQL
* Explains the logic behind queries
* Saves all generated queries in memory

### 4. 📄 Report Generator Agent

* Creates a polished Markdown report
* Summaries insights, patterns, suggestions
* Fully auto-generated

### 5. 🧩 Orchestrator Agent

* Controls the entire workflow
* Calls agents in sequence
* Stores & retrieves memory
* Ensures a clean pipeline

---

## 🧪 Demo (Notebook Included)

The full demonstration is available in the Kaggle Notebook:

👉 **Link to Kaggle Notebook**
*([Kaggle Notebook](https://www.kaggle.com/code/deepakpatil10/capstone-project))*

The notebook includes:

* Dataset ingestion
* Multi-agent workflow execution
* Auto-generated SQL queries
* Data insights
* Visualizations
* Final report creation

---

## 🛠️ Tech Stack

* **Python 3.10+**
* **Pandas** for data processing
* **Matplotlib / Seaborn** for visuals
* **Gemini 1.5** for LLM reasoning
* **Google AI Agent framework**
* **Kaggle Notebooks**

---

## ⚙️ How To Run Locally

```bash
git clone https://github.com/deepakp2410/Capstone_Project
cd learnlytics-agent-analyzer

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## 📈 Visualizations

Your notebook includes:

* **Final Grade Distribution**
* **Parental Education Levels**
* **Attendance vs Final Grade Scatterplot**

These help validate agent-generated insights.

---

## 📑 Final Output

The system generates:

* Cleaned dataset
* SQL queries
* Insights summary
* Markdown report
* Visualizations

The final report is saved to:

```
/tmp/ai_data_analyst_report.md
```

---

## 🧩 If I Had More Time…

With more time, I would:

* Add a **Prediction Agent** to forecast final grades
* Deploy the agent system using **Vertex AI Agent Engine**
* Build an interactive dashboard for real-time analysis
* Add long-term memory using vector embeddings
* Support multiple datasets and schema auto-detection
* Build a web UI

---

## ⭐ Acknowledgements

Special thanks to:

* **Google AI** for the multi-agent framework
* **Kaggle Team** for organizing the 5-Day AI Agents Intensive
* **Gemini models** for powering the reasoning

---

## 📬 Contact

**Deepak Patil**  
AI + Data Science | Educational Analytics   
🔗 GitHub: https://github.com/deepakp2410 
📧 Email: deepakpatil6243@gmail.com 
🔗 GitHub: https://www.linkedin.com/in/deepak-patil-23772b252/ 

---
