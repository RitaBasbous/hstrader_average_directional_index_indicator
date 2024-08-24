#  Average Directional Index (ADX) with python

![adx](img/average_directional_index.png)

This Python script visualizes the  Average Directional Index (ADX) indicator using both real-time and historical market data.The ADX is a popular technical analysis tool used to quantify the strength of a trend in the market.

## Prerequisites

Ensure you have the requirements file installed.

To install the libraries listed in the `requirements.txt` file, use the following command:

```sh
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in your project directory and add your `CLIENT_ID` and `CLIENT_SECRET`:

```env
CLIENT_ID=your_client_id
CLIENT_SECRET=your_client_secret
```

These variables enable secure access to market data from the [HSTRADER](https://staging.hstrader.com/login) platform.

**Note:**
Your unique `CLIENT_ID` and `CLIENT_SECRET` can be obtained from your personal account on the platform. Ensure you keep them confidential to protect your data.

### Average Directional Index (ADX) Overview

The Average Directional Index (ADX) is used to determine the strength of a trend, whether it's an upward or downward trend. It is a non-directional indicator, meaning it quantifies trend strength regardless of trend direction.

### Components of ADX 

1. **ADX Line:**
   - Measures the strength of the trend.
   - Values above 25 indicate a strong trend, while values below 20 suggest a weak trend or a range-bound market.

2. **+DI (Positive Directional Indicator):**
   - Measures the strength of the upward movement.
   - When +DI is above -DI, the market is in an uptrend.

3. **-DI (Negative Directional Indicator):**
   - Measures the strength of the downward movement.
   - When -DI is above +DI, the market is in a downtrend.

### Interpreting the ADX Chart

- **ADX Line:** A rising ADX line indicates a strengthening trend, while a falling ADX suggests weakening momentum.
- **+DI vs. -DI:** The relationship between +DI and -DI can indicate whether the trend is upward or downward. When +DI crosses above -DI, it signals a potential buy, and when -DI crosses above +DI, it signals a potential sell.
 