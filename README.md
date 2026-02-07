# Phishing URL Detection (Cybersecurity + Data Analytics)

This project classifies URLs as phishing vs legitimate using engineered URL features and a LightGBM model.

## Files
- `phishing_detection.ipynb` : main notebook
- `phishing_detection.html` : exported notebook report
- `requirements.txt` : python dependencies
- `phishing_model_bundle.joblib` : saved model + threshold
- `outputs_test_predictions.csv` : test predictions

## Run locally
```bash
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
python -m notebook

## Step 3) Initialize git + commit
```bash
git init
git add .
git commit -m "Phishing URL detection project"
git branch -M main
git remote add origin https://github.com/<Satyam4139-git>/<phishing_project>.git
git push -u origin main
