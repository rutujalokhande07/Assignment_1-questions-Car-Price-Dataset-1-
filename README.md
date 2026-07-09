# 🚗 Car Price Dataset Analysis

A beginner-friendly Data Analysis project using **Python** and **Pandas** to analyze a car price dataset. This project demonstrates data loading, filtering, grouping, aggregation, and statistical analysis.

## 📌 Project Overview

This project answers 20 analytical questions using the Car Price Dataset. It helps understand how to use Pandas for real-world data analysis tasks.

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

## 📂 Dataset

The dataset contains information about cars, including:

- Brand
- Model
- Year
- Price
- Mileage
- Fuel Type
- Transmission
- Engine Size
- Number of Doors
- Owner Count

## 📊 Analysis Performed

The project answers the following questions:

1. Average price of all cars.
2. Brand with the highest average price.
3. Most common fuel type.
4. Cars with mileage greater than 200,000.
5. Distribution of cars by transmission.
6. Car model with the highest price.
7. Average price by fuel type.
8. Cars manufactured in 2020 or later.
9. Average engine size by brand.
10. Car with the lowest mileage.
11. Correlation between mileage and price.
12. Cars with more than two owners.
13. Average price by year.
14. Car with the highest number of doors.
15. Average mileage by fuel type.
16. Number of Toyota cars.
17. Average price of automatic transmission cars.
18. Car with the highest owner count.
19. Average engine size of diesel cars.
20. Cars priced above $10,000.

## 📁 Project Structure

```
car_price_assignment/
│── Car_Price_Analysis.ipynb
│── Car_Price_Dataset.csv
│── README.md
```

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/car_price_assignment.git
```

2. Open the project folder.

3. Install the required library.

```bash
pip install pandas
```

4. Run the notebook.

## 📈 Sample Pandas Operations

```python
import pandas as pd

df = pd.read_csv("Car_Price_Dataset.csv")

# Average price
df["Price"].mean()

# Cars after 2020
df[df["Year"] >= 2020]

# Average price by fuel type
df.groupby("Fuel_Type")["Price"].mean()
```

## 🎯 Learning Outcomes

- Reading datasets using Pandas
- Data filtering
- Data grouping
- Statistical analysis
- Aggregation functions
- Data exploration using Python

## 👩‍💻 Author

**Rutuja Lokhande**

BCA Student | Data Science Learner

---

⭐ If you found this project useful, consider giving it a star.
