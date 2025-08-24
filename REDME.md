# 🕵️ Crime Data Analysis – Los Angeles  

## 📖 Introduction  
Los Angeles, California 😎 — The City of Angels, Tinseltown, the Entertainment Capital of the World!  

Famous for its warm weather, palm trees, sprawling coastline, and Hollywood, Los Angeles is also one of the most populated cities in the United States. With a large population comes not only glamour but also challenges — including a significant volume of crime.  

In this project, I support the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. The insights from this analysis can help law enforcement allocate resources effectively and tackle different types of crimes across various areas.  

---

## 🎯 Objectives  
- Clean and preprocess the crime dataset  
- Perform **exploratory data analysis (EDA)**  
- Identify **most frequent crime types**  
- Analyze **trends over time** (monthly/yearly)  
- Detect **high-crime locations & hotspots**  
- Visualize patterns with clear graphs  

---

## 📂 The Data  

This project uses a modified version of the original dataset, publicly available from **Los Angeles Open Data**.  

### crimes.csv  
| Column         | Description |
|----------------|-------------|
| `'DR_NO'`      | Division of Records Number (official case number). |
| `'Date Rptd'`  | Date reported (MM/DD/YYYY). |
| `'DATE OCC'`   | Date of occurrence (MM/DD/YYYY). |
| `'TIME OCC'`   | Time of occurrence in 24-hour format. |
| `'AREA NAME'`  | LAPD geographic patrol division (e.g., 77th Street Division). |
| `'Crm Cd Desc'`| Description of the crime committed. |
| `'Vict Age'`   | Victim’s age. |
| `'Vict Sex'`   | Victim’s gender (`F`, `M`, `X` for unknown). |
| `'Vict Descent'` | Victim’s descent/ethnicity code. |
| `'Weapon Desc'` | Weapon used (if applicable). |
| `'Status Desc'` | Current status of the case. |
| `'LOCATION'`    | Street address of the crime. |

---

## 🛠️ Tools & Technologies  
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Jupyter Notebook** – Analysis environment  

---

## 🔎 Approach  

1. **Data Cleaning**  
   - Removed duplicates  
   - Handled missing values  
   - Converted date/time to proper formats  

2. **Exploratory Data Analysis (EDA)**  
   - Crime distribution by type  
   - Trend analysis by month & year  
   - Location-based hotspots  
   - Victim demographics (age, gender, descent)  

3. **Visualization**  
   - Bar plots, line graphs, heatmaps  
   - Time-series plots for seasonal trends  

---

## 📊 Key Insights (Example)  
- Theft was the **most common crime type**  
- Crimes peaked during **late evenings & weekends**  
- Certain patrol areas consistently had **higher crime rates**  
- Victims were more often **young adults (18–30 years)**  

---

## 🚀 Future Scope  
- Build a **crime prediction model** using Machine Learning  
- Deploy an **interactive dashboard** (Streamlit/Flask)  
- Integrate with **real-time datasets** for live monitoring  

---

## 📌 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/crime-analysis.git
   cd crime-analysis
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```

4. Run the analysis notebook:  
   ```bash
   Crime_analysis.ipynb
   ```

---

## 🙌 Acknowledgements  
- Dataset: [Los Angeles Open Data](https://data.lacity.org/)  
- Project inspired by real-world **data analytics & public safety applications**  

---
