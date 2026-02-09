# Bank of England Exchange Rate Data

## Data Source

Exchange rates are sourced from the Bank of England's daily spot rates database. Rates represent the value of foreign currencies against Sterling (GBP), US Dollars (USD), and Euros (EUR).

## Data Files

| File                             | Description                                                    |
|----------------------------------|----------------------------------------------------------------|
| boe_exchange_rates.csv           | Contains only the most recent trading day's exchange rates     |
| boe_exchange_rates_full_hist.csv | Contains the complete historical record of all exchange rates since 2026-01-01  |

Both files share the same schema. The latest rates file is overwritten on each run, while the full history file is appended to with new data.

## Currency Reference

| Currency Name      | ISO Code |
|--------------------|----------|
| Australian Dollar  | AUD      |
| Brazilian Real     | BRL      |
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
