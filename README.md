# kaggle-isic-2024-challenge
[https://www.kaggle.com/competitions/isic-2024-challenge](https://www.kaggle.com/competitions/isic-2024-challenge)

## Directory
1. [Virtual Environment](#virtual-environment)
2. [Get Data](#get-data)

## Virtual Environment

Create virtual environment:
```bash
python -m venv isic-2024-challenge
```

Activate virtual environment:
```bash
source isic-2024-challenge/bin/activate
```

Update Pip:
```bash
pip install --upgrade pip
```

Install necessary packages and add to requirements.txt once done:
```bash
pip freeze > requirements.txt
```

## Get Data

Go to your Kaggle account and create a new taken. This will download `kaggle.json` which needs to be placed in `~/.kaggle/kaggle.json` in order to use the API.

Grant access once the `kaggle.json` has been added:
```bash
chmod 600 ~/.kaggle/kaggle.json
```

Download data:
```bash
kaggle competitions download -c isic-2024-challenge
```

Unzip data:
```bash
unzip isic-2024-challenge.zip
```

Delete zipped folder:
```bash
rm isic-2024-challenge.zip
```