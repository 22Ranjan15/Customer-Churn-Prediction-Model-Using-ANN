# Customer Churn Prediction Model

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Result](#result)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
 
## Overview
This project features a simple yet effective customer churn prediction model built using Artificial Neural Networks (ANN). The model is designed to predict the likelihood of a customer discontinuing service based on historical data, leveraging deep learning techniques to achieve high accuracy. The project includes data preprocessing, model training, and evaluation, offering a practical tool for businesses to enhance customer retention strategies.

## Project Structure
`Customer_Churn_Prediction/`  
`├── myenv/`  
`├── app.py`  
`├── Churn_Modelling.csv`  
`├── Experiments.ipynb`  
`├── label_encoder_gender.pkl`  
`├── model.h5`  
`├── onehot_encoder_geo.pkl`  
`├── Prediction.ipynb`  
`├── requirements.txt`  
`└── scaler.pkl`  

## Technologies Used
- **Frontend & Backend**: Python, Streamlit
- **Deep Learning Libraries**: TensorFlow, Keras, Scikit-learn, Pandas, NumPy
- **Deployment**: Streamlit Cloud

## Features
- **Data Preprocessing**: Encoding categorical variables, and normalizing data.
- **Model Training**: Building and training the ANN model with layers to capture complex patterns.
- **Model Evaluation**: Assessing model performance using metrics like accuracy.
- **Practical Application**: The model provides actionable insights, helping businesses identify customers at risk of churning and enabling proactive retention efforts.

## Installation
Follow these steps to get a copy of the project running on your local machine.

### Prerequisites
- Python 3.12+
- pip (Python package installer)
- Virtualenv (Optional but recommended)
### Installation Steps
1. Clone the repository:
  `git clone https://github.com/your-username/customer-churn-prediction.git`

2. Navigate to the project directory:
  `cd customer-churn-prediction`

3. Install the required packages:
  `pip install -r requirements.txt`

## Result
The model is trained to predict customer churn with high accuracy **( 87% )**, providing businesses with insights to implement effective retention strategies. Evaluation metrics demonstrate the model's capability to identify potential churners, offering a reliable solution for customer retention.

## Contributing
Contributions are welcome! If you have suggestions, bug reports, or want to contribute to the code, please create an issue or submit a pull request.

### Steps to Contribute
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/22Ranjan15/Customer-Churn-Prediction-Model-Using-ANN/blob/256bd691d13e1c05bc95ebfc83887e1f1ead024a/LICENSE) file for details.

## Acknowledgements
Keras and TensorFlow for the ANN implementation.
The data used in this project for providing valuable insights.

## Contact
For any inquiries, feel free to reach out:

- **GitHub**: [22Ranjan15](https://github.com/22Ranjan15)
- **Email**: [msd23012@iiitl.ac.in](msd23012@iiitl.ac.in)
