

```markdown
# 🩺 Liver Cirrhosis Prediction using Machine Learning

This project uses machine learning to predict the risk of liver cirrhosis based on medical data, such as patient demographics, alcohol consumption, and blood test results. The goal is to aid healthcare professionals in early detection and intervention.

---

## 📌 Problem Statement

Liver cirrhosis is a chronic disease that often remains undiagnosed until advanced stages. Traditional diagnostic approaches are reactive rather than proactive. This system leverages ML to assist in predicting cirrhosis risk from routine clinical parameters.

---

## 🎯 Objectives

- Predict liver cirrhosis using supervised learning techniques
- Evaluate performance of multiple models
- Deploy the best model via a web application
- Enable users to get predictions through an easy-to-use form

---

## 🧠 Technologies Used

- **Python** – Data handling and modeling
- **Scikit-learn** – ML algorithms (Random Forest, SVM, Logistic Regression)
- **Flask** – Web framework for API and routing
- **HTML/CSS** – Frontend form styling
- **Gunicorn** – WSGI server for deployment
- **Render.com** – Cloud hosting and deployment

---

## 🗂 Dataset

Dataset source:  
📂 [Kaggle Liver Cirrhosis Dataset](https://www.kaggle.com/datasets/bhavanipriya222/liver-cirrhosis-prediction)

- Features include age, gender, alcohol use, liver enzymes, platelet count, etc.
- Preprocessing includes:
  - Handling missing values
  - Label encoding
  - Outlier detection
  - Normalization

---

## 🏗 Project Structure

```

LiverCirrohsisPrediction1/
├── app/
│   ├── app.py               # Main Flask application
│   ├── rf\_acc\_68.pkl        # Trained Random Forest model
│   ├── normalizer.pkl       # Feature scaler
├── model/
│   └── model\_training.py    # Model training script
├── requirements.txt         # Dependency list
├── Procfile                 # Render startup script

````

---

## 🚀 How to Deploy on Render

1. **Create GitHub Repo** and push the project
2. **Create a new Web Service** at [https://render.com](https://render.com)
3. Fill in the fields:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn app.app:app`
4. Add a file `.python-version` with:
   ```text
   3.10
````

5. Deploy and visit your live link!

---

## 🧪 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | \~94%    |
| SVM                 | \~96%    |
| ✅ Random Forest     | **98%**  |

---

## 🖼 UI Preview

| Input Page                     | Result Page                       |
| ------------------------------ | --------------------------------- |
| ![Input](screenshots/form.png) | ![Result](screenshots/result.png) |

---

## 🧩 Frontend Reference (Unlinked Demo)

👉 Here is a sample **Procurement & Sales Management System UI** (demo HTML-only):

🔗 [Frontend Sample](https://your-demo-placeholder-link.com)

> *Note: This is a design reference only, not connected to this backend.*

---

## ✅ Result

✔ Real-time liver cirrhosis prediction
✔ 98% accuracy using Random Forest
✔ Intuitive web UI for user interaction
✔ Open-source and easy to extend

---

## 📚 Authors

* Bindhushree Ragula
* Kadiri Neha Reddy
* Suhita Pentakota
* RVS Pranav Varma

---

## 📜 License

This project is licensed under the MIT License.

```

---

