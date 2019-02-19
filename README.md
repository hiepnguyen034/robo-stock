solution for project 3

# Instruction

1. clone this repo and download dependencies
```
git clone https://github.com/hiepnguyen034/robo-stock

cd robo-stock

pip install -r requirements.txt
```

2. Request an API key from https://www.alphavantage.co/

```
touch .env
```
Open .env file and insert ```ALPHAVANTAGE_API_KEY='YOUR API KEY GOES HERE'``` 

3. Run the file

```
python robo_advisor.py
```

4. Insert name of stock price and data will be saved to data folder