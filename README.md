🌾 Crop Prediction Project

This is a Machine Learning-based Crop Recommendation System that predicts the most suitable crop based on soil and environmental parameters.

## 🎯 Accuracy
Achieved **94.5% accuracy** using RandomForestClassifier.

## 🚀 Features
- Built using Python, Jupyter Notebook
- Frontend using HTML & Flask
- Input parameters: N, P, K, Temperature, Humidity, pH, Rainfall

## 📁 Files
- `crop_prediction_project.ipynb` – Model Training
- `app.ipynb` – Flask Integration
- `crop_prediction.html` – Web UI

## 🔧 Tech Stack
- Python (Sklearn, Pandas, Numpy)
- Jupyter Notebook
- Flask
- HTML/CSS

## 📌 Run Locally
```bash
flask run
🧠 Output Example
Predicted crop: rice, maize, etc. based on inputs.

----------------------------------------------------
Project purpose & utility🌾

This project is a machine learning-based **Crop Prediction System** that recommends the most suitable crop for cultivation based on environmental and soil conditions. It aims to assist **farmers, agri-scientists, and agri-tech companies** in making **data-driven agricultural decisions** to maximize crop yield and sustainability.

--->>>>

## 🧩 Utility of This Project

Modern agriculture often suffers from poor crop selection due to lack of expert knowledge and local soil analysis. This project solves that by:

- Predicting the best crop based on nutrient content and climate data
- Reducing trial-and-error methods in farming
- Enhancing decision-making using AI/ML
- Saving resources (water, fertilizer) by recommending suitable crops

It can be integrated into:
- **Mobile apps for farmers**
- **Agri dashboards**
- **Government advisory platforms**

---

## 🎯 Model Accuracy

- Achieved **94.5% accuracy** using **Random Forest Classifier**
- Trained on real-world agricultural data (N, P, K, temperature, humidity, pH, rainfall)

---

## 🧠 Features

- 📈 Predicts crop based on:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature (°C)
  - Humidity (%)
  - pH
  - Rainfall (mm)
- 🌐 Web UI for user input
- ⚙️ Backend powered by Flask
- 🧪 Easily testable using Jupyter Notebook

---

## 🚀 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core ML development |
| Scikit-learn | Model training & accuracy |
| Pandas/Numpy | Data processing |
| Jupyter Notebook | Development & visualization |
| Flask | Backend framework |
| HTML/CSS | Web frontend |

---

## 💻 Project Structure

Crop Project Using ML/
├── crop_prediction_project.ipynb # ML model training
├── app.ipynb # Web integration (Flask)
├── crop_prediction.html # Frontend form
├── static/ CSS files
├── templates/ # HTML templates for Flask

yaml
Copy
Edit

---

## 🧪 How to Run Locally

> ⚠️ Make sure you have Python 3.7+ and Flask installed

```bash
git clone https://github.com/Richa-Ranjan/Crop-Prediction_Proj.git
cd Crop-Prediction_Proj

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
Go to http://127.0.0.1:5000 in your browser and try it out!

📸 Sample Prediction
Inputs:

N: 90
P: 42
K: 43
Temp: 22.5°C
Humidity: 80%
pH: 6.5
Rainfall: 190mm

🎯 Predicted Crop: rice

🙋‍♀️ Author
Richa Ranjan
GitHub

📜 License
This project is open-source and free to use for educational or non-commercial purposes.
