# Flask Demo

## Installation
```shell
# Get the code
git clone https://github.com/fergcb/tsi-flask-api.git
cd tsi-flask-api
# Create and activate a virtual environment:
python -m venv venv
./venv/Scripts/activate
# Install dependencies:
pip install -r requirements.txt
# To leave the virtual environment:
deactivate
```

## Running the API
If you're not already in the virtual environment, run `./venv/Scripts/activate`.
Run `deactivate` to leave the virtual environment when you're done.

To start the server, run **ONE** of the following commands:

```shell
flask run
python -m flask run
python app.py
```

### Note:
By default the application will run in production mode. To use development or testing configurations, set the `ENV` environment to `DEV` or `TEST` respectively. This can be done through the command line, or in your PyCharm Run/Debug Configurations menu.