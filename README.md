# 📄 Resume Category Prediction

## 📌 Overview

Welcome to the **Resume Category Prediction App**! This machine learning app predicts the job category of a resume based on its content. By analyzing the text within resumes, the model classifies them into various job categories, such as "Data Science", "HR", "Advocate", and many others.

---

## 💡 Features

- **📤 Resume File Upload**: Upload a resume in `.pdf`, `.docx`, or `.txt` format.
- **🔍 Text Extraction**: The app extracts the text from the uploaded resume automatically.
- **📊 Category Prediction**: Using a pre-trained machine learning model, the app predicts the job category of the uploaded resume.

---

## 🧾 Supported File Formats

The following file formats are supported for upload:

- 📄 **PDF**
- 📑 **DOCX**
- 📝 **TXT**

---

## 🛠️ How to Use

1. **Upload Resume**: Upload your resume in one of the supported file formats.
2. **Text Extraction**: The app will automatically extract the text content from your uploaded resume.
3. **Category Prediction**: Once the text is extracted, the app will predict the job category based on the content.

---

## 📦 Requirements

To run the app, make sure you have the following libraries installed:


pip install streamlit
pip install scikit-learn
pip install python-docx
pip install PyPDF2

---

### **Model Overview Section**:
```
## 🤖 Model Overview

The machine learning model used in this app is trained to classify resumes into different job categories. It utilizes various classification algorithms such as **SVC**, **KNeighborsClassifier**, **RandomForestClassifier**, and more. The categories include:

- **Data Science**
- **HR**
- **Advocate**
- **Arts**
- **Web Designing**
- **Mechanical Engineer**
- **Sales**
- **Health and Fitness**
- **Civil Engineer**
- **Java Developer**
- **Business Analyst**
- **SAP Developer**
- **Automation Testing**
- **Electrical Engineering**
- **Operations Manager**
- **Python Developer**
- **DevOps Engineer**
- **Network Security Engineer**
- **PMO**
- **Database**
- **Hadoop**
- **ETL Developer**
- **DotNet Developer**
- **Blockchain**
- **Testing**

---
## 🚀 Example Predictions

Here are a few examples of resumes and the categories they may fall into:

- **Data Scientist**: A resume featuring skills in machine learning, deep learning, and data analysis.
- **Personal Trainer**: A resume highlighting experience in health and fitness, certifications, and expertise in nutrition.
- **Network Security Engineer**: A resume with skills in cybersecurity, firewalls, and vulnerability assessments.

---

## 📝 Example Usage

You can upload a resume, and the app will predict the category. Here’s how it works:

1. **Upload** a resume in one of the supported formats (PDF, DOCX, or TXT).
2. **View** the extracted text.
3. **Get** the predicted category of the resume.

---
## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.




