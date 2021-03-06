# Example-Use-Cases 
Grouped example uses-cases used in master thesis "Engineering an Analysis Tool for Comparing Transaction Costs in Ethereum Smart Contracts" written at University of Duisburg-Essen Germany to evaluate the developed tools [scenario-eth-gas-cli](https://github.com/nullenboom/scenario-eth-gas-cli) and [scenario-eth-gas-reporter](https://github.com/nullenboom/scenario-eth-gas-reporter)

## Description
Designed use-cases can be used to evaluate the scenario-eth-gas-cli/scenario-eth-gas-reporter which was implemented in the master thesis.

Each Use-Case is represented in an own Github-Repository. If you have trouble to use one of this use-case please open an Issue in the corresponding Repository.

## Usage
Clone this repo:
``git clone https://github.com/nullenboom/Example-Use-Cases.git ``

Init submodules:
``git submodule init``

Update submodules:
``git submodule update`` 

Go into an use-case of your choice. Start your locale blockchain (or copy the script folder if you are using the scenario-eth-gas-cli) and use truffle to execute the test-cases. 
Truffle-Config.js file is already configured to use the scenario-eth-gas-reporter, but it needs to be installed.
See the respective repo for installation instruction.

## Example Reports
If you are only interested for example result: At least one report for each use-case can be found in the project example-scenario-eth-gas-reports


## Description of Use-Cases
### First Use-Case: Check Parity
Parity of two input number will be checked for parity: 
* Two Implement-Variants
  * Modulo-Operator
  * Binary-Comparison
* Two Usage-Scenario 
  * Both even Numbers (10, 20)
  * One Even/One uneven Number (10, 5)


### Second Use-Case: Add Numbers and calculate Average
Add a Number to a sum and calculate average. 
* Two Implement-Variants (AvgOnDemand and AvgOnObserv)
  * AvgOnDemand: calculates the average on demand.
  * AvgOnObserv: calculates the average every time the add function is called and saves it into an variable
* Three Usage-Scenario with different numbers of function calls:
  * Scenario A: 100 - 150 Add / 1-15 Calc 
  * Scenario B: 1-150 Add and Calc
  * Scenario C: 1-15 Add / 100-150 Calc


### Third Use-Case: Different Solidity Compiler Options
Increment a counter.
* 4 different Compiler Options 
  * Compiler Version 0.5.0
  * Compiler Version 0.5.0 with Optimizer (Runs = 200)
  * Compiler Version 0.5.15
  * Compiler Version 0.5.15 with Optimizer (Runs = 200)
* 2 Implement Variants
  * IncrementShort
  * IncrementLong
* 1 Usage-Scenario 
  * one function call
