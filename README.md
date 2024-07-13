# Flight Delay Analysis

This project involves analyzing US domestic flight data from 2013 to understand departure and arrival delays.

## Steps Covered in This Project:

1. **Data Loading and Preparation:**
   - Loaded flight data from a CSV file.
   - Separated data into features (X) and target (Y).

2. **Data Exploration and Cleaning:**
   - Examined summary statistics for numeric fields.
   - Identified and handled missing values.
   - Investigated outliers in departure and arrival delays.

3. **Exploratory Data Analysis:**
   - Analyzed the distribution of departure and arrival delays.
   - Compared carrier performance based on arrival delays.
   - Explored arrival delays across different days of the week.

4. **Model Building and Evaluation:**
   - Built a linear regression model to predict arrival delays.
   - Trained the model and evaluated its performance using metrics like MSE and R-squared.
   - Implemented a random forest model for comparison and evaluated its performance.

5. **Identifying Routes with Delay Issues:**
   - Identified routes with the most late arrivals.
   - Calculated and visualized routes with the highest average arrival delays.

## Files Included:

- `flight_data.csv`: Dataset used for analysis.
- `flight_delay_analysis.ipynb`: Jupyter notebook containing all the analysis and code.
- `README.md`: This file summarizing the project.

## Dependencies:

- Python 3.x
- Libraries used: pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/flight-delay-analysis.git
   cd flight-delay-analysis
   ```

2. Install dependencies (if not already installed):

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Open and run `flight_delay_analysis.ipynb` in Jupyter Notebook or Jupyter Lab to explore the analysis step-by-step.

