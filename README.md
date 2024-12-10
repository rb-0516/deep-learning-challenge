# Deep Learning Challenge - Nonprofit Success Predictor

## Overview
This project develops a binary classification model using deep learning to help Alphabet Soup predict the success of funding applicants. The model analyzes various organizational metadata to determine which applicants have the best chance of success in their ventures.

## Project Structure
```
deep-learning-challenge/
│
├── notebooks/
│   ├── AlphabetSoupCharity.ipynb        # Initial model development
│   └── AlphabetSoupCharity_Optimization.ipynb  # Model optimization
│
├── models/
│   ├── AlphabetSoupCharity.h5           # Initial model weights
│   └── AlphabetSoupCharity_Optimization.h5  # Optimized model weights
│
└── README.md
```

## Dataset
The analysis uses a dataset containing information about 34,000+ organizations that have received funding from Alphabet Soup. Key features include:

- Application type
- Industry affiliation
- Government organization classification
- Use case for funding
- Organization type
- Income classification
- Special considerations
- Funding amount requested

## Implementation Steps

### 1. Data Preprocessing
- Remove non-beneficial ID columns (EIN and NAME)
- Identify target and feature variables
- Handle rare categorical variables
- Encode categorical variables
- Split dataset into training and testing sets
- Scale numerical features

### 2. Model Development
- Design neural network architecture
- Compile and train the model
- Implement callbacks for model checkpoints
- Evaluate model performance
- Export trained model to HDF5 format

### 3. Model Optimization
The optimization process includes:
- Feature engineering
- Architecture modifications
- Hyperparameter tuning
- Training process adjustments

## Technologies Used
- Python
- TensorFlow
- Keras
- Pandas
- Scikit-learn
- Google Colab

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/deep-learning-challenge.git
```

2. Navigate to the project directory:
```bash
cd deep-learning-challenge
```

3. Install required dependencies:
```bash
pip install tensorflow pandas scikit-learn
```

## Usage
1. Open the Jupyter notebooks in Google Colab
2. Upload the provided dataset
3. Execute the cells sequentially to:
   - Preprocess the data
   - Train the model
   - Evaluate results
   - Optimize the model

## Results
**Model Performance:**
* Target accuracy: 75%
* Achieved accuracy: 78.75%
* Loss metric: 0.447

## Contributing
This project was created as part of a data analytics challenge. While it's not open for contributions, you're welcome to fork the repository and adapt it for your own purposes.

## Data
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/ Links to an external site.
