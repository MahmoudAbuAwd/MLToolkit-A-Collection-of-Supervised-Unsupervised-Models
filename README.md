# MLToolkit

MLToolkit is a collection of Python scripts implementing popular machine learning algorithms for both supervised and unsupervised learning. This toolkit is designed for educational purposes, experimentation, and as a reference for implementing various models from scratch or using popular libraries.

## Project Structure

```
MLToolkit/
├── Supervised Models/
│   ├── AdaBoost.py
│   ├── CatBoost.py
│   ├── Decision Tree.py
│   ├── Gradient Boosting Machine (GBM).py
│   ├── KNN.py
│   ├── LightGBM.py
│   ├── linear regression.py
│   ├── Logistic regression.py
│   ├── RandomForest.py
│   ├── SVM.py
│   └── xgboost.py
├── Unsupervised Models/
│   ├── (t-SNE).py
│   ├── DBSCAN.py
│   ├── Hierarchical clustering.py
│   ├── k-means.py
│   ├── PCA.py
│   └── README.MD
├── Evaluation metrics.txt
├── requirements.txt
└── README.md
```

## Features

- **Supervised Models:**
  - Linear Regression, Logistic Regression, Decision Tree, Random Forest, SVM, KNN, AdaBoost, CatBoost, Gradient Boosting Machine (GBM), LightGBM, XGBoost
- **Unsupervised Models:**
  - k-means, Hierarchical Clustering, DBSCAN, PCA, t-SNE
- **Evaluation Metrics:**
  - Common metrics for model evaluation (see `Evaluation metrics.txt`)
- **Visualization Effects:**
  - Many scripts include visualization of results, such as decision boundaries, cluster assignments, and dimensionality reduction plots, using libraries like Matplotlib and Seaborn.

## Getting Started

1. **Clone the repository:**
   ```powershell
   git clone https://github.com/MahmoudAbuAwd/MLToolkit.git
   cd MLToolkit
   ```

2. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```

3. **Run a model script:**
   ```powershell
   python "Supervised Models/RandomForest.py"
   ```
   *(Replace with the script you want to run)*

## Visualization Effects

Many scripts in this toolkit provide built-in visualizations to help you better understand model performance and data structure. Typical visualizations include:

- **Decision boundaries** for classifiers
- **Cluster assignments** for clustering algorithms
- **Dimensionality reduction plots** (e.g., PCA, t-SNE)
- **Feature importance** and other model insights

Visualizations are generated using [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/). To view the plots, simply run the scripts; plots will appear in a new window or inline if using a Jupyter environment.

**Example:**

```python
# Inside a script (e.g., k-means.py)
import matplotlib.pyplot as plt
plt.scatter(X[:, 0], X[:, 1], c=labels)
plt.title('Cluster Assignments')
plt.show()
```

## Requirements

See `requirements.txt` for the list of required Python packages.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, bug fixes, or new models.

## License

This project is licensed under the MIT License.

## Author

Mahmoud Abu Awd
