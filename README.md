# PREDICTION_OF_HOTEL_BOOKING_CANCELLATION

## Project Overview
This project focuses on predicting hotel booking cancellations using supervised machine learning (Classification).

## Introduction
Hotel booking cancellation is a common issue that can lead to significant revenue loss for hotels. This project aims to build a predictive model to identify bookings that are likely to be canceled, enabling hotels to take proactive measures.

## Dataset
The dataset used in this project contains various features related to hotel bookings. It includes information such as booking dates, customer demographics, and booking details. The dataset is preprocessed to handle missing values, encode categorical variables, and scale numerical features.

## Installation
To run the notebook, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/harshithas003/PREDICTION_OF_HOTEL_BOOKING_CANCELLATION.git
   ```
2. Navigate to the project directory:
   ```bash
   cd PREDICTION_OF_HOTEL_BOOKING_CANCELLATION
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook hotel-booking-cancellation-prediction.ipynb
   ```

## Model Evaluation
The notebook includes the following models for prediction:
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost

Each model is evaluated using various metrics such as accuracy, precision, recall, F1-score, and AUC.

## Results
The XGBoost model achieved the best performance in predicting hotel booking cancellations:

- **Accuracy**: 85.04%
- **F1-score (Class 1)**: 79.85%
- **Precision (Class 1)**: 79.76%
- **Recall (Class 1)**: 79.94%
- **AUC (Class 1)**: 92.17%

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
Special thanks to the contributors of the dataset and the open-source community for their invaluable resources and tools.
