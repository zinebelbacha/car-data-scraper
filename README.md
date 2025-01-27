# Car Data Scraper and Analyzer

This project scrapes car data from [Edmunds.com](https://www.edmunds.com/), cleans and preprocesses the data, and prepares it for visualization in **Power BI**. The goal is to analyze car trends, pricing, and other insights.

## Steps
1. **Scraping**:
   - The `Web_Scraping.ipynb` notebook extracts car data (make, model, year, price, mileage, etc.) from Edmunds.com using the python library `Selenium`.
   - The raw data is saved as `car_data.csv`.

2. **Cleaning**:
   - The `preprocessing.ipynb` notebook cleans and preprocesses the scraped data.
   - Tasks include handling missing values, removing duplicates, and standardizing formats.
   - The cleaned data is saved as `preprocessed_car_data.csv`.

3. **Visualization**:
   - The cleaned data is ready for analysis and visualization in **Power BI**.
   - You can create your own interactive dashboards to explore car trends, pricing, and more!

## Installation and Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/car-data-scraper.git
   cd car-data-scraper

2. **Create a virtual environment ( optional) and install the dependencies**:
   ```bash
   pip install -r requirements.txt

3. **Run the notebooks**:
Open the `Web_Scraping.ipynb` and `Preprocessing.ipynb` notebooks in Jupyter and run the cells.

4. **Visualize in Power BI**:
Feel free to create your own dashboards! You can also check out my visualizations under `Power BI\Power BI report.pbix`. 
