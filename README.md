# 📊 Nasdaq-100 Stock Market Analysis

## 🎯 Objective
This project analyzes the performance of Nasdaq-100 companies by classifying them into sectors and summarizing their stock trends using AI-powered insights. The goal is to help investors and analysts understand sector trends, top performers, and potential risks.

## 🔍 Overview
Financial markets generate vast amounts of data daily, making it challenging to extract meaningful insights. This project automates the process by:
- Classifying Nasdaq-100 companies into relevant sectors.
- Analyzing stock price changes over different timeframes (1D, 1M, 1Y, etc.).
- Generating AI-driven insights on sector and company performance.

## 🛠️ Approach
1. **Data Collection**: 
   - Used datasets containing Nasdaq-100 company details and stock price changes.
   - Merged data for comprehensive analysis.

2. **Sector Classification**:
   - Leveraged OpenAI’s API to classify companies into sectors based on their names and descriptions.
   - Addressed inconsistencies in sector Classification to ensure accuracy.

3. **Performance Analysis**:
   - Examined stock price changes over multiple periods (1D, 1Y, Max, etc.).
   - Aggregated data at the sector level to analyze trends.

4. **AI-Generated Insights**:
   - Asked OpenAI to summarize key trends in top and bottom-performing sectors and companies.
   - Extracted investment opportunities and risks based on stock movements.

## 📈 Insights & Findings
### 🔼 Top-Performing Sectors & Companies
- **Entertainment** (e.g., Netflix) soared due to increasing demand for digital content.
- **Travel & Tourism** (e.g., Booking Holdings) rebounded as post-pandemic travel increased.
- **Energy Services** (e.g., Baker Hughes) benefited from rising oil prices and economic recovery.

### 🔽 Underperforming Sectors & Companies
- **FinTech** (e.g., PayPal) struggled due to increased competition and regulatory scrutiny.
- **Cybersecurity** (e.g., CrowdStrike) faced challenges from shifting industry priorities.
- **Utilities** (e.g., American Electric Power) underperformed due to market shifts and rising interest rates.

### 💡 Investment Insights
- Sectors like **Entertainment, Travel, and Energy** present growth opportunities.
- **Caution** is advised in FinTech and Cybersecurity due to evolving risks.
- Investors should assess companies' adaptability before making decisions.

## ⚙️ Technologies Used
- **Python** Programming language and data processing (Pandas)
- **Plotly** for data visualization
- **OpenAI API** for sector classification and insights
- **Jupyter Notebook** for development and testing

## 🤔 Challenges Faced
### 1️⃣ **Sector Classification Issues**
- Initially, OpenAI classified the 100 companies into **40+ unique sectors**, many of which were too specific.
- **Solution:** Mapped these sectors into **26 broader categories** for clarity and consistency.

### 2️⃣ **Handling Missing & Noisy Data**
- Some companies lacked clear sector labels or had inconsistent naming conventions.
- **Solution:** Applied rule-based filtering and manual verification to ensure accurate classifications.

### 3️⃣ **API Costs & Rate Limits**
- Running OpenAI API queries on large datasets can be costly and slow.
- **Solution:** Optimized API calls by caching results and batching requests.

### 4️⃣ **Interpreting AI Output**
- Some AI-generated insights were vague or lacked clear explanations.
- **Solution:** Structured the prompt carefully and post-processed responses to ensure coherence.

##  Future Improvements
- **Expand Data Sources**: Incorporate earnings reports and macroeconomic indicators.
- **Refine AI Prompts**: Improve question structuring for deeper insights.
- **Automate Classification**: Train a custom model to reduce reliance on OpenAI API.
- **User Dashboard**: Develop an interactive web app for investors to explore insights in real-time.

---
📌 *This project provides a data-driven approach to understanding Nasdaq-100 performance, helping analysts make informed investment decisions!*

