# Monte-Carlo-Method 🐍 
Monte Carlo stimulation algorithm for stocks and financial instruments with Python, Numpy and Matplotlib.

# Contributions
Monte-Carlo-Method is open to contributions, but I recommend creating an issue or replying in a comment to let me know what you are working on first that way we don't overwrite each other.

# Detailed documentation of code in the case it is unclear 
- the parameters of the function get_simulation being "ticker" and "name" can be manipulated for your desired ticker and name of the stock
- Pandas DataFrame is two-dimensional size-mutable, potentially heterogeneous tabular data structure with labeled axes (rows and columns). 
- Pandas datareader is a sub package that allows one to create a dataframe from various internet datasources
- Adjusted close is the closing price after adjustments for all applicable splits and dividend distributions.
- Pandas dataframe.pct_change() function calculates the percentage change between the current and a prior element. This function by default calculates the percentage change from the immediately previous row.
- want to add to this 


# Some maths behind the program

ST = S0e^((Rf-d-(σ^2)/2)T+σ*sqrt(TZ)) 

The definitions for each of the variables in this formula are:

- ST: Simulated future stock price.
- S0: Beginning stock price (e.g., as of the grant date).
- e: The mathematical constant e (~2.72, i.e., the base of the natural logarithm).
- Rf: The risk-free interest rate based on zero-coupon U.S. Treasuries (the “drift”).
- d: The dividend yield (if applicable).
- σ: Annual volatility.
- T: The term of the award, from the grant date to the end of the applicable period.
- Z: Normally distributed random variable (Z-score); for simplicity, one can think of “Z” as a random number that changes for each simulation.
