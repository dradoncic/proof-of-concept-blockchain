## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## Sample Transaction
Creating and Mining Genesis block...
Transaction processing.
Mined 00000014b755a5edda7eb59d67dbb3ad02b393c3bb15822e28d089983284cdf6

WalletA's balance is: 10000.0
WalletB's balance is: 0.0
Miner's balance is: 0.0
Transaction processing.
Transaction processing.
Transaction processing.
Transaction processing.
Transaction processing.
Mined 000000e5c6cdbeba2c4b7f6c467f288e482be4ead31a6261ef71e030f9157ed8

WalletA's balance is: 9800.0
WalletB's balance is: 200.0
Miner's balance is: 0.0
Blockchain is valid

## How it Works
Uses a number of cryptographic protocol libraries to implement SHA256 transaction hashing and Elliptic-Curve Public and Private Key Generation. 
This POC Blockchain is implemented using UTXO's rather than an acoount based implementation.
EX.
Send: 1.2    Balance: 10.0
Change: 8.8  Balance: 8.8
Network forms a larger transaction from all the smaller/medium size UTXO's held in someones wallet.
