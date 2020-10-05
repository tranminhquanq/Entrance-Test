# Knowledge

* Knowledge of Javascript like: Variables, data types, array, object, function, scope, operators,...
* Manipulated the DOM with HTML, CSS.
* Know how to use API related such as GET, POST, PUT, DELETE.

# Challenges

## A. Problem Solving
#### 1. Junction or Self

In this challenge, you have to separate integers into two families, establishing if they are Junction Numbers or Self Numbers. Given a positive number `n`:

If exists at least a single number which added to the sum of its digits is equal to `n`, then `n` is a ***Junction Number***.

If there are not numbers which added to the sum of their digits are equal to `n`, then `n` is a ***Self Number***.

Given a positive integer `n`, implement a function that returns:

The string `"Self"` if `n` is a ***Self Number***. If `n` is a ***Junction Number*** an array, ordered descendingly, containing the numbers which generate `n`.

```js
junctionOrSelf(25) ➞ [17]
// If we add 17 to the sum of its digits...
// ...17 + 1 + 7 = 25
// 25 is a Junction Number

junctionOrSelf(818) ➞ [805, 796]
// If we add 805 to the sum of its digits...
// ...805 + 8 + 0 + 5 = 818
// If we add 796 to the sum of its digits...
// ...796 + 7 + 9 + 6 = 818
// 818 is a Junction Number

junctionOrSelf(7) ➞ "Self"
// 1 + 1 = 2
// 2 + 2 = 4
// 3 + 3 = 6
// No number added to its own digits is equal to 7
// 7 is a Self Number
```

As in example `#3`, the sum of the digits of a positive integer lower than 10 is equal to that same integer.

By the formal definition, a Junction number must have at least two other numbers that generate it, so that the Instructions are to be considered valid only for this specific challenge.
