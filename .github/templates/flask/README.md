# teste_flask Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/Rapaix/teste-flask teste_flask
cd teste_flask
make install
```

From pypi:

```bash
pip install teste_flask
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ teste_flask
```

or

```bash
$ python -m teste_flask
```

To see the help message and usage instructions.

## First run

```bash
teste_flask create-db   # run once
teste_flask populate-db  # run once (optional)
teste_flask add-user -u admin -p 1234  # ads a user
teste_flask run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
