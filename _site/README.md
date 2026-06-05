# House Prices: End-to-End Regression Case Study

This project demonstrates a complete machine learning workflow using the famous
[Kaggle House Prices dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).
The objective is to predict residential property prices from structured tabular data
while showcasing the techniques commonly used in real-world regression problems.

## About the competition 
- [Overview](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)
- [About the data](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)



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

# Step By Step instructions

After you have all requirements or environment up and running you should

### 1. Create your notebooks

However many you want. Use an old project. Just get some notebooks.

### 2. Create a "_quarto.yml" file
Addapt the structure of [this file](_quarto.yml) according to your notebooks.

### 3. Create an "index.md" file
It will be your page's index.
Addapt the structure of [this file](index.md) according to your notebooks.

### 4. install Quarto (if you haven't already done it)
```bash
pip install quarto-cli
```

### 5. Render the site locally
```bash
quarto render
```

### 6. Commit
```bash
git add .
git commit -m "some message"
git push origin
```

### 7. Publish the site
```bash
quarto publish gh-pages
```

---