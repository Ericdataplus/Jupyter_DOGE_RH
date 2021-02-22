[Reference for commands](https://robin-stocks.readthedocs.io/en/latest/quickstart.html)

This is for me to quickly reference to for when I want to tackle doing this.

```python
# I'm using anacondas prompt copy, paste this there...... pip install robin_stocks 
```


```python
import robin_stocks
```


```python
import robin_stocks as r
>>> login = r.login(<username>,<password>)
```


```python
#Sell half a Bitcoin is price reaches 10,000
>>> robin_stocks.order_sell_crypto_limit('BTC',0.5,10000)
```


```python

```
