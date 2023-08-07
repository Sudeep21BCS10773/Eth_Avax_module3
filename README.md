# Eth_Avax_module3
# SudeepDahiyaToken Smart Contract

SudeepDahiyaToken is a simple ERC-20 token smart contract written in Solidity. It provides basic functionality for managing a custom token called "SudeepDahiyaToken" (SDT).

## Overview

This smart contract implements the following features:

- Name: SudeepDahiyaToken
- Symbol: SDT
- Decimals: 20
- Total Supply: 100 SDT (with 20 decimal places)
- Initial Minting: The contract owner receives 100 SDT during deployment.
- Token Transfer: Users can transfer SDT to other addresses.
- Minting: The contract owner can mint new SDT tokens.
- Burning: Token holders can burn their own tokens.

## Contract Details

- **name**: The name of the token ("SudeepDahiyaToken").
- **symbol**: The symbol of the token ("SDT").
- **decimals**: The number of decimal places for the token (20).
- **totalSupply**: The total supply of tokens (100 SDT).
- **balanceOf**: A mapping of addresses to token balances.
- **owner**: The address that deployed the contract and is the initial owner.

## Functions

- **mint**: Allows the contract owner to mint new SDT tokens and distribute them to an address.
- **burn**: Allows a token holder to burn (destroy) their own SDT tokens.
- **transfer**: Allows token holders to transfer SDT tokens to another address.

## Usage

1. Deploy the smart contract to the Ethereum network.
2. Interact with the contract using the provided functions.
   - Use the `mint` function to create new SDT tokens.
   - Use the `burn` function to destroy SDT tokens.
   - Use the `transfer` function to send SDT tokens to another address.

## Deployment

To deploy the SudeepDahiyaToken contract:

1. Use a Solidity development environment like Remix or Truffle.
2. Set the Solidity version to ^0.8.0.
3. Deploy the contract to an Ethereum network of your choice.
4. After deployment, the contract owner can use the `mint` function to create and distribute new SDT tokens.

## Security Considerations

This is a simple example contract and does not implement advanced security features. It's recommended to review and audit the contract code thoroughly before deploying it to a production environment.

## License

This smart contract is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
