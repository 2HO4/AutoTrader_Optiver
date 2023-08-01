# Autotrader Algorithm for Optiver's Ready Trader Go

## Getting Started

To run this project, you'll need Python version 3.11 or above and PySide6. If you don't have Python installed, you can download it from [www.python.org](https://www.python.org).

### Setting up the Python Virtual Environment

After installing Python, create a Python virtual environment to manage project dependencies. If you're unfamiliar with virtual environments, you can find instructions at [docs.python.org/3/library/venv.html](https://docs.python.org/3/library/venv.html).

### Installing PySide6

To use the graphical user interface, you'll need to install the [PySide6 package](https://pypi.org/project/PySide6/). You can install it by running the following command inside your Python virtual environment:

```bash
pip3 install PySide6
```

## Running a Ready Trader Go Match
To run a trading competition with one or more autotraders, simply execute the following command:

```bash
python3 rtg.py run [AUTOTRADER FILENAME [AUTOTRADER FILENAME]]
```

For example:

```bash
python3 rtg.py run autotrader.py
```

Each autotrader must have a corresponding JSON configuration file, as described below.

## Project Contents
This project includes everything needed to run a match where multiple autotraders compete against each other in a simulated market. The project contains the following files and directories:
1. autotrader.json: Configuration file for an example autotrader.
2. autotrader.py: An example autotrader.
3. data/: Sample market data used for testing.
4. exchange.json: Configuration file for the exchange simulator.
5. ready_trader_go/: The Ready Trader Go source code.
6. rtg.py: Use this Python script to run Ready Trader Go.
