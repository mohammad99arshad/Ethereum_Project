MyToken - A Basic Fungible Token
A simplified implementation of a fungible token contract for learning and experimentation. The main function is to mint and burn tokens to demonstrate token creation and destruction.


Description
This project is a basic Solidity smart contract designed to help beginners understand the core concepts of token creation and management on the Ethereum blockchain. It simulates a simple token with the following features:

Token Information: The contract stores the token's name (JaskaranSingh), abbreviation (JKS), and total supply. Minting: The mint function allows the creation of new tokens and their allocation to a specified address. Burning: The burn function enables the destruction of tokens from a specific address, reducing the total supply. Balance Tracking: The contract uses a mapping (bal) to track the token balances of each address.

While this project is not a fully-fledged ERC-20 token implementation (it lacks transfer and approval functions), it provides a valuable starting point for understanding how tokens work at a fundamental level.

Getting Started

Executing Program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., token.sol). Copy and paste the following code into the file:

