# DESCRIPTION

Describe ERC-20.

Ethereum Request for Comment is referred to as ERC. In essence, they are community-approved standards that are used to communicate technical specifications and requirements for particular use cases.

A specific standard that describes the technical requirements of a fungible token is ERC-20.

Let's examine it line by line to better understand what is happening:

pragma solidity ^0.8.0;

The Solidity compiler version that will be used is specified in this line. Any version after 0.8.0 is referred to as 0.8.0. Generally speaking, you should use the most recent version of the Solidity compiler because new versions typically come with either new features or optimizations.


import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol";

This line imports the OpenZeppelin ERC-20 token standard (OZ). OZ is a provider of Ethereum security. OZ creates reference contracts for well-liked smart contract standards that are secure and have undergone extensive testing. Instead of writing the entire standard from scratch when implementing a smart contract that must adhere to a standard, try to find an OZ reference implementation.




