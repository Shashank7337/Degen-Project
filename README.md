DegenToken

This Solidity contract is for the DegenToken, an ERC20 token built using OpenZeppelin's ERC20 contract. The contract also contains a simple in-game store (DegenStore) where users can redeem items using the DegenToken. Users can mint, burn, and transfer tokens, as well as redeem items from the store by paying with the tokens.

Description

DegenToken is an ERC20 token contract that enables the creation, burning, and transfer of tokens. The contract also features an in-game store with five items that can be redeemed by users. The store tracks item supply, and when a user redeems an item, the token amount equivalent to the item's price is burned from the user’s account.

The purpose of this contract is to demonstrate the use of ERC20 tokens with additional functionality like minting, burning, and using tokens to redeem virtual items in a store.

Getting Started

Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Project4.sol). Copy and paste the code into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.26" (or another compatible version), and then click on the "Compile Project4.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "DegenToken - Project4.sol" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can mint, burn, check balances, transfer tokens, and redeem store items through the contract’s functions.

Author

Shashank Shekhar
