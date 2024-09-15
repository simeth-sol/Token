# MyToken Smart Contract

This solidity smart contract allows minting and burning of tokens, tracking the total supply and individual balances.

## Description

`MyToken` is a basic Ethereum smart contract that implements a token with the following features:

- Minting: Create new tokens and add them to a specified address.
- Burning: Destroy a specified number of tokens from an address.
- Balance Tracking: Maintain a record of the token balance for each address.

## Getting Started

### Installing

To interact with this smart contract, you need to have a Solidity development environment set up. You can use tool like [Remix IDE](https://remix.ethereum.org/).

1. **Clone the Repository (if the contract is hosted on GitHub):**

```
git clone https://github.com/yourusername/MyToken.git

```

2. **Open in Remix IDE:**

- Go to [Remix IDE](https://remix.ethereum.org/).
- Create a new file named `MyToken.sol` and paste the contract code into it.

### Executing program

**Using Remix IDE**

1. **Compile the Contract:**

  - Open Remix IDE.
  - Paste the code into a new Solidity file (e.g., `MyToken.sol`).
  - Select the appropriate compiler version (compatible with the code).
  - Click on the "Compile" button.

2. **Deploy the Contract:**

  - Navigate to the "Deploy & Run Transactions" tab in Remix.
  - Choose "MyToken" from the contract dropdown.
  - Click "Deploy" to deploy the contract to the Ethereum Virtual Machine (EVM).

3. **Interacting with the Contract:**

  - Once deployed, you can call the `mint` and `burn` functions:

  - **Mint Tokens:**
```
mint(address _address, uint _value)

```
Enter the address and the number of tokens to mint.

- **Burn Tokens:**

  ```
  burn(address _address, uint _value)

  ```
  Enter the address and the number of tokens to burn.

  - View the `totalSupply` and `balances` directly in the Remix interface.
 
## Help

If you encounter issues while interacting with the contract:

- Ensure you're using the correct Solidity compiler version.
- Verify that the contract is properly deployed by checking the transaction status in Remix.
- Make sure the address used in the mint and burn functions has enough balance for burning.

For more help, refer to Solidity documentation or Remix IDE troubleshooting guides.

## Authors

Simon Okwa [@OgbuOkwa](https://x.com/OgbuOkwa).

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

  





