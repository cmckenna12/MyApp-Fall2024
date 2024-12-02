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

TODO include SENDGRID instructions. Obtain API key and set key and sender address as env variables


Obtain API Key from ALPHAVANTAGE

Create a new ".env" file and add contents like the following to create your own ALPHAVANTAGEAPIKEY


```sh
# this is the ".env" file:
ALPHAVANTAGE_API_KEY="..."
```


## Usage

Run the unemployment Report:

```sh
python -m app.unemployment
```

Run the stocks report:

```sh
python -m app.stockreport
```

Run the example email send file:

```sh
python app/emailservice.py
```
### Web App
Run the web app (then view in the browser at http://localhost:5000/):

```sh
# Mac OS:
FLASK_APP=web_app flask run

# Windows OS:
# ... if `export` doesn't work for you, try `set` instead
# ... or set FLASK_APP variable via ".env" file
export FLASK_APP=web_app
flask run
```


## Testing

Run tests:

```sh
pytest
```