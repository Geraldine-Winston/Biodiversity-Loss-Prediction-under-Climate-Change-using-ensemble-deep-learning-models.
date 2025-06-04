# Biodiversity Loss Prediction under Climate Change

This project predicts **biodiversity loss** under **climate change** scenarios using an ensemble of **deep learning models**.

## Project Overview

We implemented an ensemble of three deep learning architectures:
- **MLP** (**M**ulti-**L**ayer **P**erceptron)
- **CNN** (**C**onvolutional **N**eural **N**etwork)
- **LSTM** (**L**ong **S**hort-Term **M**emory Network)

The models are trained on **climate** and **environmental data**, and their predictions are combined to improve **accuracy** and **robustness**.

## Project Structure

```
📁 Biodiversity-Loss-Prediction
├── data/
│   └── biodiversity_climate_data.csv    # Dataset (features + labels)
├── biodiversity_loss_prediction.py      # Main training and evaluation script
├── biodiversity_loss_predictions.xlsx   # Output prediction results
├── README.md                             # Project documentation
├── requirements.txt                      # Python dependencies
└── .gitignore                             # Ignored files and folders
```

## Requirements

Install all necessary Python packages by running:

```bash
pip install -r requirements.txt
```

**`requirements.txt` includes:**

```
torch
scikit-learn
pandas
numpy
openpyxl
```

## How to Run

1. Place your **dataset** inside the `data/` directory as `biodiversity_climate_data.csv`. The dataset should include:
   - **Environmental features** (e.g., temperature, precipitation, CO₂ concentration, habitat index, etc.)
   - **Target variable**: `biodiversity_loss`

2. Run the script:

```bash
python biodiversity_loss_prediction.py
```

3. After running:
   - **Evaluation metrics** such as **MSE** (Mean Squared Error) and **R² Score** will be printed.
   - **Predictions** will be saved to `biodiversity_loss_predictions.xlsx`.

## Dataset Example

```csv
temperature,precipitation,co2_concentration,habitat_index,biodiversity_loss
15.2,1200,400,0.8,5.1
16.0,1100,405,0.75,5.6
14.8,1300,398,0.85,4.9
```

## Output

- **`biodiversity_loss_predictions.xlsx`**: Contains the true and predicted biodiversity loss values.
- **Console Output**: Displays evaluation metrics.

## Acknowledgements

- Climate Data Sources: [**WorldClim**](https://www.worldclim.org/)
- [**IPCC Data Distribution Centre**](https://www.ipcc-data.org/)
- Biodiversity Data: [**GBIF**](https://www.gbif.org/), [**IUCN Red List**](https://www.iucnredlist.org/)

## Author

**Ayebawanaemi Geraldine Winston**

