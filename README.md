# Mall Customers Data Clustering using KNN Algorithm

## Project Overview
This project aims to perform customer segmentation on the Mall Customers dataset using the K-Nearest Neighbors (KNN) algorithm. The objective is to group customers into distinct clusters based on their purchasing patterns and demographic features, providing actionable insights that can help in personalized marketing strategies.

## Features
- **Data Cleaning**: The dataset was first cleaned to handle missing values and ensure consistency.
- **Data Clustering**: The KNN algorithm was applied to cluster customers into various groups.
- **Visualization**: Matplotlib and Seaborn were used to visualize the clusters and other key insights.
- **Insights Report**: An analytical report summarizing key insights from the clustering analysis is included.

## Repository Structure
```
.
├── Mall_Customers.csv          # Contains the dataset
├── Data_pre-processing.ipynb   # Jupyter notebook for data cleaning
├── Insights_report.pdf         # Detailed report with findings and recommendations
├── EDA.pynb                    # Data Clustering and visualization outputs from Matplotlib and Seaborn
├── README.md                   # Project documentation
└── requirements.txt            # Required libraries
```

## Getting Started

### Prerequisites
Ensure you have Python installed on your machine. You can install the required libraries using the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

### Dataset
The dataset used for this project can be found in the `data/` directory. The data contains information about customers, such as:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

### Libraries Used
- **Python 3.8+**
- **Jupyter Notebook**: For performing data analysis and model building.
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualizing data and clustering results.
- **Seaborn**: For enhanced data visualization.
- **scikit-learn**: For implementing the KNN algorithm and other machine learning tasks.

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mall-customers-knn-clustering.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mall-customers-knn-clustering
   ```
3. Open the Jupyter Notebook and run the cells to perform the analysis:
   ```bash
   jupyter notebook
   ```

## Data Cleaning
- Handled missing values
- Normalized and scaled numerical features to improve clustering performance
- Categorical variables were encoded

## Clustering Process
1. **Feature Selection**: Age, Annual Income, and Spending Score were selected for clustering.
2. **KNN Algorithm**: The KNN model was trained on the data to form clusters of similar customers.
3. **Visualization**: The clusters were visualized using scatter plots and pair plots to understand customer behavior.

## Results & Insights
The analysis identified distinct customer segments with varying spending habits and demographics. The key insights from the analysis are documented in the `insights_report.pdf`. This includes:
- High-spending customer profiles
- Segments that are potential targets for marketing
- Demographic patterns in purchasing behavior

## Conclusion
This project demonstrates how KNN can be effectively used for customer segmentation. The findings offer valuable insights for businesses looking to implement data-driven marketing strategies.
s.

## Acknowledgements
- Dataset provided by Mall Customers Database.
- Inspiration from various online resources and tutorials for KNN clustering.

---
