# Lab 2 - Human Bingo
## CodeSandBox
[Human Bingo CodeSandBox](https://codesandbox.io/s/lab2-humanbingo-s1yw15)

## JS-feature ES6
### Feature: Array find()

The find() method returns the value of the first array element that passes a test function.

This example finds (returns the value of ) the first element that is larger than 18:

```ruby
const numbers = [4, 9, 16, 25, 29];
let first = numbers.find(myFunction);

function myFunction(value, index, array) {
  return value > 18;
}
```