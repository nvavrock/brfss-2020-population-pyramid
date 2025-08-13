# BRFSS 2020 Population Pyramid Analysis

Visualized **400K+** survey responses from the CDC's Behavioral Risk Factor Surveillance System (BRFSS) as a population pyramid, highlighting demographic patterns by age and sex.  
Built using **RStudio** and **ggplot2**.

---

## 📊 Overview
The BRFSS is the largest continuously conducted health survey in the world, collecting data on health-related behaviors, chronic conditions, and preventive services from U.S. adults.  
This project focuses on visualizing the population structure of survey respondents using a population pyramid — a chart that shows the distribution of a population by age group and sex.

---

## 🛠 Tools & Technologies
- **RStudio**  
- **ggplot2**  
- **dplyr**  
- **tidyr**

---

## 🔍 Process
1. Imported the 2020 BRFSS dataset (LLCP2020.XPT).
2. Cleaned and filtered the dataset to include key demographic variables.
3. Created grouped counts by age group and sex.
4. Built a mirrored bar chart (population pyramid) in ggplot2.
5. Applied formatting for readability and visual appeal.

---

## 📈 Results
- Produced a clear, symmetrical population pyramid highlighting differences in age group sizes between men and women.
- Chart can be adapted to filter by other variables such as race/ethnicity, health conditions, or region.

---

## 📂 Repository Structure
brfss-2020-population-pyramid/
│
├── data/          # Optional: store dataset if public, or add a README with the download link
├── notebooks/     # RMarkdown (.Rmd) or R script (.R)
├── images/        # Screenshots or exported charts (PNG/JPEG)
├── README.md      # Main project description
└── LICENSE        # MIT License file

---

## 📎 Data Source
- [CDC BRFSS 2020 Data & Documentation](https://www.cdc.gov/brfss/annual_data/annual_2020.html)

---

## ▶️ How to Run
Clone this repository:
   
bash
   git clone https://github.com/nvavrock/brfss-2020-population
