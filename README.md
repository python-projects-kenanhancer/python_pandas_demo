# python_pandas_demo
Pandas demo

## List Python runtime versions with pyenv

`$ pyenv install --list`

## Install Python runtime with pyenv

`$ pyenv install 3.10.13`

## Select local Python runtime

`$ pyenv local 3.10.13`

## Create Virtual Environment in project root folder

`$ PIPENV_VENV_IN_PROJECT=true pipenv --python $(pyenv which python)`

## Activate Virtual Environment

`$ pipenv shell`

## Deactivate Virtual Environment

`$ exit`

## Remove Virtual Environment

`$ pipenv --rm`
