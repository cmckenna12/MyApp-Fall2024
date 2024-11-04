# MyApp-Fall2024
Version Control exercise from Python Bus App Development

# my-first-app-fall-2024

## Setup

Create and activate a virtual environment (first time only)

```sh
conda create -n reports-env-2024 python=3.11
```

Activate Virtual environment (anytime you open)
```sh
conda activate reports-env-2024
```

install packages
```sh
pip install -r requirements.txt
```

Obtain API Key from ALPHAVANTAGE

Create a new ".env" file and add contents like the following to create your own ALPHAVANTAGEAPIKEY


```sh
# this is the ".env" file:
ALPHAVANTAGE_API_KEY="..."
```


## Usage

Run the unemployment Report:

```sh
python app/unemployment.py
```

Run the stocks report:

```sh
python app/stockreport.py
```