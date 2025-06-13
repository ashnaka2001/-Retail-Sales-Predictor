# -🛒 Retail-Sales-Predictor

This project applies multiple regression algorithms to forecast retail store sales based on historical data. It involves comprehensive data preprocessing, model training, and performance evaluation to build accurate sales prediction models.

By analyzing both product and outlet-level characteristics, the project aims to uncover key features that drive sales performance. The ultimate goal is to empower retailers with data-driven insights to optimize inventory management, promotional strategies, and overall decision-making.

# 📂 Dataset Description
The dataset contains both product-level and outlet-level features that influence retail sales. Below is a description of each variable:

Variable	Description
Item_Identifier	: Unique product ID
Item_Weight	: Weight of the product
Item_Fat_Content : Indicates whether the product is low fat or regular
Item_Visibility	: Percentage of total display area of all products allocated to this product in the store
Item_Type	: Category to which the product belongs (e.g., Dairy, Snacks, Household)
Item_MRP	: Maximum Retail Price (list price) of the product
Outlet_Identifier	: Unique store ID
Outlet_Establishment_Year	: The year the store was established
Outlet_Size	: Physical size of the store (e.g., Small, Medium, High)
Outlet_Location_Type	: Type of city in which the store is located (e.g., Tier 1, Tier 2)
Outlet_Type	:Type of outlet (e.g., Grocery Store, Supermarket Type1/2/3)
Item_Outlet_Sales	: Target variable — Sales of the product in the particular store

# 📌 Project Overview
# Goal:
To build and evaluate regression models that accurately predict future sales for retail stores based on historical data.

# Key Features:

Data preprocessing & EDA

Feature scaling using StandardScaler

Model training using 9 regression algorithms

Hyperparameter tuning

Model performance evaluation (MAE, MSE, RMSE, R²)

# 🔧 Technologies Used
seaborn
matplotlib
numpy
scikit learn
pandas




