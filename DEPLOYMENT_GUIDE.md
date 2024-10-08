# Eclipse Deployment Guide

This guide outlines the steps for deploying on the Eclipse network.

## Prerequisites

1. **Bridge ETH**: You must bridge ETH into either the Eclipse Mainnet or Testnet using your existing wallet.
   - Use the [Bridge Validator](https://bridge.validators.wtf/) for this step.

2. **Generate Metadata URL**: 
   - Use the [ZunxBT Metadata Generator](https://zunxbt.github.io/Eclipse/) to generate your metadata URL. Save the credentials as they will be required during code execution.

## Deployment Instructions

1. **Run the Deployment Script**:
   Download the deployment script from the following link:  
   [eclipse.sh](https://raw.githubusercontent.com/akroyals21/Eclipse-DEPLOY/refs/heads/main/eclipse.sh).

2. **Follow the Prompts**:
   - The script will prompt you with options numbered from 1 to 5. Execute options 1 to 4 one by one. 
   - Choose option 5 to exit if no further deployment is needed.

## Wallet Setup

### Importing an Old Wallet

- If you have previously performed testnet operations, you may have a private key in a byte array format, which looks like this:  
  `[1, 2, 3, ..., 64]`

- If you have this private key, proceed with the import.

- If you do not have the key, create a new wallet. Upon creation, you will receive a public key.

### Bridging Ethereum

To bridge Ethereum from the Ethereum Mainnet to Eclipse, visit:  
[Bridge Validators](https://bridge.validators.wtf/).

### Import Private Key

1. After exiting the directory (by selecting option 5), run the following command to import your private key into the Backpack wallet:
   ```bash
   cat $HOME/solana_keypairs/eclipse-new.json

