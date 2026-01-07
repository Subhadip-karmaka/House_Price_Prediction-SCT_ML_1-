House Price Prediction Using Linear Regression

📌 Project Overview

This repository implements a simple Linear Regression model to predict house sale prices based on a subset of features from the Kaggle House Prices dataset.
The project covers:

•	Data loading & preprocessing
•	Exploratory data analysis (EDA)
•	Model training
•	Model evaluation
•	Visualization of results
📊 Dataset

•	Source: Housing.csv from Kaggle’s House Prices: Advanced Regression Techniques competition
•	Sample Size: 546 observations in Housing.csv
🧮 Features Selected

⚙️ Requirements

Make sure you have Python 3.x installed along with the following libraries:

Feature Column  	Description

bathrooms  	Number of bathrooms 

area    	Above grade (ground) total area (sq ft)

airconditioning      	Number of airconditioner
stories
	
prefarea    	total preffered area (sq ft)

parking     	parking area

basement    	
furnishingstatus    	Furnitures placed in the rooms
hotwaterheating	   Geysers placed in the bathroom
 mainroad    	how much nearest house from the main-road  (km)

guestroom  	how much bigger & well decorated guestroom

bedrooms    	Number of bedrooms 

	
🛠 Methodology

1️⃣ Data Loading
Imported train.csv using pandas.
2️⃣ Preprocessing
Selected only the columns of interest (GrLivArea, BedroomAbvGr, FullBath, SalePrice).
Renamed columns for readability.
Checked for missing values and calculated basic statistics.
3️⃣ Data Splitting & Scaling
Split dataset into training (90%) and testing (10%) sets using train_test_split.
Applied StandardScaler to standardize feature means and variances.
4️⃣ Model Training
Trained a LinearRegression model on the standardized training data.
5️⃣ Model Evaluation
•	Predicted sale prices on the test set.
•	Calculated:
o	R² Score
o	Mean Absolute Error (MAE)
•	Plotted predicted vs. actual values with:
o	Perfect prediction reference line
o	Error bars
📥 Installation & Usage
1. Clone this repository
git clone https://github.com/Subhadip-karmaka/House_Price_Prediction-SCT_ML_1-.git

2. Place dataset Make sure Housing.csv is in the project root directory.
Clone this repository:

git clone https://github.com/Subhadip-karmaka/House_Price_Prediction-SCT_ML_1-.git 

Open the notebook:

jupyter notebook project.ipynb

3. Run the notebook
jupyter notebook "House Price Linear Regression.ipynb" Execute cells sequentially to reproduce:

Data analysis

Model training

Result visualizations

📈 Results Accuracy Score: ~ 64.948 on the test set

📊 Features

Data preprocessing (handling missing values, encoding, scaling, etc.)

Visualization: The scatter plot of predicted vs. actual sale prices shows a decent fit. A perfect prediction line helps visualize prediction accuracy.

🔮 Future Improvements Feature Engineering: Add more relevant features.

Model Selection: Compare with advanced models like Ridge, Lasso, or Random Forest.

👤 Author

Subhadip Karmakmar

Machine Learning Intern @ Skillcraft Technology

