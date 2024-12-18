These files include a wiener process and stachastic model implementation in Python.

Just regarding the theory, we know that the daily returns follow normal distribution where majority of the data is centred around the mean, however the same cannot be said for stock prices themselves.

Hence we use wiener process to simulate the randomness of stock fluctuations where the mean is 0 and variance is dt. This model predicts that the increment change is normally distributed, the starting value is 0 and past val;ues don't effect future stock prices.
The conclusion of the wiener process is that the smaller the stock price, smaller the fluctuations whereas bigger the stock price, bigger the fluctuations.


When dealing with ito's lemma function, we need to normally deal with ito's higher dimensions rather than the lemma as there are two variables (stock price and time) when dealing with the problem. After deriving, we can come to the conclusion that the change in the option value is dependent on time, price of the stock and an additional term which has something to do with time as well. 


