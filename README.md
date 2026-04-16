# Currency Converter

A simple web-based currency converter application built with HTML, CSS, and JavaScript.

## Features

- Convert between multiple currencies: USD, EUR, GBP, JPY, INR
- Real-time exchange rates fetched from the ExchangeRate API
- Clean and responsive user interface
- Input validation for amounts

## Demo Screenshot

![Currency Converter Screenshot](Screenshot%202024-07-08%20202852.png)

## Technologies Used

- **HTML5**: Structure of the web page
- **CSS3**: Styling and layout
- **JavaScript (ES6)**: Logic for fetching exchange rates and performing conversions
- **ExchangeRate API**: Provides real-time currency exchange rates

## How to Use

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Enter the amount you want to convert in the input field.
4. Select the source currency from the first dropdown.
5. Select the target currency from the second dropdown.
6. Click the "Convert" button to see the result.

## API Key

This application uses a free API key from [exchangerate-api.com](https://exchangerate-api.com). The key is hardcoded in `script.js` for demonstration purposes. For production use or to avoid rate limits, obtain your own API key and update the `apiKey` variable.

Note: The free tier has limitations; consider upgrading for higher usage.

## Adding More Currencies

To add more currencies, update the `currencies` array in `script.js` with additional currency codes (e.g., 'CAD', 'AUD').

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the application.

## License

This project is open-source. Please check for any applicable licenses.