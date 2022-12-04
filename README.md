# Boston House Pricing Prediction using Linear Regression

## Requiried Software and Tools
1. [VS Code](https://code.visualstudio.com/)
2. [Python 3.7](https://www.python.org/downloads/)
3. [Anaconda](https://www.anaconda.com/distribution/)
4. [Git](https://git-scm.com/downloads)
5. [GitHub](https://www.github.com)
6. [Heroku Cloud Account](https://www.heroku.com/)


## Create a new environment
Method 1: Using Python
```
python -m venv venv
```

Method 2: Using Anaconda
```
conda create -p venv python=3.7 -y
```

## Activate the environment
Method 1: Using Python
```
venv\Scripts\activate
```

Method 2: Using Anaconda
```
conda activate venv/
```

## Deactivate the environment

Method 1: Using Python
```
deactivate
```

Method 2: Using Anaconda
```
conda deactivate
```


## requirements.txt
```python
Flask
sklearn
pandas
numpy
matplotlib
```

## Install the required packages
```python
pip install -r requirements.txt
```


## run app.py
```python
python app.py
```

## Test by passing data in json format
```python
{
    "data":{
            "CRIM": 0.00632,
            "ZN": 18.0,
            "INDUS": 2.31,
            "CHAS": 0.0,
            "NOX": 0.538,
            "RM": 6.575,
            "AGE": 65.2,
            "DIS": 4.09,
            "RAD": 1.0,
            "TAX": 296.0,
            "PTRATIO": 15.3,
            "B": 396.9,
            "LSTAT": 4.98
        }
}
```