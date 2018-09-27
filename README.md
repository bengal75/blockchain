# Learn Blockchains by Building One

This is the source code for Daniel van Flymen's Hackernoon post on [Building a Blockchain](https://medium.com/p/117428612f46).

Adapted by [Ben Galloway](mailto:ben@bengalloway.io) for use at UAE Cyber Quest 2018, including the addition of a simple webapp frontend here contained in the `static` directory and served as static files by Flask.

## Installation

In a command window, in the same directory as this file:

1. Check that Python is available. The Hackernoon code requires Python 3, so you may need to use that binary:
```
python3 --version
```
2. If you have `python3`, you hopefully also have `pip3`!
```
pip3 --version
```
3. All being well, install the required Python dependencies:
```
pip3 install -r requirements.txt
```
4. Start the server by saying:
```
python3 blockchain.py
```
This will listen on port 80 by default, so all that the participants then need to do is connect to the IP address of the laptop that the Python script is running on, in a web browser.