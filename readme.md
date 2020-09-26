# Telegram Word Cloud 繁體中文

> I just want to know how Karlam and I speaks during Telegram chat

## Get started (Python)

### Install dependencies
```bash
# pyenv https://python-poetry.org/docs/managing-environments/
# so whenever we run `poetry add xxx`, they are added to the python shell we want
# then we select the shell from vscode ipynb playbook
# brew install pyenv # optional, we just need to install the predefined python version from poetry's config

# Poetry: https://python-poetry.org/docs/basic-usage/
pip3 install poetry # poetry = npm, and we want to use python3
poetry config virtualenvs.in-project true # install to local node_modules
poetry install # install from Pipfile
```

### Select the correct python interactive shell

> Select the one where `site_packages` are installed in

![Python Shell](./assets/readme/python_shell.png)