# Healthcare Assistant - Disease Prediction System

This project implements a **Healthcare Assistant** that predicts potential diseases based on user-provided symptoms and demographic details. It uses machine learning techniques to analyze inputs and provide probabilistic predictions, helping users and healthcare professionals anticipate possible health issues.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Sample Input/Output](#sample-inputoutput)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Introduction

The Healthcare Assistant is a terminal-based application that accepts inputs like age, gender, and symptoms to predict potential diseases. It uses a **Gradient Boosting Classifier** for prediction and provides probabilities for multiple possible diseases.

---

## Features

- **Symptom Analysis:** Accepts multiple symptoms like fever, cough, headache, and fatigue.
- **Demographic Inputs:** Factors in age and gender for predictions.
- **Probability Distribution:** Displays probabilities for all possible diseases, sorted in descending order.
- **Most Likely Disease:** Highlights the most probable disease based on user input.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - `numpy`: For numerical operations
  - `pandas`: For data manipulation
  - `scikit-learn`: For machine learning and preprocessing

---

## How It Works

1. **Data Preparation:**
   - A predefined dataset of symptoms and diseases is used for training.
   - Data preprocessing includes encoding gender, imputing missing values, and scaling numerical features.

2. **Model Training:**
   - A **Gradient Boosting Classifier** is trained on the dataset to predict diseases based on symptoms.

3. **User Input:**
   - Users are prompted to input details like age, gender, and symptoms through a terminal interface.

4. **Prediction:**
   - The model predicts probabilities for multiple diseases based on user inputs.
   - Results are displayed in a clear and sorted format.

---

## Getting Started

### Prerequisites
Make sure you have Python installed on your system. You also need the following libraries:
- `numpy`
- `pandas`
- `scikit-learn`

You can install these using:
```bash
pip install numpy pandas scikit-learn 
```

Running the Project
Clone this repository:
```bash
git clone https://github.com/Nitya18-dev/Smart_Healthcare_Assistant.git
cd healthcare-assistant
```
Run the script: 
```bash
python healthcare_assistant.py
```
### Usage

Launch the script in your terminal.

Enter the requested details when prompted:

- Age: Numeric value

- Gender: 0 for Male, 1 for Female

- Symptom presence: 1 for Yes, 0 for No

Review the predicted disease probabilities and the most probable disease.

### Future Improvements
- Expand Dataset: Incorporate more symptoms, diseases, and real-world data for better accuracy.
- Explainable AI (XAI): Add interpretability features to explain predictions.
- User Interface: Develop a graphical interface for better usability.
- Cloud Deployment: Deploy as a web or mobile app for accessibility.
### License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as per the terms of the license.

### Contributing
Contributions are welcome! If you have ideas for improvements, please open an issue or submit a pull request.
