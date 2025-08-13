# 🧠 MediMind – AI-Based Disease Prediction System

**MediMind** is a Python-based **AI healthcare assistant** that predicts diseases from symptoms using **Decision Tree Classifiers** and provides medical descriptions & precautionary measures.  
It leverages **Machine Learning**, **Natural Language Processing**, and a **speech engine** for interactive diagnosis.

---

## 📌 Features
- **Disease Prediction** – Uses a Decision Tree model trained on a medical dataset.
- **Symptom Matching** – Intelligent symptom pattern matching and suggestions.
- **Secondary Prediction** – Cross-verifies using an additional trained model.
- **Severity Assessment** – Calculates urgency level based on symptoms and duration.
- **Medical Descriptions** – Explains diseases with details from dataset.
- **Precautionary Advice** – Suggests steps to manage health.
- **Voice Output** – Speaks predictions using `pyttsx3`.

---

## 🏗️ Tech Stack
- **Language:** Python 3.9+
- **Libraries:**  
  - `pandas` – Data handling  
  - `numpy` – Numerical computation  
  - `scikit-learn` – Machine learning models  
  - `pyttsx3` – Text-to-speech output  
  - `csv` – Data file handling

---

## 📂 Project Structure
Medimind/
│
├── dataset/
│ ├── Training.csv
│ ├── Testing.csv
│ ├── symptom_Description.csv
│ ├── Symptom_severity.csv
│ └── symptom_precaution.csv
│
├── medimind.py # Main script
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/medimind.git
cd medimind
2️⃣ Install dependencies

pip install -r requirements.txt
3️⃣ Run the program

python medimind.py
📊 How It Works
Load Dataset – Reads training & testing CSV files containing symptoms and prognosis.

Preprocess Data – Encodes target labels, splits data for training/testing.

Train Model – Uses DecisionTreeClassifier with cross-validation.

Predict Disease – Based on symptoms entered by the user.

Assess Severity – Calculates if doctor consultation is needed.

Provide Advice – Displays disease description & precaution list.

Voice Feedback – Speaks out the result.

📸 Example Interaction

please Your Name
John
hello  John
Enter the symptom you are experiencing
fever
searches related to input:
0) fever
Okay. From how many days ? : 5
Are you experiencing any headache ? : yes
You may have  Dengue
Dengue is a mosquito-borne viral disease...
Take following measures :
1) Drink plenty of fluids
2) Rest as much as possible
3) Monitor temperature
4) Consult a doctor if symptoms persist
confidence level is 0.8
📌 Dataset Information
Training.csv – Main dataset for training the model.

Testing.csv – Used for evaluation and cross-validation.

Symptom_severity.csv – Maps symptoms to severity levels.

symptom_Description.csv – Contains disease descriptions.

symptom_precaution.csv – Lists precautionary measures.

📄 License
This project is licensed under the MIT License – free to use and modify.

👨‍💻 Author
Ritesh Kashyap
[GitHub](https://github.com/Riteshgraphic) | Email


Steps 
install dependencies
load dataset
run the file
