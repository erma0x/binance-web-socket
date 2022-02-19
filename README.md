# Dataflow on Binance 

## Installation
```bash
python3 -m venv venv 
source venv/bin/activate
python3 -m pip install --upgrade pip 
python3 -m pip install --upgrade python-binance
export binance_api="your api key"
export binance_secret="your api secret"
```

## How to run
```bash
source venv/bin/activate
python3 binance-dataflow.py
```
## Example 
```
--------------------------------------------------------------------------------
date:  11-02-2022 22:52:59  closing price:  42470.24000000  volume:  0.38007000
BTCUSDT:  42470.24000000 
--------------------------------------------------------------------------------
date:  11-02-2022 22:52:59  closing price:  2921.63000000  volume:  3.64650000
ETHUSDT:  2921.63000000 
--------------------------------------------------------------------------------
date:  11-02-2022 22:52:59  closing price:  42505.00000000  volume:  1.56044000
BTCUSDT:  42505.00000000
--------------------------------------------------------------------------------
date:  11-02-2022 22:52:59  closing price:  2924.08000000  volume:  14.76350000
ETHUSDT:  2924.08000000 
--------------------------------------------------------------------------------
date:  11-02-2022 22:52:59  closing price:  42521.77000000  volume:  2.46013000
BTCUSDT:  42521.77000000 
--------------------------------------------------------------------------------
date:  11-02-2022 22:52:59  closing price:  2925.29000000  volume:  25.43210000
ETHUSDT:  2925.29000000  
```

## Warning
The price is in real time, but the seconds in the _date_ field will displayed all as  _:59_ 
