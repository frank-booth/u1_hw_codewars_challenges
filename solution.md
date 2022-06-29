## Return Negative

function makeNegative(num) {
  if (num < 0) {
    return num
  } else {
    return -Math.abs(num)
  }
}

## Sum of Positive

function positiveSum(arr) {
  let sum = 0
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i]
    }
  }
  if (sum > 0) { 
  return sum
  } else {
    return 0
  }
}

## Function 2

function square (num) {
  return Math.pow(num, 2)
}

## Sum Arrays

let sum1 = 0
let i = 0

function sum (numbers) {
  "use strict";
  if (Array.isArray(numbers) === true) {
    for (let i = 0; i < numbers.length; i++) {
      sum1 += numbers[i]
    }
  } else {
      return 0
    } 
  return sum1
};

## Reversed Strings

function solution(str){
  let reverseStr = ""
  for (let i = str.length - 1; i >= 0; i--) {
    reverseStr += str[i]
  }
  return reverseStr
}
