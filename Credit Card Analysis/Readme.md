# 💳 Credit Card Transaction & Customer Analysis Using Power BI  

## 📸 Dashboard Preview  

### Transaction Analysis Dashboard  
![Transaction Dashboard](https://drive.google.com/file/d/1ZS061McqNRIIKe8cmMJTo2rHZNVTb4ve/view?usp=sharing)  

### Customer Analysis Dashboard  
![Customer Dashboard](https://drive.google.com/uc?id=10ZTt88Uzeuq8_oBKz_13_S_t8U118S85D)  


## 📌 Project Overview  
This project presents an **interactive Power BI dashboard** analyzing credit card transactions and customer demographics.  
It provides insights into **revenue trends, transaction volumes, customer segments, and spending patterns** to help financial institutions optimize marketing strategies and improve customer engagement.  

---

## 🎯 Objectives  
- Extract and transform **credit card transaction data** from **PostgreSQL** into Power BI.  
- Build dashboards to track **55M+ revenue, 44M+ transaction amounts, and 650K+ records** across cards and customers.  
- Identify key business insights such as **high-value customers, spending behavior, and card category performance**.  

---

## 📊 Dashboard Features  
- **Revenue & Transactions Analysis**  
  - Quarterly revenue and transaction count trends  
  - Revenue by **expenditure type** (bills, fuel, grocery, travel, etc.)  
  - Channel usage (**swipe, chip, online**)  

- **Customer Insights**  
  - Demographics: **age, gender, salary, marital status**  
  - Segmentation by **education, job type**  
  - Top 5 states contributing to revenue  

- **Card Performance**  
  - Revenue by **card category** (Blue, Silver, Gold, Platinum)  
  - Customer acquisition cost and profitability  

---

## 🔑 Key Insights  
- **Blue Card** dominates revenue with **$46M+**, but higher-tier cards (Gold/Platinum) generate more interest income.  
- **Graduates and businessmen** are top spenders; **age group 60+** contributes the highest revenue.  
- **Top states**: California, Texas, New York, Florida, and New Jersey.  
- **Swipe transactions** lead by a wide margin compared to chip/online payments.  

---

## 🛠️ Tech Stack  
- **Database**: PostgreSQL  
- **Visualization Tool**: Power BI  
- **Data Processing**: SQL, DAX, Power Query  

---

## 📂 Project Structure  
├── data/ # Raw and transformed datasets
├── queries/ # SQL scripts for data extraction
├── dashboards/ # Power BI files (.pbix)
└── README.md # Project documentation


---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/credit-card-analysis.git
2. Import SQL scripts from the queries/ folder into PostgreSQL and load data.
3. Open the .pbix file in Power BI Desktop.
4. Connect Power BI to PostgreSQL database (update connection string).
5. Explore the interactive dashboards.
