## Wine Quality Modelling – Classification, Clustering & Linear Analysis with Python

This project involves data preparation, modelling, and analysis of a wine quality dataset. It applies various supervised and unsupervised machine learning techniques to explore, classify, and cluster wine quality based on physicochemical properties.

###  Project Files

- `Code.ipynb` – Jupyter notebook with all data preparation, modelling, and visualisations.
- `A2RandomSample.csv` – Random 600-instance sample from the original dataset (cleaned, no missing values).
- `A2data.csv` – Original full dataset (used only for sampling).

###  Project Tasks

#### Task 1: Data Preparation & Analysis
- Loaded and sampled 600 clean instances from the original dataset.
- Visualised relationships between variables (e.g., alcohol vs. density).
- Built and interpreted a simple linear regression model.
- Created grouped boxplots and provided observations.

#### Task 2: Classification
- Implemented wine quality classification using either **k-NN** or **Decision Tree**.
- Evaluated the model using accuracy, precision, and recall.
- Tuned key parameters (e.g., number of neighbors or tree depth).
- Tested model performance across multiple train/test splits (from 20:80 to 80:20).

#### Task 3: Clustering
- Performed clustering using either **k-means** or **DBSCAN** (without using the quality label).
- Tuned cluster parameters and identified optimal cluster counts.
- Compared predicted clusters with actual quality levels using a confusion matrix.

#### Task 4: Report
- Comprehensive written report covering all tasks with analysis, justifications, and findings.

### Key Libraries Used

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualisation
- `scikit-learn` – Modelling and evaluation (regression, classification, clustering)

### How to Run

1. Open the Jupyter Notebook (`Code.ipynb`) in JupyterLab or VSCode.
2. Run all cells (Kernel > Restart & Run All).
3. Visualisations and model outputs will be generated inline.

###  Dataset Source

The dataset contains 4781 rows and 12 attributes related to physicochemical tests and wine quality ratings (0 to 10). Description of each attribute is available in `Readme-A2data.txt`.

---
