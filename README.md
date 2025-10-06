# 💼 AI Workforce EDA - Tech Layoffs Analysis  

## 📌 Project Overview  

This project performs **Exploratory Data Analysis (EDA)** on global **tech layoffs data**, 

exploring patterns in workforce reductions across companies, industries, and timeframes.

The analysis leverages **Pandas, NumPy, Matplotlib, and Seaborn** to uncover trends that reflect

the **economic and organizational shifts** in the technology sector.  

## 📂 Dataset  

**Source:** `tech_layoffs (1).csv`  

**Key Features:** 

- `company` → Name of the organization
- 
- `industry` → Sector of operation (e.g., FinTech, AI, Software)
-  
- `headquarter_location` → Company’s primary location
- 
- `reported_date` → Date when layoff was reported
- 
- `status` → Company’s market status (Public / Private)
-   
- `total_layoffs` → Number of employees affected  

## 🔍 Data Preprocessing  

✔ Converted `reported_date` to datetime format  

✔ Filled missing values in categorical columns with `"Unknown"`  

✔ Summarized dataset shape, info, and statistical descriptions  

✔ Removed/handled invalid or missing data points  


## 📊 Analysis & Visualizations  

### 🔹 Top Companies by Layoffs  

**bar chart** 

<img width="899" height="470" alt="image" src="https://github.com/user-attachments/assets/293bce85-a25e-4f4b-b96b-8d9052c3b6c6" />



### 🔹 Temporal Trends  

 **time-series plot**

 <img width="859" height="486" alt="image" src="https://github.com/user-attachments/assets/e562fc52-9998-443c-be37-9d11289f6974" />

### 🔹 Industry-Wise Analysis  

 **count plot**
 <img width="859" height="486" alt="image" src="https://github.com/user-attachments/assets/d18a87cb-413c-4f9b-b581-c6a846fc6018" />

### 🔹 Geographical Insights  

**headquarter-based count plot**

<img width="954" height="470" alt="image" src="https://github.com/user-attachments/assets/40e2e0af-5132-4b22-8dc7-178972b6c0d4" />


### 🔹 Company Status Distribution  

**comparison chart** 
<img width="540" height="393" alt="image" src="https://github.com/user-attachments/assets/9a76debc-c0e5-4caf-b45b-dedfcfd6c886" />


### 🔹 Layoff Size Distribution 

**histogram of total layoffs** 
<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/9bca0857-cd02-497e-91cd-9beb3b4c47fd" />

## Install dependencies with:  

pip install pandas numpy matplotlib seaborn


## 🧩 Tools & Libraries  

- **Pandas** → Data manipulation & cleaning
   
- **NumPy** → Numerical operations
   
- **Matplotlib** → Data visualization

- **Seaborn** → Advanced plotting & aesthetics  


## Key Insights

🔹 Industry Trends

Tech sectors such as Software, FinTech, and AI exhibit the highest layoff frequencies.

🔹 Temporal Patterns

Layoff activity spikes during specific economic periods, showing a cyclical pattern.

🔹 Geographical Focus

Layoffs are concentrated in major tech hubs, indicating the globalized nature of workforce dynamics.

🔹 Company Status

Both public and private firms face layoffs, but magnitudes often vary by market stability and funding conditions.

## ✅ Business Takeaways

Monitor industry-specific trends to anticipate potential workforce risks.

Use layoff pattern analysis for predictive workforce planning.

Highlight resilient sectors to guide investment or career choices.

Provide data-driven insights to HR and economic policy researchers studying tech labor trends.

