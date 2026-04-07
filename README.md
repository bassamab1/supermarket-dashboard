# Supermarket Sales Dashboard

This project is a **Python dashboard** that analyzes supermarket sales data using **Pandas, Matplotlib, and Seaborn**. It provides visual insights into sales trends, customer behavior, and product performance.  

---

## **Dataset**

The dataset used is `SuperMarket Analysis.csv`, which contains sales transactions with the following columns:

- `Invoice ID` – Unique identifier for each transaction  
- `Branch` – Store branch (A, B, C)  
- `City` – City where the branch is located  
- `Customer type` – Member or Normal  
- `Gender` – Male or Female  
- `Product line` – Type of product sold (e.g., Food and Beverage, Health and beauty)  
- `Unit price` – Price per item  
- `Quantity` – Number of items sold  
- `Tax 5%` – Tax applied on the transaction  
- `Total` – Total price including tax  
- `Date` – Date of transaction  
- `Payment` – Payment method (Cash, Credit card, Ewallet)  
- `Rating` – Customer satisfaction rating (1-10)  

---

## **Features / Insights**

The dashboard visualizes the following insights:

1. **Total Sales by City** – Identify the top-performing cities.  
2. **Total Sales by Product Line** – See which product categories sell the most.  
3. **Payment Method Distribution** – Shows which payment methods are most popular.  
4. **Monthly Sales Trend** – Track sales patterns across months.  
5. **Sales by Gender** – Compare spending between male and female customers.  
6. **Correlation Heatmap** – Analyze relationships between numeric variables like Quantity, Unit Price, Tax, Total Sales, and Rating.  

---

## **Requirements**

Install the required Python libraries before running the code:

```bash
pip install pandas matplotlib seaborn
