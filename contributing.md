# Contributing

## Local setup

```
# Create virtual env
virtualenv venv
# Activate virtual env
source venv/bin/activate
python setup.py install
# Install in "editable" mode
pip install -e .
```

## Package

```
python3 -m build 
twine check dist/*
```

