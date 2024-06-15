# BitPredict 🚀📈

Welcome to **BitPredict**, my personal project focused on predicting cryptocurrency prices using machine learning and data from the CoinGecko API. This repository contains the code and resources needed to fetch crypto market data and train a machine learning model to make informed predictions about future prices.

## Table of Contents 📑

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction 🌟

In this project, I explore cryptocurrency price prediction using the CoinGecko API and machine learning – the ability to learn patterns from data and make informed predictions. By leveraging the CoinGecko API, I fetch historical and current crypto market data, which serves as the foundation for the machine learning model. Trained on this data, the model predicts future cryptocurrency prices, providing valuable insights for investment strategies and market trend analysis.

## Features ✨

- 🗂️ Fetch historical and current cryptocurrency market data from the CoinGecko API.
- 🤖 Train a machine learning model on the fetched data.
- 📊 Predict future cryptocurrency prices based on the trained model.
- 💡 Provide insights for investment strategies and market trend analysis.

## Installation 🛠️

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/BitPredict.git
    ```
2. Replace the placeholder API key: The script contains a placeholder "YOUR_API_KEY" for the CoinGecko API key. Replace this with your actual CoinGecko Demo API key. If you don't have one, you can get it by registering on the [CoinGecko Demo API](https://www.coingecko.com/en/api?utm_campaign=learn&utm_content=bitcoin-price-prediction-machine-learning) page.
2. Navigate to the project directory:
    ```bash
    cd BitPredict
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Setup a new environmet:
    ```bash
    python -m venv myenv
    ```
5. Activate the env:
    ```bash
    myenv\Scripts\activate.bat
    ```
6. Run the model:
    ```bash
    python model.py
    ```
7. Open the web app: In your web browser, go to http://localhost:5000

## Usage 📚

1. Fetch the cryptocurrency market data from CoinGecko API:
    ```bash
    model fetch_data.py
    ```
2. Train the machine learning model on the fetched data:
    ```bash
    model train_model.py
    ```
3. Predict future cryptocurrency prices:
    ```bash
    model predict.py
    ```

## Disclaimer ⚠️

While this covers machine learning techniques for crypto price prediction, any use or reliance on my content is solely at your own risk and discretion. Do conduct your own research, review, analyze, and verify my content before relying on them. Trading is a highly risky activity that can lead to major losses, please therefore consult your financial advisor before making any decisions.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements 🌈

- 🙏 [CoinGecko](https://www.coingecko.com/) for providing the cryptocurrency market data API.
- 🤗 [scikit-learn](https://scikit-learn.org/) for the machine learning library.
- 🐼 [pandas](https://pandas.pydata.org/) for data manipulation and analysis.
