# Kaggle Playground Series - Season 5, Episode 6

This repository contains my solution for the [Kaggle Playground Series - Season 5, Episode 6](https://www.kaggle.com/competitions/playground-series-s5e6) competition.

The goal of this competition is to build a classification model that predicts the `Transported` status of passengers in a simulated space travel dataset. The evaluation metric is **Accuracy**.

## 📁 Dataset

You can access and download the dataset directly from the [competition page](https://www.kaggle.com/competitions/playground-series-s5e6/data). To download the dataset:

1. Sign in to your Kaggle account.
2. Go to the [Data](https://www.kaggle.com/competitions/playground-series-s5e6/data) section.
3. Accept the competition rules if prompted.
4. Download the `train.csv`, `test.csv`, and `sample_submission.csv` files.

Alternatively, you can download the data via the Kaggle API:

```bash
kaggle competitions download -c playground-series-s5e6

📒 Notebook
The main solution is implemented in the Jupyter notebook:
📄 Playground_S5E6_Solution.ipynb

This notebook includes:

Exploratory Data Analysis (EDA)

Data preprocessing and feature engineering

Encoding of categorical variables

Model selection and training (e.g., XGBoost, LightGBM, CatBoost, Stacking, etc.)

Hyperparameter tuning (using Optuna or GridSearchCV)

Prediction and submission generation

Evaluation using cross-validation and public leaderboard submission

✅ Requirements
To run this notebook, install the required libraries:

bash
Kopyala
Düzenle
pip install -r requirements.txt
Or manually install:

bash
Kopyala
Düzenle
pip install pandas numpy scikit-learn lightgbm xgboost catboost optuna matplotlib seaborn
🏆 Performance
Final model used: [Mention your best model or ensemble method here]

Cross-validation accuracy: [Insert CV score]

Public leaderboard score: [Insert score if available]

📌 Notes
This repository is intended for educational and competitive purposes.

Feel free to fork the repository and experiment with your own model improvements.

📬 Contact
If you have any questions, feel free to reach out via GitHub Issues.
