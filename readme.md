# Binary Search Package

A simple and efficient binary search implementation for JavaScript arrays.

## Installation

Install the package using npm: `npm i ibrahim-binary_search`

## Usage

First, import the `binarySearch` function:

```javascript
const binarySearch = require('ibrahim-binary_search');
const sortedArray = [1, 3, 5, 7, 9, 11, 13, 15];
const target = 7;

const result = binarySearch(sortedArray, target);

console.log(result); // Output: 3 (index of the target value)