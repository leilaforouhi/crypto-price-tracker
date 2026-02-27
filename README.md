import json

def get_crypto_price(coin="BTC"):
    # Simulated API data fetch
    mock_data = {"BTC": 65000, "ETH": 3500, "SOL": 145}
    price = mock_data.get(coin.upper(), "N/A")
    print(f"Current {coin} Price: ${price}")
    return price

if __name__ == "__main__":
    get_crypto_price("BTC")
    get_crypto_price("ETH")
    print("Market data updated successfully.")
