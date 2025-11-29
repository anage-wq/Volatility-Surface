# Implied Volatility Surface for SPY Options

A Python application that visualizes the implied volatility surface for SPY options. Using real-time SPY option data from Yahoo Finance, the app calculates implied volatility based on the Black-Scholes model and plots a 3D surface to show how implied volatility varies with time to expiration and strike price. The user-friendly Streamlit interface allows for easy adjustments to model parameters.



## Features
- **Interactive 3D Volatility Surface**: View implied volatility changes over varying strike prices and time to expiration.
- **Real-Time Option Data**: The app fetches current SPY options data from Yahoo Finance.
- **Adjustable Risk-Free Rate**: Customize the Black-Scholes model with a user-defined risk-free rate.
- **User-Settable Ticker Symbol**: Input any ticker symbol to visualize its implied volatility surface.
- **Custom Strike Price Filters**: Set minimum and maximum strike price percentages relative to the spot price for tailored analysis.
- **User-Friendly Design**: Built with Streamlit for an accessible and responsive interface.

## Libraries Used
- **Streamlit**: Frontend interface for web-based interaction.
- **yfinance**: Real-time financial data fetching.
- **NumPy**: Numerical computations and array handling.
- **Pandas**: Data management and manipulation.
- **SciPy**: Root-finding and normal distribution functions for calculating implied volatility.
- **Plotly**: 3D plotting and visualization of the implied volatility surface.

## Application View
<img width="2662" height="1600" alt="image" src="https://github.com/user-attachments/assets/e3169db8-d08f-43e8-be86-fc9c8326fb5c" />
<img width="2852" height="1588" alt="image" src="https://github.com/user-attachments/assets/1ab5cddd-562e-4a77-bee3-a48da1dd419e" />

##  Accessing Application
1. Clone the repository in a folder
2. Open folder on vs code
3. Create virtual environment : python -m venv venv
4. Install Requirements : pip install -r requirements.txt
5. Run the Application : streamlit run app.py


   












