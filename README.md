new-coder-API-tutorial
======================
My walked-through version of the API tutorial project which can be found at:
http://newcoder.io/api/
The complete original version of this code can be found at: 
https://github.com/econchick/new-coder/blob/master/apis/platform_pricing.py

As described in the original version: 
"""
This is a very example demonstrating how to combine multiple data sources (raw
data and Web API). Here we generate a bar chart containing video game consoles
of multiple generations and their respective prices.

As data source for the available video game platforms we use the API provided
by Giantbomb.com. But since prices there are only stored in the amount of money
you had to put on the table back when the console was released, we also want
to put those prices into perspective with the current value of the US Dollar.
For this we use the CPI made available by the Federal Reserve Bank of St.
Louis.

http://www.giantbomb.com/api/
http://research.stlouisfed.org/fred2/

Please note that the inflation-calculation here is not really accurate but
it's also not really the point of this tutorial to show you how to calculate
currency inflation but to show you how to combine multiple data sources
including APIs ;-)

To be able to use this script, you have to register for a Giantbomb API key
and pass it to this script using the --giantbomb-api-key argument.

Written by Horst Gutmann (https://github.com/zerok)
"""
