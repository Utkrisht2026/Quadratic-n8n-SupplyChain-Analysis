# 📦 AI-Driven Supply Chain Data Analysis using Quadratic & n8n

This project demonstrates how AI tools like **Quadratic** (AI spreadsheet) and **n8n** (workflow automation) can streamline **data analysis and process automation** in a supply chain environment.

You'll find:
- Setup guides for automation tools
- Supply chain datasets
- Prompt templates for AI-driven insights
- Step-by-step analysis exercises using Quadratic

---

## 🎯 Project Objectives

- Automate data processing and notification flows using n8n
- Use Quadratic to perform EDA on supply chain datasets
- Gain insights into supply chain performance (orders, fulfillment, delivery)
- Showcase AI and no-code tools in real-world business analysis

---

## 🧰 Tools & Technologies

| Tool       | Purpose                                      |
|------------|----------------------------------------------|
| **Quadratic** | Perform AI-assisted spreadsheet analysis     |
| **n8n**     | Automate workflows (ETL, alerting, emailing) |
| **Supabase** | PostgreSQL cloud database                   |
| **Gmail API** | For sending automated alerts               |
| **Python/Pandas** | (Optional) Extend analysis manually       |

---

## 📂 Repository Structure

📁 Dataset/
└── Dataset/
📄 1_N8n_Setup_in_Local_Host.pdf
📄 2_Setup_a_Postgres_DB_in_Supabase.pdf
📄 3_Creating_OAuthClientID_for_Gmail_API.pdf
📄 Quadratic_Exercises.pdf
📄 Required_Prompts.pdf
📄 SC_Concepts_Example.xlsx
📄 Supply_Chain_Concepts.pdf
📄 fact_aggregate.csv
📄 fact_order_line.csv


---

## 📊 File Descriptions

### 🔧 Setup & Configuration
- `1_N8n_Setup_in_Local_Host.pdf`  
  ➤ How to install and configure n8n locally  
- `2_Setup_a_Postgres_DB_in_Supabase.pdf`  
  ➤ Guide to creating a hosted database in Supabase  
- `3_Creating_OAuthClientID_for_Gmail_API.pdf`  
  ➤ How to enable Gmail API for workflow alerts  

### 📘 Concepts & Exercises
- `Supply_Chain_Concepts.pdf`  
  ➤ Overview of key supply chain KPIs and metrics  
- `SC_Concepts_Example.xlsx`  
  ➤ Sample Excel calculations and dashboards  
- `Quadratic_Exercises.pdf`  
  ➤ Hands-on EDA tasks using Quadratic  
- `Required_Prompts.pdf`  
  ➤ AI prompt templates to automate workflows and insights

### 📈 Datasets
- `fact_aggregate.csv`  
  ➤ Aggregated metrics like order volumes, fulfillment rates  
- `fact_order_line.csv`  
  ➤ Detailed transactional data for EDA and automation

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/Utkrisht2026/Quadratic-n8n-SupplyChain-Analysis.git


## 🚀 How to Use This Project

Follow these steps to set up, analyze, and automate using this project:

### 🔧 Step-by-Step Setup

1. **Set up the local n8n environment**  
   📄 Refer: `1_N8n_Setup_in_Local_Host.pdf`

2. **Create a PostgreSQL database in Supabase**  
   📄 Refer: `2_Setup_a_Postgres_DB_in_Supabase.pdf`

3. **Configure Gmail API for automated email alerts**  
   📄 Refer: `3_Creating_OAuthClientID_for_Gmail_API.pdf`

---

### 📊 Load and Analyze the Data

4. **Load the datasets for analysis:**
   - `fact_aggregate.csv` – Summary-level supply chain data
   - `fact_order_line.csv` – Detailed transactional order data

   💡 You can use:
   - **Quadratic** → for AI-powered Exploratory Data Analysis (EDA)
   - **Supabase** → as a backend if using workflows with **n8n**

---

### 🤖 Automate Insights & Alerts

5. **Use** `Required_Prompts.pdf` **to:**
   - Generate AI-powered analysis questions
   - Trigger reports or alerts using n8n
   - Customize workflows based on your data needs

6. **(Optional)** Extend your automation by integrating:
   - Slack, Google Sheets, Airtable
   - Other third-party APIs via **n8n**



## 📚 References

- [Quadratic Documentation](https://docs.quadratichq.com/)
- [n8n Documentation](https://docs.n8n.io/)
- [Supabase Documentation](https://supabase.com/docs)
- [Google OAuth Client Setup Guide](https://developers.google.com/identity/protocols/oauth2)


## 🚀 Author

**Utkrisht Jalan**  
Aspiring Data Analyst | Python, SQL, Power BI, Excel  
[GitHub Profile](https://github.com/Utkrisht2026)

---

## ⭐️ If you found this useful, feel free to give it a star!
