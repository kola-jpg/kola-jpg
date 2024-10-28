// SPDX-License-Identifier: MIT
pragma solidity 0.8.28;


contract EvenOddcheck {
    // Function to check if a number is even
    function isEven(uint number) public pure returns (bool) {
        // Using the modulo operator to check for even or odd
        if (number % 2 == 0) {
            return true; // The number is even
        } else {
            return false; // The number is odd
        }
    }
}
