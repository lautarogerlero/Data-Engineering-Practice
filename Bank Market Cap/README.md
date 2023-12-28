# Bank Market Cap ETL

## Scripts

1. **bank_market_cap_webscraping.ipynb**
	. Extracts information about the largest banks in the world from Wikipedia and creates a JSON file with the name and market cap for each bank.

2. **exchange_rates.ipynb**
	. Retrieves exchange rates from ExchangeRate-API and stores the currency and corresponding rate in a CSV file.

3. **final_code.ipynb**
	. Utilizing the two files generated in the preceding processes, calculates the market cap in EUR for each bank and saves the results in a new CSV file.
