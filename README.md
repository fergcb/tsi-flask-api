# Flask Demo

## Installation
```shell
git clone https://github.com/fergcb/tsi-flask-api.git
cd tsi-flask-api
python -m pip install -r requirements.txt
```

## Running the API
To start the server, run **ONE** of the following commands:
```shell
flask run
python -m flask run
python app.py
```

By default the application will run in production mode. To use development or testing configurations, set the `ENV` environment to `DEV` or `TEST` respectively. This can be done through the command line, or in your PyCharm Run/Debug Configurations menu.