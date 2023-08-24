# Solidity Error Handling Example

This Solidity contract demonstrates different error handling mechanisms, including the use of `require`, `revert`, `assert`, and a custom user-defined error. The contract provides functions that showcase these error handling techniques and explain their usage.

## Description

This contract showcases various error handling strategies in Solidity and helps developers understand how to handle exceptional conditions gracefully.

## Functions and Error Handling

### e1(uint a) - `require`

This function takes an input `a` and returns `a * 2` if `a` is greater than 10. Otherwise, it reverts with an error message "please input greater than 10".

### e2(uint a) - `revert`

This function modifies the state variable `b` and then reverts if the input `a` is greater than 10. It returns the updated value of `b` if the condition is not met.

### e3(uint a) - `assert`

This function squares the state variable `b` and then asserts that the input `a` is equal to 0. If the assertion fails, it reverts with the message "match found".

### myError(uint256 a) - Custom Error

This function uses the block's gas limit and a custom user-defined error to check if `var1` is greater than the input `a`. If the condition is true, it reverts with a custom error message "gas limit exceeded".

## Getting Started

To understand how these error handling techniques work, you can use Remix, an online Solidity IDE. Follow these steps:

1. Go to https://remix.ethereum.org/.
2. Create a new file named `errors.sol` and paste the provided Solidity code.
3. Compile the code by selecting the appropriate compiler version.
4. Deploy the contract and interact with its functions using Remix's interface.

## Author

Priyanshu Pandey  
Email: whypriyanshu5603@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
