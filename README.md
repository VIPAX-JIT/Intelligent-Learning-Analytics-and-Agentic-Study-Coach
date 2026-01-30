# Intelligent-Learning-Analytics-and-Agentic-Study-Coach
Project 2: Intelligent Learning Analytics and Agentic Study
Coach
Project Objective
Design and implement an AI-powered learning analytics system that analyzes student perfor-
mance data and generates study recommendations. The system is progressively extended into
an agentic AI study coach that reasons about learning gaps, retrieves resources, and produces
personalized study plans.
Constraints and Requirements
• Team size: 3–4 students
• Paid APIs are not permitted
• Only free-tier APIs or open-source models may be used
• A user interface is mandatory
• Final application must be publicly hosted
• Localhost-only demonstrations will not be accepted
2.1 Dataset
• https://www.kaggle.com/datasets/spscientist/students-performance-in-exams
• https://archive.ics.uci.edu/ml/datasets/student+performance
Recommended Tools (Not Mandatory)
• ML libraries: scikit-learn, NumPy, pandas
• NLP tools (optional): NLTK, spaCy
• LLMs (Milestone 2): Open-source models or free-tier APIs
• Agent workflow: LangGraph (recommended for Milestone 2)
• UI: Streamlit or Gradio
• Hosting: Hugging Face Spaces, Streamlit Community Cloud, Render (free tier)
2.2 Dataset
• https://www.kaggle.com/datasets/Cornell-University/arxiv
Milestone 1: ML-Based Learning Analytics System (Mid-Sem)
Objective
Build a data-driven learning analytics system using classical machine learning techniques to
analyze student performance and generate basic study recommendations.
7
Inputs
• Student performance dataset (CSV) containing:
– Quiz or test scores
– Topic-wise accuracy
– Time spent per topic
Functional Requirements
• Perform data preprocessing (handling missing values, scaling)
• Predict student performance or risk level
• Classify students into categories such as:
– At-risk
– Average
– High-performing
• Generate rule-based or ML-based study recommendations
Technical Requirements
• Supervised learning models (e.g., Logistic Regression, Linear Regression)
• Optional clustering for learner grouping (e.g., K-Means)
• Model evaluation using appropriate metrics
User Interface Requirements
• Upload student data
• Display predictions and classifications
• Show generated study recommendations
Milestone 1 Deliverables
• Problem understanding and use-case description
• Input–output specification
• System architecture diagram (ML pipeline)
• Working application with a basic UI
• Brief analysis of model performance and limitations
Milestone 2: Agentic AI Study Coach (End-Sem)
Objective
Extend the analytics system into an autonomous AI study coach that reasons about student
performance, plans learning strategies, and adapts recommendations.
8
Functional Requirements
• Accept student goals (e.g., exam preparation, skill improvement)
• Diagnose learning gaps using performance data
• Generate a multi-step personalized study plan
• Retrieve and summarize relevant learning resources
• Maintain session-based memory (optional)
Technical Requirements
• Integration of open-source or free-tier LLMs
• Retrieval-augmented generation (optional but recommended)
• Agentic workflow using LangGraph or equivalent
• Prompt strategies to ensure reliable recommendations
Structured Output Requirements
The generated study coach report must include:
• Learning diagnosis
• Personalized study plan
• Weekly or milestone-based goals
• Recommended learning resources (URLs)
• Progress feedback or next steps
Extension (Choose Any One)
• Quiz or practice question generation
• Adaptive difficulty adjustment
• PDF export of study plan
• Multi-student analytics dashboard
Final Deliverables
• Publicly accessible hosted application link
• GitHub repository with complete codebase
• Demo video (5–7 minutes)
