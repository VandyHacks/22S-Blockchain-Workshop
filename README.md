# 22S-Blockchain-Workshop

Presented by: Lincoln Murr (Blockchain Club)

## Instructions
### Setup
1. Install the [MetaMask Chrome plugin](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en) in a Chrome browser
2. Go through the setup of a new account
3. Since we are not going to be dealing with real Ethereum, we will be using test networks. Click on your profile and enable test networks by going to **"Settings > Advanced > Show Test Networks"** and switching it on
4. Once enabled, go back to your homepage and click the dropdown with "Ethereum Mainnet" on the top of the page and switch to the "Ropsten Test Network"
5. Locate your account address. Below the network dropdown mentioned above, you will see the name of your account (typically "Account 1") and a long hex value that represents the location of your account
6. To get some test Ethereum for free, use a faucet. An example is provided [here](https://faucet.egorfine.com/). Paste your account address in the text box and check your account to see if your test eth has been transferred. This may take up to 5 minutes
### Creating a Token
1. Create a new project in the [Remix IDE](https://remix-project.org)
2. Create a new .sol file in the *contracts* folder
3. Write your contract in this new file (source code provided [here](SquirrelCoin.sol))
4. Compile your contract in the "Compile" tab or by using the shortcut **Control+S**
5. Go to the "Deploy & Run Transactions" tab
6. Switch the "Environment" dropdown to "Injected Web3"
7. Ensure that the Account selected is yours (found on your MetaMask homepage)
8. Under "Value," enter the desired amount of Eth you would like to transfer. Note that the unit here is Wei, which is 10^-18th of an Eth.
9. Click Deploy to publish your contract
10. The progress of your transaction will be provided at the bottom right of the IDE. You can click "view on etherscan" to see the live progress of your contract on the blockchain
