<h1>Understanding the code</h1>

- This is a Solidity smart contract that creates an ERC20 token called "ShardeumERC20Token".

- We are importing the ERC20.sol contract from the OpenZeppelin library, which provides standard ERC20 functionality for creating a token.

- We have defined a constructor that takes two string parameters called _name and _symbol, which are used to set the name and symbol of the token respectively. It then calls the ERC20 constructor with these parameters.

- In the constructor, we are minting 10,000 tokens and are assigning them to the address that deployed the contract using the _mint function. The 10 ** 18 in the amount parameter represents the decimal value of the token.

- We have defined two public functions: mint and burn.

- The mint function takes a uint256 parameter called _amount and allows users to mint additional tokens. It calls the _mint function with the sender address and the _amount parameter to mint the specified number of tokens and assign them to the user.

- The burn function takes a uint256 parameter called _amount and allows users to burn their own tokens. It checks that the user has a sufficient balance using the require statement, then calls the _burn function to reduce the balance of the user by the specified amount.