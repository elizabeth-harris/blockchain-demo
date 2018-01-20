## A simple blockchain demo app

This tool allows you to interact with a very minimal blockchain. It's designed to allow investigating the inter-workings of a blockchain. We'll continue adding functionality and enhancement as we go.

This is a progression of the work shared by Daniel van Flymen in his post: [Building a Blockchain](https://medium.com/p/117428612f46)

## Installation

1. Make sure [Python 3.6+](https://www.python.org/downloads/) is installed.
2. Install [pipenv](https://github.com/kennethreitz/pipenv).

```
$ pip install pipenv
```

3. Create a _virtual environment_ and specify the Python version to use.

```
$ pipenv --python=python3.6
```

4. Install requirements.  

```
$ pipenv install
```

5. Run the server:
    * `$ pipenv run python blockchain.py`
    * `$ pipenv run python blockchain.py -p 5001`
    * `$ pipenv run python blockchain.py --port 5002`


----------------------------
TODO: Finish implementing the UI
