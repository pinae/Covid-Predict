# Covid-Predict
Very simple predictions for the spreading of SARS-Cov-2 in Germany.

## Virtual environment

Create a Virtualenv with:

```shell script
python3 -m venv env
```

Activate it on Windows with:

```shell script
env\Scripts\activate.bat
```

On Linux and MacOS use `source`:

```bash
source env/bin/activate
``` 

## Dependencies

It is always a good idea to update `pip` and `wheel`:

```shell script
pip install -U pip wheel
```

Install the dependencies using `requirements.txt`:

```shell script
pip install -r requirements.txt
```

## Running

Start Jupyter with:

```shell script
jupyter notebook
```

Open the Notebook “COVID-19-Predictions” and execute the cells.