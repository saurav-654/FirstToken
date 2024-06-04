# MyToken 

The `MyToken` smart contract is a basic token management system using Solidity. It has three public variables , mapping function , mint function and burn function. If statement is present in the burn function tomake sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned 

## Contract Details

- Token Name: _Name_
- Token Abbreviation: _Abbrv_
- Total Supply: 0 

## Public Variables

- TokenName: Stores the name of the token.
- TokenAbb: Stores the abbreviation of the token.
- totalSupply: Tracks the total supply of tokens.

## Functions

### mint(address _add, uint _value_)

- Increases the total supply by the specified value.
- Increases the balance of the given address by the same value.
- Parameters:
    - _add: Address to mint tokens for.
    - _value_: Amount of tokens to mint.

### burn(address _add, uint _value_)

- Decreases the total supply by the specified value.
- Decreases the balance of the given address by the same value.
- Parameters:
    - _add: Address to burn tokens from.
    - _value_: Amount of tokens to burn.

## Author
Saurav Agrawal
