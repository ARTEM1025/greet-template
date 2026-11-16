# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

```bash
python -m pip install -e .
```

## Run the tests

Run the test command:

```bash
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"
```

Expected output: `Hello, Hee!`

## Send a change

1. Branch from `main` and commit your changes.
2. Push the branch to GitHub.
3. Open a pull request to `main`.
