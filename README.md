# BBVA Plugin for [ofxstatement](https://github.com/kedder/ofxstatement/)

Parses BBVA xslx statement files to be used with GNU Cash or HomeBank.

## Installation

You can install the plugin as usual from pip or directly from the downloaded git

### `pip`

    pip3 install --user ofxstatement-bbva

### `setup.py`

    python3 setup.py install --user

## Usage
Download your transactions file from the official bank's site and then run

    ofxstatement convert -t bbva BBVA.xlsx BBVA.ofx
