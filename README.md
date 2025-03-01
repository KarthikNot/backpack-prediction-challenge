# <center><i>Kaggle Challenge</i></center>

# <center> BackPack Prediction Challenge [[link]](https://www.kaggle.com/competitions/playground-series-s5e2) <center>

## <center>Playground Series - Season 5, Episode 2 <center>center>

## Challenge Objective 🎯

The goal of the Tabular Playground Series is to provide the Kaggle community with a variety of light-weight challenges that can be used to learn and sharpen skills in different aspects of machine learning and data science. Each competition typically lasts a few weeks, with durations varying depending on the challenge. These challenges utilize light-weight datasets that are synthetically generated from real-world data, offering an opportunity to quickly iterate through various model and feature engineering ideas, as well as create visualizations. 📊

---

## About the Dataset 📊

This dataset contains 50,000 records of student bags, featuring various attributes relevant for predicting the price of a bag. It is intentionally designed with duplicates, missing values, and noise to simulate a realistic scenario for data cleaning, preprocessing, and exploratory data analysis (EDA) tasks. 🧹

- Download the dataset from here: [Kaggle Dataset](https://www.kaggle.com/competitions/playground-series-s5e2/data) 📥

## Dataset Features 📝

- **`Brand`**: The brand of the bag (e.g., Nike, Adidas, Jansport)
- **`Material`**: The primary material used (e.g., Leather, Polyester, Nylon, Canvas)
- **`Size`**: The size of the bag (Small, Medium, Large)
- **`Compartments`**: The number of compartments in the bag (1 to 10)
- **`Laptop Compartment`**: Whether the bag has a laptop compartment (Yes/No)
- **`Waterproof`**: Whether the bag is waterproof (Yes/No)
- **`Style`**: The style of the bag (Backpack, Messenger, Tote)
- **`Color`**: The color of the bag (e.g., Black, Blue, Red, Green, Gray, Pink)
- **`Weight Capacity`**: The maximum weight the bag can hold
- **`Price`**: The price of the bag in USD 💵

<br>

## How to Set Up This Project 🛠️

This guide walks you through setting up the project's environment.

**1. Install Python 🐍**

If you don't have Python installed yet, head over to the official download page: [Python Download Guide](https://wiki.python.org/moin/BeginnersGuide/Download) and follow the instructions for your operating system (Windows, macOS, or Linux).

**<u>Optional: Creating a Virtual Environment 🌱</u>**

1. Create a virtual environment:

   In the terminal, run the following command:

   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment:

   To activate the virtual environment, use:

   ```bash
   venv\Scripts\activate
   ```

**2. Download the Repo 📥**

1. Open your Git client or terminal.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command, replacing `<repository_url>` with the actual URL of the project's repository:

   ```bash
   git clone <repository_url>
   ```

**3. Install Required Dependencies 📦**

1. Open terminal/cmd.
2. Navigate to the repository directory.
3. Run the following command to install dependencies from `requirements.txt`:

   ```bash
   pip install -r ./backpack-prediction/requirements.txt
   ```
