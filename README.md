# Economic Recession Prediction Using Machine Learning

## Project Overview

This project leverages machine learning models to predict economic recessions using a diverse set of indicators. The goal is to provide actionable insights that can help policymakers, businesses, and individuals mitigate the impact of economic downturns.

## Data and Preprocessing

The dataset is compiled from various reliable sources and includes a wide range of economic indicators. The data undergoes extensive preprocessing to ensure quality and consistency, including:

- Data cleaning
- Missing value imputation
- Feature engineering

Following preprocessing, the data is explored and analyzed to understand underlying patterns and relationships. Dimension reduction techniques are applied to enhance model performance and interpretability.

## Machine Learning Models

We evaluate five different machine learning models to determine the most effective approach for predicting economic recessions:

1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbors (K-NN)
4. Naive Bayes
5. Neural Network
6. Discriminant Analysis

## Model Evaluation

Each model is assessed based on key performance metrics, including:

- Accuracy
- Precision
- F1 Score

Among these models, K-Nearest Neighbors (K-NN) emerges as the top performer, demonstrating high accuracy and precision in predicting economic recessions.

## Insights and Applications

The results of this project offer valuable insights into the indicators most closely associated with economic downturns. These findings can aid in early warning systems, enabling proactive measures to be taken by:

- Policymakers for informed decision-making
- Businesses for strategic planning
- Individuals for personal financial management

## Conclusion

While the K-NN model shows promising results, it is essential to complement these predictions with other economic indicators for a comprehensive understanding of the economy. This project underscores the potential of machine learning in economic forecasting, highlighting the importance of continuous refinement and validation of predictive models.

## Repository Contents

- `data/`: Contains the dataset and data preprocessing scripts.
- `notebooks/`: Jupyter notebooks detailing data exploration, preprocessing, and model evaluation.
- `models/`: Saved model files and performance evaluation scripts.
- `results/`: Detailed results and visualizations of model performance.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/economic-recession-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd economic-recession-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the data preprocessing script:
   ```bash
   python scripts/preprocess_data.py
   ```
5. Execute the model evaluation notebook:
   ```bash
   jupyter notebook notebooks/model_evaluation.ipynb
   ```

## Contributing

We welcome contributions to improve the project. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This description outlines the project's objectives, methodology, and potential applications, providing a clear overview for potential collaborators and users.
