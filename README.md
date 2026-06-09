The analysis showed that glucose level has the strongest connection to diabetes, and patients with higher glucose, BMI, and pregnancy counts were more likely to have diabetes. The charts and statistics also revealed patterns between insulin, age, and other health features, helping us better understand factors that may increase diabetes risk.
CAR PRICE PREDICTION:
This project develops a machine learning model to predict the selling price of used cars based on their characteristics. The dataset contains information such as car name, year of manufacture, present market price, kilometers driven, fuel type, seller type, transmission type, and ownership history.

The objective is to help buyers, sellers, and online car marketplaces estimate fair vehicle prices using data-driven insights.

Business Problem

Pricing used cars accurately can be challenging because many factors influence a vehicle's value. The goal of this project is to build a predictive model that estimates a car's selling price based on its features.

Dataset Features
Feature	Description
Car_Name	Name of the car
Year	Manufacturing year
Present_Price	Current market price
Kms_Driven	Distance driven (km)
Fuel_Type	Petrol, Diesel, or CNG
Seller_Type	Dealer or Individual
Transmission	Manual or Automatic
Owner	Number of previous owners
Selling_Price	Target variable
Project Steps
1. Data Loading
Imported the dataset using Pandas.
Examined the dataset structure and data types.
2. Data Exploration
Checked dataset dimensions.
Generated summary statistics.
Identified missing values.
Explored distributions of variables.
3. Data Visualization
Created histograms to analyze price distribution.
Generated scatter plots to study relationships between features and selling price.
Used correlation analysis to identify influential features.
4. Data Preprocessing
Encoded categorical variables.
Selected relevant features.
Split the dataset into training and testing sets.
5. Model Development
Built a Linear Regression model.
Trained the model using historical car data.
6. Model Evaluation

The model was evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
7. Prediction
Generated selling price predictions for test data.
Compared actual prices with predicted prices.
Key Findings
Present_Price was the strongest predictor of selling price.
Newer vehicles generally had higher selling prices.
Automatic vehicles tended to be more expensive than manual vehicles.
Mileage (Kms_Driven) had less influence than expected.
Dealer-listed vehicles were generally priced higher than individually listed vehicles.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
How to Run the Notebook
1. Clone the Repository
git clone https://github.com/yourusername/used-car-price-prediction.git
2. Navigate to the Project Folder
cd used-car-price-prediction
3. Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
4. Launch Jupyter Notebook
jupyter notebook
5. Open the Notebook

Open:

Car_Price_Prediction.ipynb
6. Run All Cells

In Jupyter Notebook:

Kernel → Restart & Run All

The notebook will:

Load the dataset
Perform exploratory data analysis
Train the machine learning model
Evaluate model performance
Generate car price predictions
Model Performance

Evaluation metrics used:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

These metrics help assess the accuracy of the car price prediction model.
