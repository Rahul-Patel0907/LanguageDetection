📁 Dataset
Name: WiLI-2018 (Wikipedia Language Identification)

Source: https://www.kaggle.com/datasets/zarajamshaid/language-identification-datasst

Description: The dataset comprises 235 languages, each represented by 1,000 paragraphs extracted from Wikipedia.

🛠️ Features

TF-IDF vectorization with character n-grams (1 to 3).

Multinomial Naive Bayes classifier.

Hyperparameter tuning using GridSearchCV.

Evaluation metrics: Accuracy, Precision, Recall, F1-Score.

Visualization of training and testing data distribution.

🚀 Getting Started

Prerequisites

Ensure you have the following libraries installed:

pip install pandas scikit-learn matplotlib seaborn

Clone the repository: git clone https://github.com/yourusername/language-detection.git

Navigate to the project directory: cd language-detection

Place the dataset.csv file in the project directory.


📊 Usage
Run the language_detection.ipynb notebook in Google Colab or your local Jupyter environment to:

-Load and preprocess the dataset.

-Split the data into training and testing sets.

-Visualize the distribution of languages in both sets.

-Train the model with hyperparameter tuning.
-Evaluate the model's performance.
-Predict the language of custom text inputs.

