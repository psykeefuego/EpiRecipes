## Exploring the EpiRecipes Dataset

This notebook provides a comprehensive exploratory data analysis (EDA) of the EpiRecipes dataset from Kaggle.
The dataset can be found at: [Epicurious - Recipes with Rating and Nutrition](https://www.kaggle.com/datasets/hugodarwood/epirecipes).


Below is a summary of the key sections and their purposes:

### 1. **Getting Started**
   - **Imports & Data Load:** We load the necessary libraries and import our dataset `epi_r.csv`.
   - **First Look:** We check out the first few rows and get a summary of the data.

### 2. **Cleaning Up**
   - **Fixing Missing Data:** We handle missing values in the calorie column by filling them with the average calorie count.
   - **Removing Outliers:** We get rid of recipes with unusually high calorie counts.

### 3. **Analyzing the Data**
   - **Visualizations:** We create histograms and boxplots to understand the distribution of recipe ratings and calorie content.
   - **Relationships:** Scatter plots help us see how recipe ratings relate to calorie content.

### 4. **Simplifying the Data**
   - **Dropping Unnecessary Columns:** We remove columns that aren’t very useful.
   - **Meal Types:** We sort recipes into breakfast, lunch, and dinner categories.
     
### 5. **Generating a random meal plan
   - Finding exclusive breakfast, lunch and dinner dishes

### 6. **Vegetarian vs. Non-Vegetarian**
   - **Comparisons:** We use pie charts and histograms to compare vegetarian and non-vegetarian recipes by calorie content.

### 7. **Dish Types**
   - **Dairy-Free vs. Dairy:** We compare the counts of dairy-free and dairy dishes using stacked bar charts.
   - **Recipe Types:** We look at different types of recipes like quick meals and those needing advance prep.

### 8. **Holiday Dishes**
   - **Global View:** A map shows how holiday-specific dishes are distributed around the world.

### 9. **Understanding Relationships**
   - **Correlations:** We use heatmaps to see how different features like calories, rating, and protein relate to each other.
   - **Regression:** We analyze relationships between features with simple regression models.

### 10. **Statistical Tests**
   - **Checking Normality:** We use tests to see if our data follows a normal distribution.

### 11. **Machine Learning**
   - **Modeling:** We train models like Support Vector Regression and Random Forest to predict and evaluate recipe data.
   - **Regularization:** We apply Ridge and Lasso regression to improve model accuracy and avoid overfitting.

### 12. **Ingredient Insights**
   - **Top Ingredients:** We analyze and visualize the most common ingredients across recipes.

### 13. **Final Visualisation**
   - **Ingredient-Rating Correlation:** We create a heatmap to show the relationship between the number of ingredients and recipe ratings.
   - **Interactive Plot:** An interactive scatter plot lets you explore how recipe ratings change with the number of ingredients.

## Note: The final plot may not be processed due to the dynamic nature of plotly visualizations, thus a link to the colab notebook is embedded in the notebook.The map is also uploaded as a separate file.
