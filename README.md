# About
The official Python library for the TakinAI API: https://pypi.org/project/takinai/0.0.1/

## Installation

```
pip install takinai
```

## Test

```bash
pip install pytest
python -m pytest
```

## Packaging and Upload

Find classifier from https://pypi.org/classifiers/ for `setup.py`
```
python setup.py sdist
twine upload dist/*
```
