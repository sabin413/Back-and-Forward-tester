# Back-and-Forward-tester
Here, I develop a trading model and deploy it.
I 'train' a trading strategy on historical Bitcoin data and find a profitable trading strategy. Then I deploy it with Amazon's AWS and Binance API. Please do not copy as the version I share here may not be profitable. 
For my trading strategy, 'class_backtester.py' performs both back and forward testing and give a set of parameters that is most likely to generate profit. Using, this I write a few other short Python scripts to generate signals and automaticaly execute 'buy' and 'sell' based on them. 
