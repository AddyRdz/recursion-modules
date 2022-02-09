---
name: Homework submission template
about: Issue for submitting homework
title: Your Name Here
labels: ''
assignees: ''

---

## Answer the questions below! 

1. In your own words, define the terms "Recursion", "Base Case" and "Recursive Case"
> Your answer here. 

2. What are the basic steps to writing a recursive function? Provide a brief summary of each step. 
> Your answer here. 

3. In plain english, write all the steps that the `sumArrayOfNums` function goes through to evaluate `6` as the sum of the `nums` array.

```js
const nums = [1,2,3]

function sumArrayOfNums(arr, index = 0, sum = 0){
  if(index === arr.length) {
    return sum;
  }

  sum += arr[index];

  return sumArrayOfNums(arr, index + 1, sum);
}

sumArrayOfNums(nums)
```

> Your answer here.
