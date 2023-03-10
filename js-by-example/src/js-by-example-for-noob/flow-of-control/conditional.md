# Conditionals

Conditionals are used to create branches in the flow of your code. JavaScript provides 2 types of conditional they are

- If/else
  - Ternary
- switch

## If / else

If/else are one most used conditions statement. Let's have a look.

```javascript,editable
if (7 % 2 === 0) {
  console.log('7 is even')
} else {
  console.log('7 is odd')
}
```

Let's break it down just like did to functions.

- `if`: This is the keyword (reserved word) used to define.
- `(7 % 2 === 0)`: These can further be divided in 2 types
  - `7 % 2 === 0`: These are called **parameters**, here we have 2 of them separated by a **,**. These are also know as **inputs**
  - `()`: All the **parameters** are wrapper by them.
- `else`: This is the keyword (reserved word) used to define.
- `{}`: These represent the body of the `if` and `else`. when the condition is true, code withing if block will get execute or the code with within `else` block will get executed.

```javascript,editable
// You can have if without else
if (8 % 4 === 0) {
  console.log('8 is divisible by 4')
}
```

You don't always have to use `else`

What if, we want to create more than 2 branches. Well you can use `else if`

```javascript,editable
const duck = 'blue';
if (duck === 'yellow') {
  console.log('Rubber ducky')
} else if (duck === 'brown') {
  console.log('Live duck')
} else {
  console.log('Ive never seen a blue duck before.')
}
```

Here each condition will be checked till atleast anyone of them checks out. And if all of them are fails, then the else section will be executed.

### Ternary Operator

Ternary Operator is short hand notation for if/else.

```javascript,editable
const true_value = true ? "I am True" : "I am False";
const false_value = false ? "I am True" : "I am False";

console.log("true_value = ", true_value);
console.log("false_value = ", false_value);

```

## Switch

Switch statements are conditionals that may have many branches (like if / else if).
Switch statements are more performant but less flexible.

<!-- Simple Example -->

```javascript,editable
// a simple switch statment
const fruit = 'banana'
switch (fruit) {
  case 'blueberry':
    console.log('blue')
    // everything after the true case executes
    // use 'break' if you aren't returning a value
    break;
  case 'banana':
    console.log('yellow')
    break;
  default:
    console.log('not blue, yellow or red')
}
```

<!-- Example without break -->

```javascript,editable
// a simple switch statment
const fruit = 'banana'
switch (fruit) {
  case 'blueberry':
    console.log('blue')
    // everything after the true case executes
    // use 'break' if you aren't returning a value
    break;
  case 'banana':
    console.log('yellow')
    break;
    // multiple cases can resolve to the same branch
  case 'apple':
  case 'raspberry':
    console.log('red')
    break;
  default:
    console.log('not blue, yellow or red')
}
```
