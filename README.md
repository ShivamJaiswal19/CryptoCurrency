# 📈 CryptoCurrency Price Prediction Using Twitter Sentiment Analysis 🐦

Welcome to the **CryptoCurrency Price Prediction** project! This project leverages **Twitter sentiment analysis** using **Llama 3** and **LSTM** (Long Short-Term Memory) neural networks to predict the price movements of Bitcoin based on social media sentiment.

---

## 📋 Project Overview

In the world of cryptocurrency, social media can have a major influence on price movements. This project aims to:
- 🐦 **Collect tweets** about Bitcoin, analyze their sentiment, and use that information to make predictions about Bitcoin price trends.
- 💬 Use **Llama 3**, a pre-trained model for sentiment analysis, to determine if tweets are positive, negative, or neutral.
- 📈 Train an **LSTM model** on historical Bitcoin prices and sentiment data to predict future price changes.

### Key Features
- **Twitter Sentiment Analysis** using Llama 3 to classify tweet sentiment.
- **LSTM Model** for time-series forecasting, predicting cryptocurrency price movements.
- **Integrated Workflow** with modular notebooks, making it easy to understand and adapt each step of the project.

---

## 📂 Project Structure

This project is organized into the following notebooks:

1. **Data Collection and Preprocessing**: Collects historical Bitcoin prices and uses a placeholder for tweet data. The notebook sets up data for sentiment analysis.
2. **Sentiment Analysis**: Loads the Llama 3 model to classify the sentiment of tweets as positive, negative, or neutral.
3. **Feature Engineering**: Combines sentiment scores with Bitcoin price data, creating features for model training.
4. **LSTM Model Training**: Builds and trains the LSTM model on the combined dataset.
5. **Evaluation and Results**: Evaluates the model’s performance and visualizes the predicted vs. actual price movements.

---

## 🚀 Getting Started

### Prerequisites
To get started, you’ll need:
- Python 3.7+
- Jupyter Notebook
- Git
- Libraries listed in `requirements.txt`

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ShivamJaiswal19/CryptoCurrency.git
   cd CryptoCurrency
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

### Usage

1. Start with the **Data Collection and Preprocessing** notebook to load Bitcoin price data and prepare tweet data.
2. Move to **Sentiment Analysis** to apply Llama 3 for sentiment classification.
3. Continue with **Feature Engineering** to merge sentiment with price data and generate features.
4. Use the **LSTM Model Training** notebook to train the LSTM model on the processed data.
5. Finally, evaluate the model in the **Evaluation and Results** notebook and visualize the predictions.

---

## 📊 Results

The LSTM model was evaluated based on its ability to predict the trend of Bitcoin prices. The model uses both historical price data and Twitter sentiment, which provides insights into public sentiment as a driving factor in price movements. Below is an example plot showing the **predicted** vs. **actual** price movement:

![Prediction Results](https://via.placeholder.com/800x400?text=Prediction+vs+Actual+Plot)

---

## 🛠️ Technologies Used

- **Python** 🐍: Programming language used for data processing, model training, and analysis.
- **Jupyter Notebook** 📓: Used for the development and documentation of the project.
- **Llama 3** 🦙: Pre-trained model for Twitter sentiment analysis.
- **TensorFlow / Keras** 🤖: Deep learning framework for building and training the LSTM model.
- **Pandas** 🐼 and **NumPy** 🔢: Libraries for data manipulation and numerical computations.
- **Matplotlib** 📊: Library for plotting and visualizing the results.

---

## 📚 Acknowledgements

Special thanks to the open-source community for providing amazing tools and resources, including:
- [Hugging Face](https://huggingface.co/) for the Llama 3 model.
- [Yahoo Finance API](https://pypi.org/project/yfinance/) for historical price data.

---

## 📌 Future Work

Future improvements could include:
- 🧠 **Integrating more sophisticated sentiment models**.
- 📉 **Expanding the dataset** to include other cryptocurrencies.
- 📈 **Implementing additional forecasting algorithms** to compare and contrast with LSTM.

---

## 📬 Contact

If you have any questions, feel free to reach out via GitHub issues or fork the repository and contribute! 

---

### Enjoy exploring crypto trends and happy forecasting! 🚀💰📉

--- 

