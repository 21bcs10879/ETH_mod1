# ETH_mod1
Error Handling tehniques

 Creating a smart contract that implements the require(), assert() and revert() statements.

## Description
 There are three methods that constitute the error-handling process in Solidity:

require():
The require() function is used to validate specific conditions before a function continues execution. It accepts two parameters as input. If the condition fails, the function stops executing, and an optional message (the second parameter) is logged. The second parameter is not mandatory; require() will still function if only the condition is provided. The condition for the above is mentioned below-
require(<condition to be validated> , <message to be displayed if the condition fails>);



assert():
Similar to require(), the assert() function checks a condition, and if the condition is not met, the function execution is halted with an error. The syntax for assert() is:
assert(<condition to be checked/validated>);

revert(): 
The revert() function is used to flag an error and revert the current transaction. It can include an optional message to provide details about the error, which will be returned to the caller. When revert() is invoked, it reverts all changes made to the state, returning it to its previous state before the function call. This is crucial when it's unsafe to continue execution due to unexpected conditions, and it also helps conserve gas.





### Installing
Go to https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.26+commit.8a97fa7a.js
And start writing the code 


### Executing program

First, write the code. Once the code is complete, compile it and check for any errors. If errors are present, resolve them, and feel free to reference my code for assistance if needed. After successful compilation, deploy the contract and test each function by passing appropriate values. Verify the output of each function to ensure they work correctly.

## Authors

Aryan Arman


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
