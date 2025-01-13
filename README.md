# DatasetCollection
Public repository containing datasets from various projects for analysis and visualization

# Public Data Repository

This repository contains datasets from various projects, organized for easy access and integration. The datasets can be downloaded directly or loaded programmatically using Python.

## 📂 Repository Structure
The datasets are organized by project folders:
- **Project 1:** Regresion - Diamonds Prices
  - `project1/Diamonds_Prices2022.csv`
- **Project 2:** Clasification:


---

## 📖 How to Load the Data in Python

You can use the [pandas](https://pandas.pydata.org/) library to load the datasets directly from this repository.

### 1. Install pandas
If you don't already have pandas installed, you can install it using pip:
```bash
pip install pandas


### 2. Load a CSV File from the Repository
Here’s how you can load a file directly from the repository using its raw URL:

```python
import pandas as pd

# Example: Load the 'repairs_workshop.csv' file from Project 2
url = "https://raw.githubusercontent.com/your-username/your-repository/main/project2/repairs_workshop.csv"
data = pd.read_csv(url)

# Display the first few rows of the dataset
print(data.head())
```

### 3. Access Other Files
Replace the `url` with the raw URL of the file you want to load. For example:
- **Energy Data**: `https://raw.githubusercontent.com/your-username/your-repository/main/project1/energy_data.csv`
- **Maintenance Times**: `https://raw.githubusercontent.com/your-username/your-repository/main/project2/maintenance_times.csv`

---

## 💡 Example Use Case

```python
# Import pandas
import pandas as pd

# Load two datasets
energy_url = "https://raw.githubusercontent.com/your-username/your-repository/main/project1/energy_data.csv"
repairs_url = "https://raw.githubusercontent.com/your-username/your-repository/main/project2/repairs_workshop.csv"

energy_data = pd.read_csv(energy_url)
repairs_data = pd.read_csv(repairs_url)

# Preview the data
print("Energy Data:")
print(energy_data.head())

print("\nRepairs Data:")
print(repairs_data.head())
```

---

## 📋 Notes
- Make sure the raw URL of the file is correctly formatted. To get the raw URL, open the file in GitHub, click on the **"Raw"** button, and copy the link.
- Keep your pandas library updated for compatibility with the latest features.

---

If you encounter any issues or have questions, feel free to open an issue in this repository. 😊
