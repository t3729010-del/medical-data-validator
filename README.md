# Medical Data Validator 🏥

## 📌 Overview

Medical Data Validator is a Python-based tool designed to check structured medical records for errors, missing values, and inconsistencies. It applies rule-based validation techniques to ensure data integrity and correctness.

This project demonstrates how healthcare data can be validated using simple programming logic before further processing or analysis.

---

## ⚙️ Features

* Validates patient records using predefined rules
* Checks for:

  * Invalid Patient IDs
  * Incorrect age values
  * Invalid gender entries
  * Missing or incorrect visit IDs
* Detects inconsistent or incorrect data formats
* Provides clear output indicating errors

---

## 🧠 How It Works

The system uses rule-based validation logic:

* Patient ID must follow a specific format
* Age must be within a valid range
* Gender must match allowed values (e.g., Male/Female)
* Visit ID must not be missing or incorrect

The program processes a predefined dataset and prints validation results.

---

## 📂 Project Structure

* `Medical Data Validator.ipynb` → Main notebook containing validation logic
* `README.md` → Project documentation

---

## 🚀 How to Run

1. Install Python (3.x)
2. Open the notebook using Jupyter Notebook or VS Code
3. Run all cells

---

## 📊 Example Output

The system identifies invalid records and prints error messages such as:

* "Invalid Patient ID"
* "Age out of range"
* "Missing Visit ID"

---

## ⚠️ Limitations

* Uses predefined sample data (no user input yet)
* No file upload support (CSV/JSON not implemented)
* No graphical interface

---

## 🔮 Future Improvements

* Add CSV/Excel file input
* Build a user interface (GUI or web app)
* Integrate with real healthcare datasets
* Improve validation rules
* Add automated reporting

---

## 💡 Use Case

This project can be used as a foundation for:

* Healthcare data preprocessing
* Data cleaning pipelines
* Hospital record validation systems

---

## 👨‍💻 Author

Taimoor Ahmad

---
