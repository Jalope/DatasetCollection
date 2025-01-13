# DatasetCollection
Public repository containing datasets from various projects for analysis and visualization

# Public Data Repository

This repository contains datasets from various projects, organized for easy access and integration. The datasets can be downloaded directly or loaded programmatically using Python.

## 📂 Repository Structure
The datasets are organized by project folders:
- **Project 1:** Regresion - Diamonds Prices
  - `project1/Diamonds_Prices2022.csv`
- **Project 2:** Clasification - Evolution:
  - `Evolution_DataSets.csv`

---

## 📖 How to Load the Data in Python

You can use the [pandas](https://pandas.pydata.org/) library to load the datasets directly from this repository.

### 1. Install pandas
If you don't already have pandas installed, you can install it using pip:
```bash
pip install pandas
```

### 2. Load a CSV File from the Repository
Here’s how you can load a file directly from the repository using its raw URL:

```python
import pandas as pd

# Example: Load the file from Project 1
url = "https://raw.githubusercontent.com/Jalope/DatasetCollection/refs/heads/main/Project_1/Diamonds%20Prices2022.csv"
data = pd.read_csv(url)

# Display the first few rows of the dataset
data.head()
```

---

## 📋 Notes
- Make sure the raw URL of the file is correctly formatted. To get the raw URL, open the file in GitHub, click on the **"Raw"** button, and copy the link.
- Keep your pandas library updated for compatibility with the latest features.

---

If you encounter any issues or have questions, feel free to open an issue in this repository. 😊
