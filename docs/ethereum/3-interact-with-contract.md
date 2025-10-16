---
sidebar_position: 3
---

# Interact with EVM Contract

## Add Your Contract

To begin working with your EVM contract in **_ChainForge_**, choose one of the following methods:

### Method 1: Deploy and Interact

If you intend to deploy your EVM contract to the blockchain, you must provide:

- **EVM ABI** (JSON array format)
- **EVM bytecode** (hexa data)

Navigate to [Contract Templates](https://tranquanghuy7198.github.io/chainforge/#/contract-templates) to add these artifacts.

### Method 2: Interact Only

If you only need to interact with an existing EVM contract, the EVM ABI is sufficient.

Navigate to [Contract Explorer](https://tranquanghuy7198.github.io/chainforge/#/contracts) to register your contract.

## Interaction

You can quickly interact with your EVM contracts by providing necessary parameters:

- **Complex parameters** (arrays, custom structs, etc.) must be provided in JSON format
- **Native parameters** (addresses, numbers, strings, etc.) can be provided as plain text
