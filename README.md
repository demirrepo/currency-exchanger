# currency-exchanger

**Currency exchanger app that uses apilater.com API for exchanging amounts in the latest rates of currencies from all over the world. It fetches the data from the JSON response. The data includes currency codes like AUD, USD and UZS. Then, it displays them on the Spinners to show user to choose between currencies. After choosing FROM and TO options, a user enters the amount and press the CONVERT button. At this point, API will send request to obtain data based on the choices. Then, it will send the latest rate of chosen currencies. After that, the app calculates the result amount by multiplying rate and amount. That's basically how it works.**

Technologies used:

1. API: apilayer.com
2. JSON parser
3. JSON objects
4. Volley
