# NumberList.sol
NumberList.sol5
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract NumberList {
    uint[] public numbers;

    function addNumber(uint _num) public {
        numbers.push(_num);
    }
}
Add beginner-friendly Solidity contracts
Update setter logic
Add getter function
Clean code formatting
