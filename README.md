# Restaurant Customer Segmentation

Developed by Pirate-Emperor, Customer_Segmentation is a Python-based machine learning application, implemented in a Jupyter Notebook, that focuses on segmenting restaurant customers based on their frequency of visits, recency of last visit, and total spending.

## Problem Statement:
Customer Segmentation is needed in order to use the clusters with most valuable customers to predict the seat/visitor forecasting to ensure adequate seat reservation and to gain financial boost to the restaurant.
The second objective is to provide recommendation to the restaurant to capture those cluster of customers whose recency is less and payout is high.

## Methodology:
Python is used to perform the analysis in this project. The complete Python code can be found in the Jupyter Notebook named **’Customer Segmentation - RFM’**. The outline of the steps followed in the analysis is as follows:
- Data exploration and Validation (Performing data integrity checks, identifying missing values etc.)
- Data Preprocessing (Handling missing values, standardization, checking for correlation, testing hypothesis)
- Pareto Analysis (To determine what percentage of the customer contribute to what percent of the revenue)
- Determining the Key Performance Indicators.
- Determining the number of clusters through Elbow Analysis.
- K-Means clustering for Customer Segmentation.
- PCA for better visualization.
- Aggregate information for each cluster.


## Features

- **Data Preprocessing**: Cleans and preprocesses the restaurant customer data for machine learning.
- **Feature Engineering**: Enhances the dataset by creating features for frequency, recency, and monetary value.
- **Customer Segmentation**: Utilizes clustering algorithms, such as K-Means, to segment customers into groups based on the created features.
- **Model Evaluation**: Evaluates the performance of the clustering model using metrics such as silhouette score and elbow method.
- **Visualization**: Generates plots and charts to display the distribution of features, clustering results, and customer segments.
- **Segment Analysis**: Analyzes each customer segment to derive insights and characteristics.

## Prerequisites

To run the project, you'll need:

- Python 3.x
- Required Python libraries (e.g., pandas, numpy, scikit-learn, matplotlib)
- Jupyter Notebook

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/Pirate-Emperor/Customer_Segmentation.git
cd Customer_Segmentation
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the `Restaurant Customer Segmentation.ipynb` file and open it.

Execute the cells in the notebook to preprocess data, perform customer segmentation, evaluate the model, visualize results, and analyze segments.

## Data Source

The project uses customer data from a restaurant reservation system, including visit frequency, recency, and monetary value. Use the _**orders.csv**_ file to get the customer data used in this project. The dataset is pretty much self-explanatory.

## Development

To enhance the project, you can modify the Jupyter Notebook (`Customer_Segmentation.ipynb`). Some potential areas for improvement include:

- Implementing more advanced clustering algorithms and parameters for better segmentation.
- Incorporating additional customer features, such as demographics and preferences, for more comprehensive segmentation.
- Developing marketing strategies and personalized offers for each customer segment.
- Expanding the application to include features such as churn prediction and customer lifetime value.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

