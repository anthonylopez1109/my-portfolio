# my-portfolio
# [Project 1: Stock Analysis of the American Phone Market (Apple vs. Samsung during the Covid-19 Pandemic)](https://github.com/Jeniquef/stock-Analysis_t2)

# Overview:
This project explores the stock performance of Apple and Samsung during the Covid-19 pandemic, comparing their resilience to other tech companies in the market. It aims to understand how external factors, such as lockdowns and supply chain disruptions, influenced stock prices and investor sentiment.

# Key Insights:
- Analyzed stock trends before, during, and after the pandemic.
- Examined trading volumes and volatility changes for Apple and Samsung.
- Compared stock performance against the broader technology sector.
- Identified key factors influencing stock price fluctuations, such as external market events and operational challenges.
- Gained insights on business model resilience and recovery strategies.

# Data Sources:
- Yahoo Finance
- Statista
# Add Statista my_plot1

# [Project 2: Crowdfunding ETL Project](https://github.com/DanOMearaWD/Crowdfunding_ETL)

# Overview:
This project involved building an ETL pipeline using Python, Pandas, and PostgreSQL to extract, clean, and load data from a crowdfunding platform. The goal was to structure the raw data into a well-organized database for analysis and integration.

# Key Insights:
-Data Structuring: Successfully cleaned and transformed unstructured crowdfunding data into structured CSV files.
-Category & Subcategory Creation: Extracted 9 unique categories and 24 subcategories, enabling better organization of campaigns.
-Database Design: Designed a PostgreSQL database schema based on an Entity Relationship Diagram (ERD) to ensure efficient data relationships.
-Contact Data Parsing: Cleaned and structured contact information using regular expressions and Python’s JSON module.

# Data Sources:
crowdfunding.xlsx: Crowdfunding campaign data.
contacts.xlsx: Contact information for users associated with campaigns.

Add Image:
(You can include the ERD diagram image here or a relevant screenshot of the data flow or pipeline.)



---

## 📈 Project 1: Stock Analysis of the American Phone Market

### Overview:
This project explores the stock performance of **Apple** and **Samsung** during the **Covid-19 pandemic**, comparing their resilience to other tech companies in the market. It aims to understand how external factors, such as lockdowns and supply chain disruptions, influenced stock prices and investor sentiment.

### Key Insights:
- Analyzed stock trends **before, during, and after** the pandemic.
- Examined trading volumes and **volatility changes** for Apple and Samsung.
- Compared stock performance against the broader **technology sector**.
- Gained insights on **business model resilience** and **recovery strategies**.

### Data Sources:
- **Yahoo Finance**
- **Statista**
![my_plot1](https://github.com/user-attachments/assets/cf3f2023-2f28-43c0-b258-8ecff3d49442)
### Stock Performance Graph:

The graph above visualizes the stock price trends of **Apple** and **Samsung** before, during, and after the **Covid-19 pandemic**. As seen in the chart, both companies experienced significant volatility, with a sharp decline in stock prices at the start of the pandemic. Apple’s stock recovered faster than Samsung’s, demonstrating resilience in comparison to its competitor. This trend reflects market sentiment and the companies’ ability to adapt during global disruptions.



---

## 🔄 Project 2: Crowdfunding ETL Pipeline

### Overview:
This project involves building an **ETL (Extract, Transform, Load) pipeline** for a crowdfunding platform. Using **Python**, **Pandas**, and **PostgreSQL**, I extracted data from provided spreadsheets, cleaned and transformed it into structured DataFrames, and loaded the data into a PostgreSQL database.

### Key Components:
- **ETL Process**: Extracted data from **crowdfunding.xlsx** and **contacts.xlsx**, transformed it, and loaded into CSVs and PostgreSQL.
- **Database Design**: Created an **Entity Relationship Diagram (ERD)** and designed a **PostgreSQL schema** for the crowdfunding database.
- **Data Export**: Exported structured data into **CSV files** for further analysis.

### Data Files:
- crowdfunding.xlsx (Crowdfunding campaign data)
- contacts.xlsx (Contact information for campaigns)
- **CSV Files**:
  - category.csv
  - subcategory.csv
  - campaign.csv
  - contacts.csv
- **SQL Schema**: crowdfunding_db_schema.sql

![ERD](https://github.com/user-attachments/assets/608fe7ce-b260-4ca0-90c7-6e705dbbe412)
### **ERD: Entity Relationship Diagram**

The **Entity Relationship Diagram (ERD)** above represents the relationships between key entities in the crowdfunding database. It provides a visual overview of how data is structured and connected across various tables, including **campaigns**, **categories**, **subcategories**, and **contacts**.

#### **Key Tables:**
- **Campaign Table**: Stores details about each crowdfunding campaign, including its **goal**, **amount pledged**, and **dates**.
- **Category & Subcategory Tables**: Define the categorization of campaigns (e.g., **Film & Video**, **Technology**) and further classify them into **subcategories** (e.g., **Animation**, **Mobile Games**).
- **Contacts Table**: Stores **contact information** associated with campaigns, helping to link users with their respective campaigns.


#### **Relationships:**
- The **Campaign Table** is linked to both the **Category** and **Subcategory** tables via **foreign keys**.
- The **Contacts Table** connects to the **Campaign Table**, linking each user to a specific campaign they’re associated with.

This ERD helps to understand the **data model** and how the different entities are related, forming the foundation for the **ETL process** and subsequent database operations.

---

## 🌍 Project 3: Flu Trends Analysis and Visualization

### Overview:
This project focuses on creating an interactive **dashboard** to visualize **flu trends** across the United States, based on **age groups** and **virus types**. The dashboard provides insights into flu activity, mortality rates, and regional trends, assisting in **public health decision-making**.

### Key Features:
- **Interactive Dashboards**: Built using **Dash** and **Plotly**, allowing users to interact with flu data through filters.
- **Data Sources**: Data from **CDC FluView Interactive** and the **National Center for Health Statistics**.
- **Ethical Considerations**: All data was anonymized and handled according to **CDC guidelines** to ensure privacy and accuracy.

### Tools Used:
- **Pandas**: Data manipulation and cleaning
- **Matplotlib**: Static visualizations
- **Plotly/Dash**: Interactive visualizations and dashboards
- **SQLAlchemy**: For loading data from a **PostgreSQL database**

### Instructions:
1. Clone this repository and navigate to the project directory.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Dashboard: python app.py

![figure3](https://github.com/user-attachments/assets/c9fa02b2-17b9-4972-bfb5-b0d954b47ebb)
### 🌍 **Flu Activity Choropleth Map**

The **flu activity choropleth map** above provides an interactive view of the **flu activity** across the United States at the **state level**. The color intensity of each state corresponds to the **flu activity level**, with darker shades indicating **higher flu activity**.

🔍 **Key Features:**
- The color intensity indicates the **severity of flu activity**, with **darker shades** representing **higher activity**.
- **Hover over each state** to see specific data points, such as flu activity levels, number of cases, and hospitalization rates.
- **Explore trends over time** by selecting different time periods to see changes in flu activity.

📊 **Insights:**
- Identify regions with **high flu transmission** to support **targeted public health responses**.
- Track flu trends to predict future outbreaks and inform **vaccination and healthcare efforts**.

---

### 📚 **Data Source**
The data is sourced from the **CDC FluView Interactive**, offering a comprehensive view of **influenza trends**. This data can assist:
- **Public health officials** in tracking flu spread and making timely decisions.
- **Researchers** studying flu patterns and effectiveness of interventions.
- The **general public** in understanding flu transmission and prevention.



 





