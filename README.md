
# This is a simple trading algorithm that buy low sell high

# Algorithm:
# 1.    Use 27 stocks context, most in technology and healthcare sector 
# 2.    For each stock in these stocks
# 3.    Buy in long only when current price lower than 45 day price average, and when I have over  $2000 cash left, and when I currently do not hold any position for that one particular stock

# 4.    buy in # of shares = $2000 / current stock price
# 5.    Hold until stock price has come up
# 6.    Sell once stock price is higher and total earning is larger than $100
