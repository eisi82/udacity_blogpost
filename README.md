# **Remote Work in Transition: Trends, Salaries & Company Size (2022–2025)**  
*Exploring remote work trends, salaries, and company size insights from 4 years of Stack Overflow Developer Surveys.*

---

## **📌 About This Project**  
This project (Write a Data Science Blog Post) is part of **Udacity Data Scientists Nanodegree Program.**
It demonstrates the full data science workflow using real-world survey data from the [**Stack Overflow Developer Survey**](https://survey.stackoverflow.co/) using **CRISP-DM Methology**.

---

## **📌 Project Overview**  
This project analyzes **Stack Overflow Developer Survey data (2022–2025)** to uncover how remote work has evolved and what factors influence its adoption.  

We answer three key questions:  
1. **How has remote work changed over time?**  
2. **Are there salary differences between remote, hybrid, and in-person roles?**  
3. **Is remote work more common in small or large companies?**  

---

## **🎯 Motivation**  
Remote work is no longer a trend—it’s a fundamental shift in how we work. But adoption varies by region, company size, and even compensation. This project aims to uncover these patterns and provide actionable insights for professionals, businesses, and policymakers.

---

## **📂 Data Source**  
- **Stack Overflow Developer Survey**: https://survey.stackoverflow.co/  
- Years: **2022–2025**  
- Focus: Full-time employees in **Europe, North America, India, and China**  
- Key variables:  
  - `SurveyYear`  
  - `Country` → grouped into regions according to the Definition of World-Regions by UN M49 Standard.  
  - `RemoteWork` → clustered into *Remote*, *Hybrid*, *In-person*  
  - `ConvertedCompYearly` (annual compensation)  
  - `OrgSize` → clustered into company size categories  

---

## **🛠️ Tech Stack**  
- **Python**: Data processing & analysis  
- **Pandas, NumPy**: Data wrangling  
- **Matplotlib, Seaborn**: Visualization  
- **Jupyter Notebook**: Interactive analysis  

---

## **📊 Key Insights**  
✔ Remote work peaked in 2022 but declined slightly afterward, while **hybrid work surged from 2024 onward**.  
✔ **Remote and hybrid roles generally pay more** than in-person roles, especially in North America.  
✔ **Company size matters**: Small firms lean remote, while large corporations favor hybrid flexibility.  
✔ Regional differences persist: **North America pays the most**, India the least.  

---

## **📈 Visualizations**  
The notebook includes:  
- **Stacked area charts**: Remote vs. Hybrid vs. In-person over time  
- **Line charts**: Median salary trends by work type and region  
- **Heatmaps**: Work model distribution by company size  

---

## **📁 Repository Structure**  
```
├── data/                # Raw survey data (not included in repo)
├── requirements.txt     # Requirements-File for this project
├── project.ipynb        # Jupyter Notebook with full analysis
├── README.md            # Project documentation
```

---

## **⚙️ How to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook project.ipynb
   ```

---

## **📝 Blog Post**  
For a detailed narrative and visual insights, check out the full article on Medium:  
👉 https://medium.com/@roman.eisenbarth/remote-work-in-transition-trends-salaries-and-company-size-2022-2025-d3e82ba88231

