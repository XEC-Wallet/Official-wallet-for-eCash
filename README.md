# [Official wallet for eCash](https://xecwallet.org)
Open source crypto wallet

![Logo](https://i.ibb.co/qm2YbW2/Xec-Wallet.png)

### Features
- Send & Receive XEC
- Import existing wallets

### Links

| Name | Link |
| ------ | ------ |
| eCash wallet | https://xecwallet.org |
| eCash explorer | https://explorer.e.cash |
| eCash Price | https://coinmarketcap.com/currencies/ecash |

### Development
```sh
npm install
npm start
```

Runs the app in the development mode.
Open localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### Testing
Run the tests in watch mode (interactive):
```sh
npm test
```
Run the tests and generate a coverage report (non-interactive):
```sh
npm run test:coverage
```
You can then browse the HTML coverage report by opening the coverage/lcov-report/index.html file in your web browser.

### Docker deployment
```sh
npm install
docker-compose build
docker-compose up
```

### How Is the eCash Network Secured?
In contrast to the Bitcoin Cash ABC (BCHA) network, which is secured using a proof-of-work (PoW) consensus mechanism, the developers of eCash plan to add proof-of-stake (PoS) in order to speed up transactions. What they term “Avalanche post-consensus” would see enhanced security and fork-free upgrades and allow for advanced opcodes thanks to enhanced script capability. The Avalanche layer will be added on top of the existing PoW in order to leverage the benefits of both.

**XEC is not an ERC-20 token, it is its own blockchain similar to Bitcoin (BTC).**
