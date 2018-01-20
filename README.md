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
There's two parts to what you can run. The first is a demonstration of how things play out prior to adding the logic that makes block-chains decentralized.

To start this version of the code, run:
    * `$ pipenv run python blockchain-preconsensus.py`
    * `$ pipenv run python blockchain-preconsensus.py -p 5001`
    * `$ pipenv run python blockchain-preconsensus.py --port 5002`
This shows a code state where each instance of the chain is separate and silo-ed.

The next step would be to copy the snippets from "blockchain-preconsensus-additions.py" into the correct spots, then rerun the nodes. There are some steps outlined in Daniel's blog post that allow you to see the play by play of what adding the block-chain consensus logic does.

The complete code can be run by executing:


    * `$ pipenv run python blockchain.py`
    * `$ pipenv run python blockchain.py -p 5001`
    * `$ pipenv run python blockchain.py --port 5002`

Currently I've started work on a Bootstrapped UI to interact with this API. This is found in the complete code. It's not done yet, but much of the functionality is present today.

----------------------------
TODO: Finish implementing the UI
