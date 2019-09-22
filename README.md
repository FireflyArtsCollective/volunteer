# volunteer

A Website to Manage Volunteering

## Setup

The required version of Python for this project is 3.7.4. It suggested that you use [pyenv](https://github.com/pyenv/pyenv) to juggle your python versions. 

To install Python 3.7.4 with Pyenv proceed to do the following:

```
$ pyenv install 3.7.4
```

It is helpful to set python 3.7.4 as your default python. We will do that now:

```
$ pyenv global 3.7.4
```

Additionally, this project uses [pipenv](https://docs.pipenv.org/en/latest/) to manage its dependencies.

To install pipenv, perform the following:

```
$ pip3 install pipenv
```

After you've installed pipenv, go to the root of this repository and install our dependencies and enter a pipenv shell

```
$ pipenv install
$ pipenv shell
```

You will need to enter pipenv shell as you work, so next time also enter

```
$ pipenv shell
```
