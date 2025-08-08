Health Prediction System Based on Day-to-Day Life Activity Using Machine Learning
This project is a Python-based machine learning application that predicts health conditions based on daily life activity data, such as movements recorded from a smartwatch. It uses clustering techniques to group user behaviors and presents the results in a user-friendly interface.

🧠 Project Overview
The system aims to analyze daily activity patterns to help users gain insights into their lifestyle and potential health conditions.

Features
User sign-up and login functionality

Health prediction using K-Means clustering

Smartwatch dataset analysis with preprocessing

Visualizations for activity analysis

Simple GUI built with Tkinter

SQLite database for user data management

Trained model saved using Pickle for quick predictions

📊 Dataset
Source: smart watch Dataset.csv

The dataset contains real-world activity data captured from smartwatch sensors.

⚙️ Technologies Used
Python

Pandas, NumPy, Matplotlib

Scikit-learn (for machine learning)

Tkinter (for GUI)

SQLite (for database)

Pickle (for model serialization)

Jupyter Notebook (for development and analysis)

🚀 Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/health-prediction-system.git
cd health-prediction-system
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the application
bash
Copy
Edit
python app.py
Make sure your Python environment has access to all dependencies listed in requirements.txt.

📁 Project Structure
graphql
Copy
Edit
├── app.py                  # Main application file  
├── signup_page.py          # User registration module  
├── login_page.py           # User login module  
├── home_page.py            # Health prediction and UI  
├── database.py             # Database connection  
├── smart_watch.ipynb       # Jupyter notebook for analysis  
├── kmeans_model.pkl        # Saved ML model  
├── users.db                # SQLite database file  
├── smart watch Dataset.csv # Input dataset  
└── requirements.txt        # Required Python packages  
✍️ Author
undalu diwakar

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.












