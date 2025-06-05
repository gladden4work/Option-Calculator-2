# Options Pricing Calculator

A professional-grade options pricing calculator that implements the Black-Scholes model for European options with support for multi-leg strategies.

## Features

- **Single-Leg Calculator**: Calculate theoretical prices and Greeks for individual options
- **Multi-Leg Strategy Builder**: Build and analyze complex multi-leg options strategies
- **Black-Scholes Model**: Implements the standard Black-Scholes pricing model
- **Comprehensive Greeks**: Calculates Delta, Gamma, Theta, Vega, and Rho
- **Responsive Design**: Works on both desktop and mobile devices

## Usage

1. Open `options-calculator.html` in a modern web browser
2. Choose between single-leg and multi-leg modes
3. Enter the required parameters:
   - Underlying price
   - Strike price
   - Days to expiry
   - Implied volatility (%)
   - Risk-free rate (%)
   - Option type (Call/Put)
4. View the calculated theoretical price and Greeks

## Note on American Options

This calculator uses the Black-Scholes model, which is designed for European options. When American style is selected, the calculator will display a warning that the results are an approximation and may not be accurate, especially for American puts.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

## License

This project is open source and available under the MIT License.
