# E-Commerce Data Analytics Project with Python and SQL

## Overview

This project showcases a complete data analytics pipeline for an e-commerce dataset, leveraging both Python and SQL to derive meaningful insights. The project involves data extraction, cleaning, analysis, and visualization to provide a thorough understanding of customer behavior, sales trends, and business performance.

## Project Features

1. **Data Extraction and Cleaning:**
   - Loaded raw e-commerce data into a SQL database.
   - Cleaned and transformed data using SQL and Python (pandas).

2. **Exploratory Data Analysis (EDA):**
   - Performed EDA using SQL queries and Python libraries to uncover trends and patterns.
   - Visualized data distributions, correlations, and key metrics using Matplotlib and Seaborn.

3. **Customer Segmentation:**
   - Implemented RFM (Recency, Frequency, Monetary) analysis to categorize customers based on their purchase behavior.
   - Used SQL to compute RFM scores and Python for clustering.

4. **Sales Analysis:**
   - Analyzed sales performance over time using SQL.
   - Identified top-selling products, seasonal trends, and revenue drivers.

5. **Customer Retention:**
   - Calculated customer retention rates using SQL.
   - Investigated factors influencing customer loyalty and repeat purchases.

6. **Predictive Analytics:**
   - Built predictive models using Python (Scikit-learn) to forecast future sales and customer behavior.
   - Evaluated model performance and fine-tuned hyperparameters.

## Technologies Used

- **SQL:**
  - PostgreSQL/MySQL for database management and complex queries.
  
- **Python:**
  - pandas for data manipulation and analysis.
  - Matplotlib and Seaborn for data visualization.
  - Scikit-learn for predictive modeling.

- **Jupyter Notebook:**
  - Documented the analysis process and findings.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8+
- PostgreSQL/MySQL
- Jupyter Notebook

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ecommerce-data-analytics.git
   cd ecommerce-data-analytics
   ```

2. **Set up the database:**
   - Import the provided SQL scripts in the `data/` directory to set up the database schema and load sample data.

3. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the analysis:**
   - Open the Jupyter notebooks in the `notebooks/` directory to explore the data analysis and insights.

### Project Structure

- `data/`: Sample data and SQL scripts for database setup.
- `notebooks/`: Jupyter notebooks containing data analysis and visualizations.
- `scripts/`: Python scripts for data processing and modeling.
- `requirements.txt`: Python dependencies.

## Usage

- Navigate through the Jupyter notebooks to understand the data analysis process.
- Modify and run SQL queries in the `scripts/` directory to further explore the data.
- Use the predictive models to forecast future sales trends and customer behavior.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
