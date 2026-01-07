# Gym-Members-Exercise-Prediction-
🏋️ Gym Members Exercise Tracking & Prediction 📊
This project explores and analyzes a comprehensive dataset of gym members' workout metrics using Python. It includes data preprocessing, exploratory data analysis (EDA), and machine learning models to predict Calories Burned 🔥 based on physical and session-based attributes.

📁 Dataset Source
File: gym_members_exercise_tracking.csv 📝

The dataset contains 15+ features including Age, Gender, Weight, Heart Rate (BPM), Workout Type, and Experience Level.

🔧 Technologies Used
Language: Python 🐍 (Pandas, NumPy)

Data Visualization: Matplotlib 📈, Seaborn 📉

Machine Learning: Scikit-learn 🤖 (KNN, SVR)

✅ Project Objectives
🧹 Objective 0: Data Preprocessing & Cleaning
Encoding: Convert categorical columns like Gender and Workout_Type into numerical values using Label Encoding 🔢.

Normalization: Scale numerical features using StandardScaler to optimize model performance ⚖️.

Data Integrity: Check for missing values and ensure data types are correct for analysis 🔍.

📊 Objective 1: Physical Metrics Statistics
Calculate Average BMI and Heart Rate across different experience levels 💓.

Analyze the distribution of Age and Weight among gym members ⚖️.

Identify the most common Workout_Type (Yoga, HIIT, Cardio, Strength) 🧘‍♂️.

📦 Objective 2: Workout Performance Analysis
Experience Level vs. Calories: Analysis of how experience affects workout intensity ⚡.

Gender-wise Comparison: Compare average calories burned and session duration between male and female members 🚻.

Heart Rate Analysis: Correlation between Avg_BPM and Calories_Burned ❤️‍🔥.

📈 Objective 3: Visualizations & Trends
Donut Chart: Proportion of members in different workout categories 🍩.

Grouped Bar Chart: Calories burned across different workout types 📊.

Correlation Heatmap: Relationship between Session Duration, Heart Rate, Age, and Calories 🌡️.

Histogram: Distribution of member ages and BMI 🏛️.

🤖 Objective 4: Machine Learning Modeling
Task: Regression analysis to predict Calories_Burned 🎯.

Algorithms:

KNN (K-Nearest Neighbors): Used for its effectiveness in finding similar member patterns 👥.

SVR (Support Vector Regression): Used to capture non-linear relationships in workout data 🧬.

Evaluation: Compare models using R2 Score, MAE, and RMSE ✅.

📉 Objective 5: Graphical Insights
Scatter Plot: Session Duration vs. Calories Burned to see intensity trends 📍.

Box Plots: Detect outliers in heart rate and session duration data 📦.

Line Chart: Trends in calories burned as workout frequency increases 📈.

📌 Insights & Benefits
This analysis helps to:

Understand which workout types are most efficient for calorie burning 🔋.

Predict calorie expenditure for new gym members based on their profile 🔮.

Help trainers optimize workout plans by identifying key performance drivers 📋.

📎 Notes
⚠️ Ensure that gym_members_exercise_tracking.csv is in the same directory as the notebook. Update the file path in the code to a local path if necessary before running.

Happy Analyzing! ⚙️🔋💪
