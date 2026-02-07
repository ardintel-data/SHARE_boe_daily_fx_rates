# Bank of England Exchange Rate Data

## Data Source

Exchange rates are sourced from the Bank of England's daily spot rates database. Rates represent the value of foreign currencies against Sterling (GBP), US Dollars (USD), and Euros (EUR).

## Currency Reference

| Currency Name      | ISO Code |
|--------------------|----------|
| Australian Dollar  | AUD      |
| Canadian Dollar    | CAD      |
| Chinese Yuan       | CNY      |
| Czech Koruna       | CZK      |
| Danish Krone       | DKK      |
| Euro               | EUR      |
| Hong Kong Dollar   | HKD      |
| Hungarian Forint   | HUF      |
| Indian Rupee       | INR      |
| Israeli Shekel     | ILS      |
| Japanese Yen       | JPY      |
| Malaysian Ringgit  | MYR      |
| New Zealand Dollar | NZD      |
| Norwegian Krone    | NOK      |
| Polish Zloty       | PLN      |
| Romanian Leu       | RON      |
| Saudi Riyal        | SAR      |
| Singapore Dollar   | SGD      |
| South African Rand | ZAR      |
| South Korean Won   | KRW      |
| Swedish Krona      | SEK      |
| Swiss Franc        | CHF      |
| Taiwan Dollar      | TWD      |
| Thai Baht          | THB      |
| Turkish Lira       | TRY      |
| US Dollar          | USD      |

## Data Schema

| Column              | Description                            |
|---------------------|----------------------------------------|
| Rate date           | Date of the exchange rate (YYYY-MM-DD) |
| Base Currency       | Base currency for conversion (GBP)     |
| Conversion Currency | Target currency ISO code               |
| Exchange Rate       | Units of foreign currency per 1 GBP    |
| Calculation Type    | Rate derivation method                 |
