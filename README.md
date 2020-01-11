# Example-Use-Cases 

Grouped example uses-cases used in master thesis "Engineering an Analysis Tool for Comparing Transaction Costs in Ethereum Smart Contracts" written at University of Duisburg-Essen
Germany.

##Description
Designed use-cases can be used to evaluate the scenario-eth-gas-cli/scenario-eth-gas-reporter which was implemented in the master thesis.

Each Use-Case is represented in an own Github-Repository. If you have trouble to use one of this use-case please open an Issue in the corresponding Repository.

## Usage
Clone this repo:
``git clone https://github.com/nullenboom/Example-Use-Cases.git ``

Init submodules:
``git submodule init``

Update submodules:
``git submodule update`` 

Go into an use-case of your choice. Start your locale blockchain and use truffle to execute the test-cases. 
If you are using scenario-eth-gas-cli, it will configure the truffle-config file for you. If you are just using the scenario-eth-gas-reporter you need to add some lines to the truffle-config file. 
See the respective repo for installation instruction.

## Example Reports
If you are only interested for example result: At least one report for each use-case can be found in the project example-scenario-eth-gas-reports


## Description of Use-Cases
### First Use-Case: Check Parity
Parity of two input number will be checked with two implement variants for parity. <br>
* modulo-operator
* binary comparison 
### Second Use-Case: Add Numbers and calculate Average

### Third Use-Case: Different Solidity Compiler Options
