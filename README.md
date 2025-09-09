# Liver_Cirrhosis_Prediction

This project is a Flask web application that predicts whether a patient is likely to have liver disease based on medical and lifestyle input features.
It uses a Machine Learning model (liver_prediction.pkl) trained with patient data and integrates it into a simple web interface.

## 🚀 Features

✅ User-friendly web form to enter patient details (age, gender, blood test results, lifestyle habits, etc.)

✅ Predicts "Diabetes" or "Non-Diabetes" based on model output (labels can be adjusted based on dataset)

✅ Built with Flask and Scikit-learn

✅ Easily deployable on local system or cloud platforms (Heroku, Render, etc.)

## 📂 Project Structure

├── Demo/                   # Demo files

├── Documentation/          # Project documentation

├── Ideation Phase/         # Initial idea and brainstorming

├── Performance Testing/    # Testing reports

├── Project Design Phase/   # Design related files

├── Project Planning Phase/ # Planning related files

├── Requirement Analysis/   # Requirement analysis documents

├── screenshots/            # Screenshots of the app

├── static/                 # CSS, JS, Images

├── templates/              # HTML templates (page.html, index.html)

├── app.py                  # Main Flask application

├── liver_prediction.pkl    # Trained ML model

└── README.md               # Project description

## ⚙️ Installation & Setup

#### 1)Clone this repository

```bash
git clone https://github.com/CHENNAMSETTYGURUTEJA/Liver_Cirrhosis_Prediction.git
cd Liver_Cirrhosis_Prediction
```

#### 2)Create a virtual environment (optional but recommended)

```bash
python -m venv venv
```

```bash
source venv/bin/activate   # On Mac/Linux
```

```bash
venv\Scripts\activate      # On Windows
```

#### 3)Install dependencies

```bash
pip install -r requirements.txt
```

#### 4)Run the Flask app

```bash
python app.py
```

## 🧪 Usage

1️⃣Open the web app in your browser.

2️⃣Fill in the patient’s details (age, gender, blood test results, alcohol history, etc.).

3️⃣Submit the form.

4️⃣The app will display "Diabetes" or "Non-Diabetes" as prediction output.

## 📸 Output

<img width="1918" height="907" alt="Screenshot 2025-06-22 162721" src="https://github.com/user-attachments/assets/8cb743ea-ec7b-4937-bba4-bf853c6bf4ec" /> 
<img width="1908" height="886" alt="Screenshot 2025-06-22 171228" src="https://github.com/user-attachments/assets/020e0d16-bcc9-4520-a134-855793c7794e" />
<img width="1905" height="410" alt="Screenshot 2025-06-22 171243" src="https://github.com/user-attachments/assets/8086d9db-f24c-4d23-8677-2f0546779386" />
<img width="902" height="217" alt="Screenshot 2025-06-22 163020" src="https://github.com/user-attachments/assets/74ff21ed-828e-4a78-8910-0c282d336060" />

