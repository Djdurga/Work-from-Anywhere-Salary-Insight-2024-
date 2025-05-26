# 💼 Work From Anywhere Salary Insight (2024)

This project explores global salary trends for remote-friendly roles in 2024 using real-world data. The goal is to uncover how compensation varies by role, geography, experience level, and company attributes, offering valuable insights for job seekers, employers, and policy-makers.

---

## 👩‍💻 Role: Data Analyst

As the **Data Analyst**, I was responsible for:

### ✅ 1. **Data Cleaning & Preprocessing**

* Loaded and validated the dataset using **Pandas**
* Removed duplicates, handled missing values, and ensured consistent formatting
* Standardized country names using the **`pycountry`** package
* Converted salary figures into USD for consistency
* Categorized features such as:

  * **Experience Level** (Entry, Mid, Senior, Executive)
  * **Company Size** (Small, Medium, Large)

---

### 📊 2. **Exploratory Data Analysis (EDA)**

Used Python libraries such as **Seaborn**, **Matplotlib**, and **Plotly** to explore trends and patterns:

#### Key Insights Discovered:

* **Highest-paying remote roles** globally
* **Salary variations** by country, experience level, and company size
* **Top-paying countries** for remote tech jobs
* **Salary trends** in different job categories (e.g., Data Scientist vs. Data Analyst)

#### Visualizations Created:

* Country-wise average salary bar charts
* Heatmaps showing salary distribution across the globe
* Box plots and swarm plots to compare salaries by experience
* Donut charts for company size distribution

---

### 🌍 3. **Geographical Salary Mapping**

* Used **Plotly** to create interactive choropleth maps
* Mapped salary distributions by employee and company locations
* Highlighted geographical disparities in remote work compensation

---

### 🧠 4. **Key Business Questions Addressed**

* What are the best-paying countries for remote tech professionals in 2024?
* How do salaries vary by experience level and company size?
* Which roles offer the highest median compensation?
* Are there any noticeable regional trends or anomalies?

---

## 📁 Dataset Overview

* **Source**: Real-world data collected for 2024
* **Features**:

  * `job_title`, `experience_level`, `employment_type`
  * `employee_residence`, `company_location`, `company_size`
  * `remote_ratio`, `salary_in_usd`, `currency`
* \~4,000 records representing remote-friendly jobs across 100+ countries

---

## 🛠️ Tools & Technologies

| Tool       | Purpose                      |
| ---------- | ---------------------------- |
| Python     | Data wrangling & analysis    |
| Pandas     | Data cleaning & exploration  |
| Seaborn    | Statistical visualizations   |
| Plotly     | Interactive geo-mapping      |
| PyCountry  | Country name standardization |
| Matplotlib | General plotting             |

---

## 📈 Outcome

This analysis helps:

* **Job seekers** understand where their skills are valued most
* **Companies** benchmark compensation globally
* **Researchers** identify salary equity trends in remote work

---

## 🔮 Next Steps

* Add regression modeling to predict salaries
* Integrate cost-of-living adjustment for more accurate comparisons
* Extend analysis with job descriptions and skill tags
