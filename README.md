# Hackathon Startup Decision Support System (SRS)

## Overview
The **Venture Companion** is a data-driven platform designed to empower entrepreneurs by providing **actionable recommendations** based on **industry-specific KPIs**. This project was developed as part of a hackathon challenge to assist startups in aligning their business strategies with market trends and insights.

---

## Features
1. **Data Scraping**:
- Data Scraping:
- Collects relevant data from industry-specific sources such as news headlines, KPI databases, and public datasets to ensure up-to-date and accurate insights.
- Employs web scraping techniques to fetch real-time data for dynamic analysis.
2. **Analytical Skills**:
- Performs data analysis using tools like Pandas or Excel to clean, organize, and preprocess data for further insights.
- Conducts statistical analysis to identify trends and patterns in key performance indicators (KPIs).
3. **Sentiment Analysis**:
   - Analyzes industry news headlines using NLP techniques.
   - Classifies headlines into **positive**, **negative**, or **neutral** sentiment.

4. **Trend Analysis**:
   - Uses historical data and machine learning models like linear regression to identify KPI trends over time.
   - Provides insights into past performance and future projections.

5. **AI-Driven Recommendations**:
   - Combines sentiment and trend analysis to generate **top 10 strategic recommendations** tailored to specific industries and KPIs.

6. **Interactive Dashboard**:
   - Users can interact with the platform via a responsive web interface, receiving visualized insights and data-driven guidance.

---

## Dataset
- **File**: `startup_kpi_data.csv`
- **Contents**:
  - Industry-specific metrics (e.g., SaaS, FinTech, Gaming).
  - KPIs: Customer Acquisition Cost (CAC), Monthly Recurring Revenue (MRR), Churn Rate, Net Promoter Score (NPS), etc.
  - News headlines summarizing trends and developments from 2011 to 2024.

## Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - **Data Analysis**: Pandas, NumPy
  - **Visualization**: Matplotlib
  - **Machine Learning**: Scikit-learn
  - **Natural Language Processing**: Hugging Face Transformers (for sentiment analysis)
  - **Backend Framework**: Flask (optional for deployment)
- **Other Tools**:
  - `.env` for environment variables
  - `Gradio` for a user-friendly interface (optional)

## Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nikhitagollamudi/Hackathon-SRS
2. **Create a virtual environment**:

- Use the command: python -m venv venv
- Activate the virtual environment:
- On Linux/macOS: source venv/bin/activate
- On Windows: venv\Scripts\activate
3. **Install dependencies**:

- Run: pip install -r requirements.txt
4. **Run the Project**:
- Execute the main script:
- Run: python src/client.py
5. **Optional: Run Tests**
- Execute tests to ensure functionality:
- Run: pytest tests/


## Contributors
- Sai Navya Jyesta
- Nikhita Gollamudi
- Venkata Kalyani Vemula
- Madhughnea Sai Adabala
   
