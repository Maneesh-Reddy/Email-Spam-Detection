# Email Spam Detection Project README

## Project Overview
This project focuses on developing an **Email Spam Detection** system using machine learning techniques. The goal is to classify emails as either **spam** or **ham** (non-spam) based on their content.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used
- **Python 3**
- **Libraries**: 
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

## Dataset
The dataset used for this project is a CSV file containing email data. Each email is represented by various features derived from its content, with the target variable indicating whether it is spam (1) or ham (0).

### Dataset Structure
- **Features**: Independent variables (columns 1 to 3000).
- **Target**: Dependent variable (last column):
  - `0` = Non-spam email (ham)
  - `1` = Spam email

## Installation
To set up the project, follow these steps:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd email-spam-detection
   ```
3. Install the required libraries:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```

## Usage
1. Load the dataset:
   ```python
   import pandas as pd
   email_data = pd.read_csv('emails.csv')
   ```
2. Preprocess the data and split it into training and testing sets.
3. Train the models and evaluate their performance.

## Models Implemented
The following machine learning models have been implemented in this project:
1. **Multinomial Naive Bayes**
2. **Support Vector Classifier (SVC)**
3. **Random Forest Classifier**

Each model's performance is evaluated using accuracy scores and classification reports.

## Results
The results of the models are summarized as follows:
- **Multinomial Naive Bayes**: Accuracy ~ 94.66%
- **Support Vector Classifier**: Accuracy ~ 89.33%
- **Random Forest Classifier**: Accuracy ~ 97.44%

A bar plot comparing the accuracy of each model is generated for better visualization.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

