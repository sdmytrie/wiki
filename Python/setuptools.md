:setuptools:package:

# Setuptools

Fichier `setup.cfg`

```
[metadata]
name = Labo
author = Serge D.
description = Only for testing
version = 1.0.0

[options]
packages = find:
install_requires = 
  flask

[options.entry_points]
console_scripts = 
  labo = main:main
  
  
```

Fichier `setup.py`

<!---->

```
from setuptools import setup
setup()

```

Install package

<!---->

    pipenv install -e .
