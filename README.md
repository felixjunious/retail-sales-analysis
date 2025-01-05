# **Retail Sales Analysis : Analyzing Customer Behavior and Seasonal Trends To Make An Informed Business Decisions**  
**Author:** Felix Junious  

## **Overview**  
This project analyzes a fictional retail sales data focusing on the customer behaviour and the seasonal trends or patterns. 
A detailed summary of the findings can be found in [`reports/summary.ipynb`](../reports/summary.ipynb).  

---

## **Dataset Description**  
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset/data). The raw data is downloaded from the source and saved in [`data/raw/retail_sales_dataset.csv`](../data/raw/retail_sales_dataset.csv)

---

### **Key Attributes in the Dataset:**  

- **Basic Details:**  
  - `transaction_id`, `customer_id`, `date`

- **Customer Information:**  
  - `gender`, `age`  

- **Product Information:**  
  - `product_category`, `price`, `quantity`  

- **Sales Information:**  
  - `total_amount`   

---

### **Data Cleaning Process:**  
The processes for cleaning the dataset includes : 
1. Transform columns name into lowercase snake format
2. Convert columns data type to appropriate type

---

## **Installation and Requirements**  
To run this project, you'll need:  
1. **Jupyter Notebook**: The primary tool for this analysis.  
2. **Python Libraries:**  
   - `pandas`: For data manipulation and cleaning.  
   - `matplotlib` and `seaborn`: For visualization.  

Install the dependencies using the following command:  
```bash
pip install pandas matplotlib seaborn
```

---

## **Usage Instructions**  
1. **Viewing the Summary:**  
   - Open `reports/summary.ipynb` to explore the key findings of the analysis.  

2. **Project Structure:**  
   - **`data/raw`**: Contains the raw dataset `retail_sales_dataset.csv`.
   - **`data/cleaned`**: Contains the cleaned dataset `retail_sales_cleaned.csv`.  
   - **`notebooks/`**: Includes Jupyter Notebooks for:  
     - **Data Cleaning**  
     - **Exploratory Data Analysis (EDA)**  
   - **`plots/`**: Stores generated visualizations.  
   - **`reports/`**: Summary and key insights (`summary.ipynb`).  

3. **How to Run:**  
   - Clone the repository:  
     ```bash
     git clone https://github.com/felixjunious/retail-sales-analysis.git
     cd berlin-airbnb-analysis
     ```
   - Open the desired notebook:  
     ```bash
     jupyter notebook
     ```

---

## **Summary of Analysis**  
The analysis explores:  
The customer behavior and seasonal trends and make reccomendation based on the insights gathered from the analysis.

Key findings and visualizations are available in [`reports/summary.ipynb`](./reports/summary.ipynb).  
