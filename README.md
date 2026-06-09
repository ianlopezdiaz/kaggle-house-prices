# House Prices: End-to-End Regression Case Study

This project demonstrates a complete machine learning workflow using the famous
[Kaggle House Prices dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).
The objective is to predict residential property prices from structured tabular data
while showcasing the techniques commonly used in real-world regression problems.

## About the competition 
- [Overview](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)
- [About the data](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

Check the site [here](https://ianlopezdiaz.github.io/kaggle-house-prices).

---

# Getting started to do this locally

### Install requirements:

```bash
pip install -r requirements.txt
```

or, if you prefer

### Clone my environment:

```bash
conda env create -f environment.yml
```

You can change `name` to anything you like in the `environment.yml` file
if you already have an Anaconda/Miniconda environment with this name or
you simply want to use a different name for whatever reason.

---

# Build the site with Quarto

### 1. Install [Quarto](https://quarto.org/) (if you haven't already done it)
```bash
pip install quarto-cli
```

After you have all requirements or environment up and running
and can modify the project anyway you feel like and 
to preview the site just do

```bash
quarto preview
```

After you are finished just

### 2. Render the site locally
```bash
quarto render
```

### 3. Commit/Push
```bash
git add .
git commit -m "some message"
git push origin
```

### 4. Publish the site
```bash
quarto publish gh-pages
```

---