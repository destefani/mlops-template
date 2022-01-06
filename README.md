# MLOps project template

Template repo for a Machine Learning project following MLOps good practices

Files:
- Makefile
- requirements.txt
- hello.py
- test_hello.py
- Virtualenv

## Create a virtual environment
Create a virtual environment using python's `venv`:

```
python3 -m venv ~/.your-repo-name
```

Activate the virtual environment:

```
source ~/.your-repo-name/bin/activate
```

## Makefile

Install dependencies:

```
make install
```

Lint code:

```
make lint
```

Format code:

```
make format
```

Test code:

```
make test
```

# Continuous Integration
Automatically build and test code when merged.

# Continuous Delivery
Automatically deploy code.



