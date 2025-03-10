# 💰Crypto Dashboard 

A web application built with FastAPI to fetch and visualize cryptocurrency data for Bitcoin, Ethereum, or other cryptocurrencies using CoinGecko's API. The app displays interactive price charts using Plotly.

## 🪨Features 

- Fetch cryptocurrency data (Bitcoin, Ethereum, etc.) from the CoinGecko API.
- Display price history as interactive line charts using Plotly.
- Simple FastAPI endpoints to request price data and display graphs.

## 💻Installation 

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/crypto-dashboard.git
cd crypto-dashboard
```

### 2. Set up a virtual environment:

```bash
python -m venv venv
```

### 3. Activate the virtual environment:

- **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **Mac/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 4. Install the necessary dependencies:

```bash
pip install -r requirements.txt
```

## 💻Usage 

### 1. Start the FastAPI server:

```bash
uvicorn main:app --reload
```

### 2. Access the web application:

- Open your browser and navigate to: `http://127.0.0.1:8000`
- Use the FastAPI Swagger UI at: `http://127.0.0.1:8000/docs` to test the endpoints.

### 3. Endpoint examples you can try:

- **Get Bitcoin Prices:** `/crypto-prices?coin=bitcoin&days=365`
- **Get Ethereum Prices:** `/crypto-prices?coin=ethereum&days=365`

## ⌨️Development 

### 1. Create a new route:

- Modify the `routes.py` file to add new routes for fetching other cryptocurrencies.

### 2. Add new features:

- Feel free to explore adding additional chart types, advanced features, or more cryptocurrency options.

## 🪪License 

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
