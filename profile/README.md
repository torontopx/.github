# <img width="28" height="28" alt="tpx-logo" src="https://github.com/user-attachments/assets/b42ca7b6-e41a-40f3-a39f-a4f74846b84d" /> Toronto Prediction Exchange

Trade shares on binary outcome markets across sports, finance, politics, culture, and more.

## What We Do

Toronto Prediction Exchange is an options exchange where participants can trade shares on prediction markets. The exchange uses the Central Limit Order Book (CLOB) trading method with Merges and Splits.

Splits are when cash is converted into an equal number of contracts on both sides. I.e. a participant can input $1 to receive 1 YES contract and 1 NO contract for a given market.

Merges are when opposing contracts are combined and destroyed to redeem cash. I.e. a participant can input 1 YES contract and 1 NO contract for a given market to redeem $1.

## Current Status

The tpx monolith operates both as a brokerage and central exchange. There exists a thin API layer for participants to trade programatically.

The order book and engine will eventually be broken out into a stand-alone system. When this happens, the web application will operate strictly as a broker and GUI for participants.

## Contact

- Website: [torontopx.ca](https://www.torontopx.ca)
- Email: hello@torontopx.ca
