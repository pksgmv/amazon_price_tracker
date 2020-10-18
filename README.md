# Amazon Price Tracker

## Steps Involved
    - Get Link to Website with Items
    - Get Items Links
    - Extract Info about Items
    - Generate Report Based on Info

## Initial Setup Instructions

Make sure to download correct chromedriver - https://chromedriver.chromium.org/downloads

### Setup Python Virtual Environment
```buildoutcfg
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```
## Running Script

```buildoutcfg
python tracker.py
```

## The iphone.json file is generated by running the Python script tracker.py, giving the input search term as 'iphone', minimum price filter as '30,000' and maximum price filter as '50,000'