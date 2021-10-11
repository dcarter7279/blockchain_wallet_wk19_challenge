# blockchain_wallet_wk19_challenge

Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. The application has been intergrated with the Ethereum blockchain network in order to enable its customers to instantly pay the fintech professionals whom they hire with cryptocurrency. 

# Technologies 
pip install bip44
pip install mnemonic
pip install streamlit
pip install web3==5.17

# Imports- for crypto_wallet.py

import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3.auto.infura.kovan import w3
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy

# Imports - fintech_finder.py

from bip44.wallet import Wallet
import mnemonic
import streamlit as st
from dataclasses import dataclass
from typing import Any, List

# Example

![Screen Shot 2021-10-11 at 10 47 34 AM](https://user-images.githubusercontent.com/36581111/136810715-3dc28596-81ad-4981-b6e0-72e04b1f4e80.png)
![Screen Shot 2021-10-11 at 10 23 20 AM (2)](https://user-images.githubusercontent.com/36581111/136808247-abb25e7c-1145-4248-a617-15a5fad64345.png)
![Screen Shot 2021-10-11 at 10 24 09 AM](https://user-images.githubusercontent.com/36581111/136808262-088a24b4-614a-487d-ad04-7914902106cb.png)
![Screen Shot 2021-10-11 at 10 24 50 AM](https://user-images.githubusercontent.com/36581111/136808269-637b8d8b-7664-432b-bf56-2bf6b9181a46.png)
![Screen Shot 2021-10-11 at 10 26 59 AM](https://user-images.githubusercontent.com/36581111/136808285-068db553-7f5b-4644-a821-0ff16b4dd3b8.png)

# Contributors 

Donell Carter email address: dcarter7279@gmail.com
