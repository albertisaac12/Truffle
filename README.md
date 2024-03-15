# Truffle

```markdown
# Truffle Commands Cheat Sheet

Truffle is a development framework for Ethereum that facilitates smart contract development, testing, and deployment. This cheat sheet provides a quick reference for common Truffle commands.

## Installation

To install Truffle globally, use npm:

```
npm install -g truffle
```

## Commands

- **Initiate a New Project:**
    
    ```
    truffle init
    
    //This will make certain directors namely ./test, ./contracts, ./migrations, ./truffle-config.js
    ```
    
    This command initializes a new Truffle project in the current directory.
    
- **Compile Contracts:**
    
    ```
    truffle compile
    
    ```
    
    This command compiles all contracts within the Truffle project.
    
- **Migrate Contracts to the Blockchain:**
    
    ```
    truffle migrate [--network <network-name>] [--reset]
    
    ```
    
    Deploy compiled contracts to the blockchain. Use `--network` to specify the network and `--reset` to redeploy contracts from scratch.
    
- **Run Tests:**
    
    ```
    truffle test
    
    ```
    
    Run tests for contracts located in the `test/` directory.
    
- **Console:**
    
    ```
    truffle console [--network <network-name>]
    
    ```
    
    Open an interactive JavaScript environment pre-configured with project contracts and configurations. Use `--network` to specify the network.
    
- **Create a New Migration Script:**
    
    ```
    truffle create migration <migration-name>
    
    ```
    
    Create a new migration script file in the `migrations/` directory.
    
- **Create a New Contract:**
    
    ```
    truffle create contract <contract-name>
    
    ```
    
    Create a new Solidity contract file in the `contracts/` directory.
    
- **Create a New Test:**
    
    ```
    truffle create test <test-name>
    
    ```
    
    Create a new JavaScript test file in the `test/` directory.
    
- **Run a Specific Migration:**
    
    ```
    truffle migrate --f <migration-number>
    
    ```
    
    Run only the migration with the specified number.
    
- **Network Management:**
    
    ```
    truffle networks
    
    ```
    
    List networks configured in the project's configuration file.
