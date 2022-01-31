# Project Title

This is the Fintech Professional Finder application for Challenge 19! I begin by importing functions I need from the crypto_wallet.py
file.  I create an account and pull in the account balance and write it to the sidebar of what will be webpage by using streamlit later!
After that I calculate a wage based on a candidate's hourly wage expectations multiplied by the hours we are hoping to hire them for.
I then write that to the sidebar as well.

After the above is completed I create a function where I send a transaction for payment to my candidate of choice, and for the number of hours I want them to work! It is crazy how much power we have with such little code! I test that everything is working by finally going to ganache and seeing my account and transaction as proof of my transactions being sent. All very exciting!

## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:
# Imports
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

---


## Usage

Go to the directory where fintech_finder.py is located and run the file by typing streamlit run fintech_finder.py in the command
line and that's it!  From there the person can select which fintech professional to use, and how many hours you'd like to hire them for.
After that is decided you can click the send transaction button at the bottom and you are done.


---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
