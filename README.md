# Biodiversity Loss Prediction under Climate Change

This project aims to predict biodiversity loss under varying climate change scenarios using an ensemble of deep learning models.

## Project Overview

We implement multiple deep learning architectures including:
- **MLP** (Multi-Layer Perceptron)
- **CNN** (Convolutional Neural Network)
- **LSTM** (Long Short-Term Memory Network)

These models are trained on climate and environmental data and ensembled to improve prediction accuracy.

## Project Structure

📁 Biodiversity-Loss-Prediction
│
├── data/
│ └── biodiversity_climate_data.csv # Dataset (features + labels)
├── biodiversity_loss_prediction.py # Main training and evaluation script
├── biodiversity_loss_predictions.xlsx # Output prediction results
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── .gitignore # Ignored files and folders

csharp
Copy
Edit

## Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
Contents of requirements.txt:

nginx
Copy
Edit
torch
scikit-learn
pandas
numpy
openpyxl
How to Run
Prepare your dataset (data/biodiversity_climate_data.csv), with:

Environmental features (temperature, precipitation, CO₂ concentration, habitat index, etc.)

Target variable: biodiversity_loss

Run the script:

bash
Copy
Edit
python biodiversity_loss_prediction.py
Outputs:

Model evaluation metrics (MSE, R² Score)

Prediction results saved to biodiversity_loss_predictions.xlsx

Dataset Example
csv
Copy
Edit
temperature,precipitation,co2_concentration,habitat_index,biodiversity_loss
15.2,1200,400,0.8,5.1
16.0,1100,405,0.75,5.6
...
Output
biodiversity_loss_predictions.xlsx containing true and predicted biodiversity loss values.

Evaluation metrics printed in the console.

Acknowledgements
Climate Data Sources: WorldClim, IPCC Data Distribution Centre

Biodiversity Data Sources: GBIF, IUCN Red List

Author
Ayebawanaemi Geraldine Winston
