# HeartDisease

Predicting heart diseases by using advanced automated EDA, Feature Engineering and selecting the optimal model from a set of 20, with visualizations.

Environment:

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands:

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

activate

```
source .venv/bin/activate
```

Freezing pip installs:

```
pip freeze > requirements.txt
```

Cleaning cache:

```
find . -name "*.pyc" -exec rm -f {} \;
find . -type d -name __pycache__ -exec rm -r {} +

```
