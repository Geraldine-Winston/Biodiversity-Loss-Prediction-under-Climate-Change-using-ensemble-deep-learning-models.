Biodiversity Loss Prediction under Climate Change
This project aims to predict biodiversity loss under varying climate change scenarios using an ensemble of deep learning models.

Project Overview
We implement multiple deep learning architectures including:

MLP (Multi-Layer Perceptron)

CNN (Convolutional Neural Network)

LSTM (Long Short-Term Memory Network)

These models are trained on climate and environmental data and ensembled to improve prediction accuracy.

Project Structure
bash
Copy
Edit
📁 Biodiversity-Loss-Prediction
│
├── biodiversity_loss_prediction.py    # Main training and evaluation script
├── biodiversity_loss_predictions.xlsx # Output prediction results
├── README.md                           # Project documentation
└── data/
    └── biodiversity_climate_data.csv   # Input dataset (features + label)
Requirements
To install the necessary packages, run:

bash
Copy
Edit
pip install -r requirements.txt
requirements.txt includes:

nginx
Copy
Edit
torch
scikit-learn
pandas
numpy
openpyxl
How to Run
Prepare the dataset with environmental features and a target variable biodiversity_loss.

Execute the script:

bash
Copy
Edit
python biodiversity_loss_prediction.py
The model outputs predictions and saves them to an Excel file.

Dataset Example
csv
Copy
Edit
temperature,precipitation,co2_concentration,habitat_index,biodiversity_loss
15.2,1200,400,0.8,5.1
16.0,1100,405,0.75,5.6
...
Output
biodiversity_loss_predictions.xlsx with true and predicted biodiversity loss values.

Evaluation metrics including Mean Squared Error (MSE) and R² Score.

Acknowledgements
Climate Data Sources: WorldClim, IPCC Data Distribution Centre

Biodiversity Data Sources: GBIF, IUCN Red List

Author
Ayebawanaemi Geraldine Winston
