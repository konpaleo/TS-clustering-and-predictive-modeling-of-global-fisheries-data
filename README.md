# TS-clustering-and-predictive-modeling-of-global-fisheries-data
This project involves data preprocessing, EDA, time series clustering and regression practices.\
More details can be found in the presentation file `presentation.pdf`.

## Getting Started

### Data Import

There are two options for data import:
1. **Google Colab**: Use the 1st import cell for seamless integration with Google Colab (comment out the 2nd import cell).
2. **Local Execution**: Use the 2nd import cell for local execution. Ensure you have set up a virtual environment and installed all necessary modules.

### Setup

For local execution, please create a virtual environment and install the required modules using the provided `requirements.txt` file.

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows

venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install required modules
pip install -r requirements.txt
```

## Data

The dataset files are located in the `data` folder. Ensure this folder contains the following files:

- `global-fishery-catch-by-sector.csv`
- `capture-fishery-production.csv`
- `aquaculture-farmed-fish-production.csv`
- `fish-and-seafood-consumption-per-capita.csv`
- `fish-stocks-within-sustainable-levels.csv`
