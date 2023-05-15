# FIFA World Cup 2018 Supporter Prediction

This repository contains code and data for predicting supporter preferences and behavior during the FIFA World Cup 2018 using Twitter data. The goal is to analyze social media activities and tweets to gain insights into fan preferences and make data-driven predictions.

## Tasks Completed

1. **Classifications**:
	- Decision Tree: Implementation of a decision tree classifier to predict supporter preferences.
	- KNN (K-Nearest Neighbors): Implementation of the KNN algorithm for classification.
	- Random Forest: Building a random forest classifier to predict supporter preferences.
	- Adaboost: Implementation of the Adaboost algorithm for classification.

2. **Data Balancing**:
	- SMOTE (Synthetic Minority Over-sampling Technique): Balancing the dataset using SMOTE to address class imbalance.

3. **Clustering**:
	- K-means clustering: Implementation of the K-means clustering algorithm to identify patterns and group supporters based on their preferences.

4. **Regression**:
	- Linear Regression: Building a linear regression model to predict numerical outcomes related to supporter preferences.
	- Logistic Regression: Implementation of logistic regression to predict binary outcomes, such as team preference.

5. **Deep Learning**:
	- LSTM (Long Short-Term Memory): Utilizing LSTM architecture for sequence modeling and predicting supporter preferences.
	- RNN (Recurrent Neural Network): Implementation of a basic RNN for analyzing sequential data and predicting supporter behavior.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/HasnatAbdullah/FIFA_WC_2018_Supporter_Prediction_Twitter.git
cd FIFA_WC_2018_Supporter_Prediction_Twitter
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook The_FIFA_World_Cup_2018_Supporter_Prediction_Based_on_Twitter.ipynb
```

3. Run the notebook and follow the instructions provided within.

## Data

The dataset used for this project is available in the `FIFA_Supporter` folder. It includes tweets collected during the FIFA World Cup 2018, along with corresponding supporter preferences.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or additional models/techniques to add, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to thank the authors of the original research paper and the contributors to the dataset used in this project[Predicting Fans’ FIFA World Cup Team Preference from Tweets](https://link.springer.com/chapter/10.1007/978-3-030-52856-0_22)   . The relevant citations can be found in the research paper file [`Project Report of G-17.pdf`](Project Report of G-17.pdf).

For a detailed overview of the project, please refer to the [Project Report of G-17.pdf](Project Report of G-17.pdf).
