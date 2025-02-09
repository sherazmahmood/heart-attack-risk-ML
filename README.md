# Heart Attack Risk Prediction

This project aims to predict the risk of heart attacks using machine learning algorithms. By analyzing various health parameters, the model provides insights into an individual's likelihood of experiencing a heart attack.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Modeling](#modeling)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease is a leading cause of mortality worldwide. Early prediction can aid in timely medical interventions. This project utilizes machine learning techniques to assess heart attack risk based on patient data.

## Dataset

The dataset used in this project contains various health-related parameters. Each row represents a patient, and columns include attributes such as age, cholesterol levels, blood pressure, and more.

## Features

Key features in the dataset include:

- **Age**: Patient's age in years
- **Sex**: Gender of the patient
- **Chest Pain Type**: Type of chest pain experienced
- **Resting Blood Pressure**: Blood pressure at rest
- **Cholesterol**: Serum cholesterol level
- **Fasting Blood Sugar**: Blood sugar levels after fasting
- **Resting ECG**: Results of resting electrocardiogram
- **Max Heart Rate**: Maximum heart rate achieved
- **Exercise Induced Angina**: Presence of angina induced by exercise
- **ST Depression**: Depression induced by exercise relative to rest
- **Slope**: Slope of the peak exercise ST segment
- **Number of Major Vessels**: Number of major vessels colored by fluoroscopy
- **Thalassemia**: Blood disorder status

## Modeling

The project explores various machine learning algorithms to predict heart attack risk, including:

- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines
- Neural Networks

## Results

The models are evaluated based on accuracy, precision, recall, and F1-score. Detailed results and performance metrics are provided in the repository.

## Usage

To run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/sherazmahmood/heart-attack-risk-ML.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-attack-risk-ML
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```bash
   python main.py
   ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
