# House Prices: End-to-End Regression Case Study

An end-to-end machine learning project based on the **Kaggle House Prices: Advanced Regression Techniques** competition.

The project demonstrates a complete supervised regression workflow using structured tabular data, covering:

- Exploratory data analysis (EDA)
- Data cleaning
- Feature engineering
- Log transformation of skewed variables
- Baseline models
- Linear Regression
- Random Forest
- Gradient Boosting
- Cross-validation and model comparison
- Model interpretation
- Kaggle submission generation

---

## Documentation

The complete project documentation is available as a Quarto website:

**[https://ianlopezdiaz.github.io/kaggle-house-prices](https://ianlopezdiaz.github.io/kaggle-house-prices)**

The website contains:

- Project overview
- Interactive notebooks
- Methodology
- Results and discussion

---

## Dataset

This project uses the **House Prices: Advanced Regression Techniques** dataset from Kaggle.

Competition page:

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

For convenience and reproducibility, the original competition files are included in this repository under:

```text
data/raw/
```

The processed datasets generated throughout the workflow are stored in:

```text
data/processed/
```

---

## Repository Structure

```text
kaggle-house-prices/
│
├── README.md
├── index.qmd
├── _quarto.yml
├── environment.yml
├── LICENSE
|
├── notebooks/
|   |
|   ├── 01_exploratory_data_analysis.ipynb
|   ├── 02_feature_engineering.ipynb
|   └── 03_modeling_and_evaluation.ipynb
|
├── data/
|   |
|   ├── raw/
|   |   ├── data_description.txt
|   |   ├── sample_submission.csv
|   |   ├── test.csv
|   |   └── train.csv
|   |
|   └── processed/
|       ├── 01_data.parquet
|       ├── 01_features.parquet
|       ├── 02_data.parquet
|       ├── 02_features.parquet
|       └── submission.csv
|
└── _site/
```

---

## Running the Project

### Create the environment

```bash
conda env create -f environment.yml
conda activate kaggle-house-prices
```

or

```bash
pip install -r requirements.txt
```

### Render the website

```bash
quarto preview
```

or

```bash
quarto render
```

---

## License

This project is released under the MIT License.