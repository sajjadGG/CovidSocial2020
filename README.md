# CovidSocial2020


CovidSocial2020 is a project aimed at analyzing social media responses to the Covid pandemic. It uses machine learning techniques to assess data gathered from public channels on Telegram. The repository contains various Jupyter notebooks demonstrating the different analyses performed. The notebooks are organized into different categories as follows:

## Exploratory Data Analysis (EDA)

- `Explore.ipynb`: This notebook is focused on exploring the data. It provides statistical measures and visualization techniques to gain insight from the data (e.g., frequent items, number of unique values, histograms, etc.)

- `CharacterWordManipulation.ipynb`: This notebook deals with text preprocessing tasks such as character normalization and tokenization.

- `WorldLevelAnalysis.ipynb`: This notebook tests different features for word modeling with the aim of finding appropriate features for clustering.

## Feature Extraction and Modeling

- `FeatureExtraction.ipynb`: This notebook is used to extract features from the message texts, which can be used for clustering.

- `Clustering.ipynb`: This notebook clusters the text messages based on the hypothesis that covid related messages will end up in the same cluster.

## Final

- `AllTogether.ipynb`: This notebook presents the full model pipeline, from preprocessing to clustering and visualization.

## Installation and Usage

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/CovidSocial2020.git
```

Navigate to the directory:

```bash
cd CovidSocial2020
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Now you can run each notebook in a Jupyter notebook environment.

```bash
jupyter notebook
```

Select the notebook you want to run in the opened browser.

Please note: Be sure to replace `yourusername` with your actual GitHub username in the git clone command. Also, the actual name of the repository might be different.

## Contributions

Contributions are always welcome. Please read the contribution guidelines first.

