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

## Upload to pypi

```
python -m build
twine check dist/*
twine upload dist/*
```

