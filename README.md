#  Phishing Website Detection

A machine learning-based solution to classify URLs as **safe** or **unsafe** using an XGBoost model. This project extracts key features from URLs to predict whether a website is a phishing site.

##  Features

- **Machine Learning-Based Detection**: Uses an XGBoost model trained on extracted URL features.
- **Feature Extraction**: Extracts important characteristics like `URL Length`, `Domain Age`, `HTTPS Usage`, `Redirections`, etc.
- **Model Deployment**: Joblib is used to store and load the trained model.
- **Basic UI (Planned)**: A simple GUI to allow users to paste a URL for classification.

##   Dataset & Model
The dataset includes features such as:

- Domain Age
- Presence of "@" in URL
- URL Length
- Redirections
- HTTPS Usage
- JavaScript-based Attacks (e.g., iFrame, MouseOver events)

The XGBoost model was trained on this dataset, achieving high accuracy in detecting phishing websites.
##   Tech Stack
-  **Python**	Core development
- **XGBoost, Scikit-learn**	Model training & evaluation
- **Pandas, NumPy**	- Feature Engineering
-  **Flask** - Backend
- **JavaScript, HTML, CSS** - frontend
- **Joblib** - Model Storage
- **Git, GitHub** - Version Control
