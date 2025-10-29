🧠 German Credit Risk Prediction App
A sleek and interactive Streamlit web app that predicts whether a credit applicant is a GOOD or BAD risk using machine learning. Built for data enthusiasts, recruiters, and anyone curious about financial modeling.

🚀 What It Does
Predicts credit risk based on user inputs like: Age, Job, Housing, Saving & Checking accounts, Credit amount, Duration, and more

Uses a trained Extra Trees Classifier on the German Credit Risk dataset

Encodes categorical features for accurate predictions

Delivers instant results via a clean Streamlit interface
🛠️ Tech Stack
Python · Pandas · Streamlit · Joblib · Extra Trees Classifier

📁 Folder Structure
credit-risk/
├── app.py                          # Streamlit app  
├── extra_trees_credit_model.pkl   # Trained ML model  
├── Sex_encoder.pkl                # Encoders for categorical features  
├── Housing_encoder.pkl  
├── Saving accounts_encoder.pkl  
├── Checking account_encoder.pkl  
├── target_encoder.pkl             # (if used)  
├── requirements.txt               # Python dependencies  

⚡ How to Run Locally
# Clone the repo  
git clone https://github.com/<YourUsername>/credit-risk.git  
cd credit-risk  

# Install dependencies  
pip install -r requirements.txt  

# Run the app  
streamlit run app.py  
This app uses the publicly available German Credit Risk dataset from Kaggle.
