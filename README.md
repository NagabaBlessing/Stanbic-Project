# Stanbic-Project
## Customer Complaint Analysis using NLP
### Case Study: Stanbic Bank Uganda

![NLP](https://img.shields.io/badge/NLP-Topic%20Modeling-green)
![Model](https://img.shields.io/badge/Model-BERT%20%7C%20LDA-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)



# Project Overview

Banks receive thousands of customer complaints every year. Most of these complaints are **unstructured text**, making them difficult to analyze using traditional data analysis methods.

This project applies **Natural Language Processing (NLP)** and **Topic Modeling** to analyze customer complaints related to **Stanbic Bank Uganda** in order to uncover major service issues and support data-driven decision making.

The analysis converts raw complaint text into **structured insights**, revealing the most common customer problems and operational bottlenecks.


# Project Objectives

The goals of this project were to:

• Convert **unstructured complaint text into structured insights**    

• Discover hidden complaint patterns using **topic modeling**

• Provide insights that can help improve **banking service quality**


# Dataset Description

The dataset contains customer complaint records with the following fields:

| Column | Description |
|------|-------------|
| `case_number` | Unique complaint identifier |
| `date_created` | Date the complaint was recorded |
| `category` | Complaint category |
| `description` | Detailed customer complaint text |


#  Project Workflow

The project followed the following workflow:
Customer Complaint Data
↓
Data Cleaning
↓
Text cleaning and Preprocessing using NLP preprocessing techniques
↓
Exploratory Data Analysis to identify general patterns within the complaint dataset
↓
Word Frequency & WordCloud to highlight the most frequent complaint phrases
↓
Topic Modeling to automatically discover hidden themes in the complaint data. 
↓
Model Evaluation: Two models were implemented and compared
↓
Insights & Recommendations

## 1️ Latent Dirichlet Allocation (LDA)

## 2️ BERT-Based Topic Modeling


# Model Comparison

| Model | Coherence Score | Interpretation |
|------|------|------|
| LDA | 0.4 | Moderate topic clarity |
| BERT | 0.7 | Strong contextual topic quality |

The results indicate that **BERT produces more coherent and meaningful topics compared to LDA**.

# Temporal Complaint Analysis
Temporal features were extracted from complaint timestamps to analyze trends over time.
This analysis can help banks **optimize support staffing and system maintenance schedules**.

# Key Insights

Major findings from the analysis include:

• **Cash advance related complaints were highly frequent**

• Many complaints involved **account debits without successful transactions**

• **Delayed transaction reversals** were a common issue

• **Account access problems** such as blocked accounts appeared frequently

• Complaint patterns suggest operational issues in **transaction processing and customer support response times**


# Technologies Used
Programming & Data Analysis
- Python
- Pandas
- NumPy

Visualization
- Matplotlib
- Plotly
- WordCloud

Natural Language Processing
- NLTK
- Scikit-learn
- Gensim
- BERT (Transformer-based embeddings)
- LDA

# Repository Structure
customer-complaint-analysis/
│
├── data/
│ └── complaints_dataset.csv
│
├── notebooks/
│ └── complaint_analysis.ipynb
│
├── outputs/
│ ├── wordcloud.png
│ ├── temporal_analysis.png
│ └── topic_visualization.png
│
└── README.md

# Conclusion

This project demonstrates how **Natural Language Processing and Topic Modeling** can be used to analyze customer complaint data and extract actionable insights.

By identifying recurring service issues and operational bottlenecks, financial institutions can improve:

• Customer experience  
• Transaction reliability  
• Complaint response strategies  

# Disclaimer
This project was conducted **for academic and analytical purposes** using complaint data related to **Stanbic Bank Uganda**. The analysis is intended for educational demonstration and does not represent official bank reporting.