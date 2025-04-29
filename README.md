# **QTM 350 Final Project - Economic Growth Analysis in Asia**

## **Project Overview**

This project investigates the relationships between income levels, demographic trends, labor market dynamics, and economic growth volatility among East and Southeast Asian countries from 1990 to 2023. Using the World Bank’s World Development Indicators dataset, we conduct three primary analyses:

GDP Growth Volatility vs. Income Level
- We examine whether wealthier countries in the region experience more stable economic growth. Regression analysis reveals no statistically significant relationship between average GDP per capita and GDP growth volatility, suggesting that structural factors like economic diversification and resource dependence play a larger role.

Population Growth vs. GDP Growth
- We explore how population growth correlates with economic expansion across emerging economies. The results show that while a growing population can support higher output, the strength and nature of this relationship vary significantly between countries, influenced by broader socio-economic contexts.

Employment-to-Population Ratio vs. GDP Growth
- The final analysis investigates whether rising employment rates are associated with stronger GDP growth. While modest positive correlations are observed in several countries, results indicate that employment growth alone does not fully drive economic expansion—factors such as productivity and external trade also significantly impact outcomes.

---

## **Getting Started**

### **Prerequisites**
Ensure you have the following software installed:
- Python 3.x
- A package manager like `pip` to install Python libraries.
- Jupyter Notebook or any Python IDE for running `.qmd` files.

### **Required Libraries**
Install the necessary libraries before running the code:
```bash
pip install pandas matplotlib seaborn numpy statsmodels 
```

---

## **Running the Project**

1. **Clone the Repository**
   Clone the repository to your local machine:
   ```bash
   git clone git clone https://github.com/yejinannachoi/world-bank-wdi-analysis.git
   cd world-bank-wdi-analysis
   ```

2. **Prepare the Dataset**
   - Ensure `asian_countries.csv` is in the project root directory.


3. **Run the Analysis**
   - Open the `report.qmd` file in your preferred Quarto-compatible editor or IDE.
   - Render the file:
     ```bash
     quarto render report.qmd
     ```

4. **View Outputs**
   The code generates:
   - Visualizations of GDP volatility and economic growth trends.
   - Correlation plots between employment and GDP growth.
   - Summary tables highlighting country-specific statistics.

---

## **Repository Structure**

The repository is organized into the following directories and files:

- **[`data/`](data/)**: Contains raw and processed datasets used in the analysis.  
- **[`documentation/`](documentation/)**: Includes the codebook and the erdiagram.  
- **[`figures/`](figures/)**: Stores plots and tables generated in the analysis. 
- **[`scripts/`](script/)**: Folder with the SQL and Python scripts used in the analysis.  

---

## **Key Insights**
- Primary enrollment rates are consistently high, reflecting global prioritization of foundational education.
- Significant disparities exist in tertiary education, particularly in regions like Sub-Saharan Africa and South Asia.
- Positive correlations between enrollment levels suggest that strengthening access at one level improves outcomes at others.

---