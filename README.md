# USD-BTC
USD-BTC-THORSWAP-ONRAMP


# usd-btc-thorswap-onramp

This is an app that allows users to swap USD for BTC and then use BTC to swap with other cryptocurrencies on THORSwap, a decentralized exchange powered by THORChain.

## Features

- Accept USD payments from customers using BitPay, a payment processor that supports crypto conversions.
- Convert USD to BTC automatically using BitPay's exchange rate and API.
- Swap BTC with other cryptocurrencies on THORSwap using their API and app interface.
- Display the swap details, fees, and status to the user.

## Installation

To install and run this app, you need to have the following:

- A GitHub account and a repository for your app.
- A BitPay account and an API key for your app.
- A THORSwap account and a wallet address for your app.
- A web server and a domain name for your app.

To install this app, follow these steps:

- Clone this repository to your local machine using the command `git clone https://github.com/your-username/usd-btc-thorswap-onramp.git`.
- Navigate to the app directory using the command `cd usd-btc-thorswap-onramp`.
- Install the required dependencies using the command `npm install`.
- Create a .env file in the app directory and add the following variables:

  - BITPAY_API_KEY: Your BitPay API key.
  - THORSWAP_API_KEY: Your THORSwap API key.
  - THORSWAP_WALLET_ADDRESS: Your THORSwap wallet address.

- Save and close the .env file.
- Start the app using the command `npm start`.
- The app will run on `http://localhost:3000` by default. You can change the port number in the app.js file.

## Usage

To use this app, follow these steps:

- Open your web browser and go to `http://localhost:3000` or your domain name.
- You will see a form where you can enter the amount of USD that you want to swap and the cryptocurrency that you want to receive on THORSwap.
- Click on the "Pay with BitPay" button and follow the instructions to complete the USD payment.
- Once the payment is confirmed, you will see a confirmation message and a link to view the transaction details on BitPay.
- The app will automatically convert your USD to BTC and send it to your THORSwap wallet address.
- You will see a message that says "Swapping BTC with [CRYPTO] on THORSwap" and a link to view the swap details on THORSwap.
- Once the swap is completed, you will see a confirmation message and a link to view the transaction details on THORSwap.
- You can check your THORSwap wallet balance and history on their app.

## Contribution

This app is open source and welcomes contributions from other developers. If you want to contribute to this app, follow these steps:

- Fork this repository to your GitHub account.
- Create a new branch for your feature or bug fix using the command `git checkout -b your-branch-name`.
- Make your changes and commit them using the command `git commit -m "your-commit-message"`.
- Push your changes to your forked repository using the command `git push origin your-branch-name`.
- Create a pull request from your forked repository to this repository.
- Wait for your pull request to be reviewed and merged.

## License

This app is licensed under the MIT License. See the LICENSE file for more details.

