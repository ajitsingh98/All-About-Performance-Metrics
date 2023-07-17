# All-About-Performance-Metrics
This repository contains a comprehensive collection of performance metrics for various machine learning tasks, including regression, classification, and clustering. These metrics have been implemented from scratch to provide a reliable and customizable way of evaluating the performance of your machine learning models.

## Table of Contents

- [Introduction](#introduction)
- [Implemented Metrics](#implemented-metrics)
- [Usage](#usage)
- [Data](#data)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Evaluating the performance of machine learning models is a crucial step in the development and assessment of their effectiveness. This repository aims to provide a wide range of performance metrics that can be applied to various machine learning tasks. By using these metrics, you can measure and analyze the performance of your models, gain insights into their strengths and weaknesses, and make informed decisions about improving them.

## Implemented Metrics

The repository currently includes the following performance metrics:

### [Regression Metrics](regression_metrics.ipynb)

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R2) Score
- Adjusted R-squared (R2) Score

### [Classification Metrics](classification_metrics.ipynb)

- Confusion Matrix 
- Accuracy Score
- Precision Score
- F-1 Score
- Recall Score
- Log Loss/ Binary Cross Entropy Loss
- Area Under the Receiver Operating Characteristic Curve (ROC AUC)
-  Classification report

### [Clustering Metrics](clustering_metrics.ipynb)

- Silhouette Coefficient

These metrics cover a wide range of evaluation needs and can be utilized across different machine learning domains. Each metric has been implemented from scratch, ensuring transparency and allowing for customization if needed. 

## Usage

To use the performance metrics in this repository, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ajitsingh98/All-About-Performance-Metrics.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd All-About-Performance-Metrics
   ```

3. Analyze the results and utilize the metrics to gain insights into your model's performance.

## Data

This repository also includes sample data files that can be used to test the performance metrics. The data files are stored in the `data/` directory and are labeled according to the task they correspond to (e.g., `Churn_Modelling.csv`, `HousingData.csv`, `Mall_Customers.csv`).

Feel free to use these sample datasets to assess the performance metrics or substitute them with your own data to evaluate your models effectively.

## Contributing

Contributions to this repository are welcome! If you have any suggestions, improvements, or additional performance metrics that you would like to include, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or enhancement.
3. Make the necessary changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request, explaining the purpose and benefits of your changes.

Your contributions will be reviewed, and upon approval, they will be merged into the main repository.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

I hope that this repository and the included performance metrics will be valuable tools in evaluating the effectiveness of your machine learning models. Feel free to explore, experiment, and contribute to further improve the available metrics. If you have any questions or encounter any issues, please don't hesitate to reach out to me. Happy modeling and evaluating!