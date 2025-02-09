Table of Contents
- [Overview](#overview)
- [Use Cases](#use-cases)
- [Token Contract](#token-contract)
  - [SRC-20 Functionality](#src-20-functionality)
    - [`total_assets()`](#total_assets)
    - [`total_supply()`](#total_supply)
    - [`name()`](#name)
    - [`symbol()`](#symbol)
    - [`decimals()`](#decimals)
    - [`set_name()`](#set_name)
    - [`set_symbol()`](#set_symbol)
    - [`set_decimals()`](#set_decimals)
  - [SRC-3](#src-3)
    - [`mint()`](#mint)
    - [`burn()`](#burn)

# Overview

This document provides an overview of the application.

It outlines the use cases, i.e. desirable functionality, in addition to requirements for the smart contract and the user interface.

# Use Cases

This section contains general information about the functionality of the application and thus does not touch upon any technical aspects.

If you are interested in a functional overview then this is the section for you.

# Token Contract

## SRC-20 Functionality

### `total_assets()`

This function will return the total number of individual assets for a contract.

### `total_supply()`

This function will return the total supply of tokens for an asset.

### `name()`

This function will return the name of an asset, such as “Ether”.

### `symbol()`

This function will return the symbol of an asset, such as “ETH”.

### `decimals()`

This function will return the number of decimals an asset uses.

### `set_name()`

This function will set the name of an asset.

### `set_symbol()`

This function will set the symbol of an asset.

### `set_decimals()`

This function will set the decimals of an asset.

## SRC-3

### `mint()`

This function will mint new tokens using a sub-identifier.

### `burn()`

This function will burns tokens with the given sub-identifier.
