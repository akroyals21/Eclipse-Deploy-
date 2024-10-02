# Eclipse Deployment Guide

This guide outlines the steps for deploying on the Eclipse network.

## CREDIT

**Credits to**:  [ZUN](x.com/ZunXBT) This guide is based on Zun's original guide, with a significant modification allowing you to import your private key directly from your old wallet, enhancing your interactions with your old wallet.

## Prerequisites

1. **System**: Use any linux based system be it ubuntu(preferably),vps,codespaces,etc.

2. **Bridge ETH**: You must bridge ETH into either the Eclipse Mainnet or Testnet using your existing wallet.- Use the [Bridge Validator](https://bridge.validators.wtf/) for this step.

3. **Generate Metadata URL**:
   - Use the [ZunxBT Metadata Generator](https://zunxbt.github.io/Eclipse/) to generate your metadata URL. Save the credentials as they will be required during code execution.

## Deployment Instructions

1. **Download the Deployment Script**:  
   Download the deployment script using `curl` and save it as `eclipse.sh` I.e. one by one execute:
   ```bash
   curl -O https://raw.githubusercontent.com/akroyals21/Eclipse-DEPLOY/refs/heads/main/eclipse.sh
    
   chmod +x eclipse.sh
    
   ./eclipse.sh

2. **Follow the Prompts**:
   - The script will prompt you with options numbered from 1 to 5. Execute options one by one i.e. 1) then 2).....4)
   - Choose option 5 to exit if want no further deployments.
## Wallet Setup
### Importing an Old Wallet
- If you have previously performed testnet operations, you may have a private key in byte array form retrieved from solana cli in the form of
  `[1, 2, 3, ..., 64]`
- If you have this private key, proceed with the import.
- If you do not have the key, create a new wallet. Upon creation, you will receive the pubkey into which you bridge in funds and sorry for the inconvenience  please go to last instruction and follow it to import key into which eth is to be bridged at certain fee of 6-10 $ DEPENDING ON GWEI .use [BACPACK WALLET](https://chromewebstore.google.com/detail/backpack/aflkmfhebedbjioipglgcbcmnbpgliof)
### Bridging Ethereum
To bridge Ethereum from the Ethereum Mainnet to Eclipse, visit:
[Bridge Validators](https://bridge.validators.wtf/).
### Import Private Key
1. After exiting the directory (by selecting option 5), run the following command>
   ```bash
   cat $HOME/solana_keypairs/eclipse-new.json



`[DO GIVE A STAR TO MY REPO ]`

##  Thank You! ??

Do follow me as a token of appreciation
[mustanda](x.com/mustanda2302)
 

If you have any suggestions, issues, or ideas, feel free to open an issue or submit a pull request. Let's build something amazing together!

Happy coding! ?? Along with [ZunXBT](https://github.com/zunxbt)

