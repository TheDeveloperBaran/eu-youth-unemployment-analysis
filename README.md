# EU Youth Unemployment Analysis

This project presents an exploratory data analysis of youth unemployment rates across European Union countries based on multiple criterias such as focusing on individuals aged 15–29, with the aim of uncovering long-term trends, cross-country differences, and post-crisis recovery patterns.

##  Objective

To identify and visualize youth unemployment patterns over a 13-year period, supporting socioeconomic insights, comparative country analysis, and data-driven storytelling through interactive visuals and summary statistics.

---

##  Dataset

- **Source:** https://data.europa.eu/data/datasets/djwzl5mcfh9fccw8bzsxw?locale=en
- **Format:** CSV (Comma-Separated Values)
- **Key fields used:**  
  - `GEO` – Country  
  - `AGE` – Age group  
  - `TIME_PERIOD` – Year  
  - `OBS_VALUE` – Unemployment rate (%)  

---

##  Technologies Used

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Features

- Data filtering and transformation for youth segment (15–29)
- Country-level and regional unemployment comparison
- Year-over-year trend visualization
- Exportable plots and CSVs for further policy analysis

---

##  How to Run the Project

```bash
# Clone the repository
git clone https://github.com/TheDeveloperBaran/eu-youth-unemployment-analysis.git

# Navigate into the project folder
cd eu-youth-unemployment-analysis

# Install the required dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebooks/analysis.ipynb
