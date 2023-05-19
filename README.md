# Currency Converter

A simple currency converter application that utilizes the API Layer Exchange Rate DATA API made as a fun personal project.

Built with Python and Tkinter.

## How the Code Works

The code uses the API Layer API to perform currency conversions. It retrieves exchange rate data from the API based on the selected start and end currencies, and the specified amount. The code then displays the converted amount to the user.

## API (API Layer Exchange Rate DATA API)

The API Layer Exchange Rate DATA API provides real-time and historical exchange rate data. It offers various endpoints and parameters to retrieve currency exchange rates.

To use this application, you need to create an account with API Layer and obtain an API key. The API key is used to authenticate your requests to the API Layer API.

For more information on the API Layer Exchange Rate DATA API, visit their [website](https://apilayer.com/).

## Installation

1. Clone the repository:

```git clone https://github.com/ElRapt/currency-converter.git```

2. Change into the project directory:

```cd currency-converter```

3. Install the required dependencies:

```pip install -r requirements.txt```

## Usage

1. Create an account with API Layer at [https://apilayer.com/](https://apilayer.com/) if you haven't already.

2. Obtain an API key from API Layer.

3. Replace `"YOUR_API_KEY_HERE"` with your actual API key (line 203).

4. Run the application:

```python currencyconverter.py```

5. Select the start currency, end currency, and enter the amount to convert.

6. Click the "Convert" button to perform the conversion.

7. The converted amount will be displayed on the screen.

## License

This project is licensed under the [MIT License](LICENSE).
