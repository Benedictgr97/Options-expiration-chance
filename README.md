# Options-expiration-chance
Code is split into 3 functions and the stock data is from alpha vantage using an api key (these can be freely obtained by signing up on the alpha vantage website).
Each model uses a simple monte carlo simulation to find the range of prices in the future. Each function can have 
1. Used to find the average return of a bull credit spread. The cost of buying and selling the put options are not taken into account but can easily be found.
2. Works out the expiration chance for a american option.
3. Works out the expiration chance for a europeon option.
