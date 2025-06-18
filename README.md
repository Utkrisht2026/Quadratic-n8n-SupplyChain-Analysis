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
Follow the PDF guides in this order:

Set up local n8n environment

Create a database in Supabase

Configure Gmail API for alerts

Load the datasets (fact_aggregate.csv, fact_order_line.csv) into:

Quadratic (for EDA)

Supabase (if using n8n workflows)

Use Required_Prompts.pdf to test AI queries, automate insights, or trigger actions (like alerts or reporting).

(Optional) Extend workflows by integrating Slack, Google Sheets, or third-party APIs using n8n.

📚 References
Quadratic Docs

n8n Docs

Supabase Docs

Google OAuth Client Setup

👨‍💻 Author
Utkrisht Jalan
Aspiring Data Analyst | Passionate about automation, AI, and simplifying data workflows

🔗 GitHub

🧠 Tools: SQL · Python · Power BI · Excel · n8n · Quadratic

🧩 Fun fact: I love finding the smartest way to automate manual tasks!
