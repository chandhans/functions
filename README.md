```markdown
# Custom Token Smart Contract

This Solidity smart contract implements a basic ERC-20 token named "Custom Token" (CTK). The contract provides functionality for token minting, burning, and transfers.

## Contract Details

- **Name:** Custom Token (CTK)
- **Symbol:** CTK
- **Solidity Version:** ^0.8.17
- **License:** MIT

## Features

1. **Initialization:** The contract can be initialized by an originator to mint an initial supply of tokens.

2. **Mint Tokens:** The originator can mint additional tokens and allocate them to a specified address.

3. **Burn Tokens:** Token holders can burn a specified amount of their own tokens.

4. **Transfer Tokens:** Token holders can transfer tokens to another address.

## Usage

1. Deploy the contract using a Solidity compiler with version ^0.8.17.

2. Initialize the contract by calling the `initialize` function. This can only be done once.

3. The originator can mint tokens using the `mintTokens` function.

4. Token holders can burn their own tokens using the `burnTokens` function.

5. Token holders can transfer tokens to another address using the `transferTo` function.

## Security

- The contract includes a `onlyOriginator` modifier to restrict certain functions to the originator.

- Deploy the contract securely, and safeguard the originator's private key.

## License

This smart contract is released under the [MIT License](LICENSE).
