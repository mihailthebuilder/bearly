[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mihailthebuilder/bearly/main?urlpath=%2Fvoila%2Frender%2Fbearly.ipynb)

# Bearly

## What is it?

Recognises the bear in an image is a grizzly, black, or teddy bear.

## How to run on Linux?

Create local environment & activate

```bash
python3 -m venv venv
source venv/bin/activate
```

Install Python packages

```bash
pip install -r requirements.txt
```

Add the Voila extension to the Jupyter notebook

```bash
jupyter serverextension enable --sys-prefix voila
```

Run Voila

```bash
voila
```
