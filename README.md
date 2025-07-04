# 🩺**careBOT** — AI Disease & Treatment Advisor 

> **An intelligent clinical assistant built with Machine Learning and NLP to analyze symptoms, predict possible diseases, and recommend categorized treatments.**

---

## 📸 Screenshots

### 🔹 Main Interface

User-friendly input area with live character counter and example symptoms.

<img width="692" alt="image" src="https://github.com/user-attachments/assets/fab6e5fa-ad0c-46a1-aa27-c106d7e3e2bd" />


### 🔹 Diagnosis Results 

Predicted disease, severity badge, and confidence percentage.

<img width="692" alt="image" src="https://github.com/user-attachments/assets/a0ac338f-3571-4a10-8394-97bcd315b954" />



### 🔹Treatment Suggestions

AI-generated summary with categorized, expandable treatment lists.

<img width="692" alt="image" src="https://github.com/user-attachments/assets/6ffe72a4-a739-4721-9e27-f33c9927354c" />


---

## ✅ Key Features

| Feature                      | Description                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------- |
| 🧠 **AI-Based Diagnosis**    | Predicts diseases from free-text symptoms using trained ML model                   |
| 📊 **Severity Indicator**    | Displays low/medium/high severity visually                                         |
| 💊 **Treatment Recommender** | Suggests treatments grouped by type: Topical, Systemic, Biologics, Lifestyle       |
| 🧾 **Report Generator**      | Generates downloadable diagnosis reports in `.txt` format                          |
| 🤖 **Smart Summarizer**      | Uses Hugging Face's BART model to summarize long treatment lists                   |
| 🎨 **Interactive UI**        | Built with `ipywidgets`, `matplotlib`, and styled HTML for a clean user experience |

---

## ⚙️ How It Works

1. **Symptom Entry**: User types natural-language symptoms.
2. **Prediction**: ML model (TF-IDF + Classifier) identifies the most probable disease.
3. **Severity Detection**: Based on keywords in user input.
4. **Treatment Matching**: Retrieves treatments from a curated `.json` knowledge base.
5. **Summarization**: Uses NLP to generate a human-readable overview.
6. **Report Output**: Displays result and enables downloading a report.

---

## 🧠 Tech Stack

* `Python`, `Jupyter Notebook`
* `scikit-learn` (TF-IDF Vectorizer + Classifier)
* `transformers` (`distilbart-cnn-12-6`)
* `joblib`, `json`, `matplotlib`, `seaborn`
* `ipywidgets`, `HTML`, `CSS`

---

## 📁 Project Structure

```
carebot/
├── models/
│   ├── text_disease_model.pkl
│   ├── tfidf_vectorizer.pkl
│   └── label_encoder.pkl
├── treatement/
│   └── cpu_optimized_treatments.json

├── CareBOT.ipynb
├── README.md
└── diagnoses_report.txt
```

---

## 🚀 Getting Started

### 1. Clone Repository

```bash
git clone https://github.com/Zuhaib23/careBOT-AI-Disease-Treatment-Advisor.git
cd careBOT-AI-Disease-Treatment-Advisor
```
### 2. Install Dependencies

## 📦 Requirements

```
scikit-learn
joblib
ipywidgets
transformers
matplotlib
seaborn
```
```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
jupyter notebook
# Open and run `CareBOT.ipynb`
```

---

## 📄 Sample Use Case

> **Input**:

```
Itchy red skin with silver scales and mild burning sensation.
```

> **Output**:

* **Predicted Disease**: Psoriasis
* **Confidence**: 91.3%
* **Severity**: Medium
* **Top Treatments**: Corticosteroids, tar-based ointments, phototherapy, etc.

---



---

## ⚠️ Disclaimer

This tool is for **educational and clinical decision support** only. It **does not replace professional medical consultation**. Always consult a licensed healthcare provider for diagnosis and treatment.

---

## 🙌 Acknowledgements

* [Hugging Face Transformers](https://huggingface.co/)
* [Scikit-learn](https://scikit-learn.org/)
* [ipywidgets](https://ipywidgets.readthedocs.io/)
* Medical dataset compiled and optimized manually

---

## 📬 Contact

Created by **Muhammad Zuhaib**
📧 Email: zohaibrajput0311@gmail.com
🔗 GitHub: https://github.com/Zuhaib23

---

> ⭐ *If you found this project helpful, please give it a star and share it!*

---

