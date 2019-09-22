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

## Adding Packages/Dependencies

This project uses pipenv to manage dependencies. To add a dependency, do the following:

```
$ pipenv install PACKAGENAME
```

Where "PACKAGENAME" Is the name of the package you want to install.

## Project Layout

### Apps

Django projects are divided into "apps", each representing a discrete part of the project. 

Current proposal:
* users
* schedule

## Deploying

This is how you deploy our application to openshift.

First you will need to log into open shift. Go to the OpenShift web console, click the name dropdown in the top right, then click "Copy Login Command". On the page it brings you to click "Display Token". Copy and paste the login! 

After you have completed that step, it's time deploy the project

```
$ oc new
```

To deploy to openshift, do the following.


