# Loops

Loops are used to create loop in your code. JavaScript provides 3 types of loops and they are

- For
- While
- Do while

## For

One of most used loops of all time.

```javascript,editable
// for(declaration; condition; increment)
for(let i=0; i<7; i++) {
  console.log("i = ", i)
}
```

Let's understand it's syntax.

- `for`: This is the keyword (reserved word) used to define.
- `let i=0` or **declaration**: These can further be divided in 2 types
- `i<7` or **condition**: This is the keyword (reserved word) used to define.
- `i++` or **increment**: These represent the body of the `if` and `else`. when the condition is true, code withing if block will get execute or the code with within `else` block will get executed.

```javascript,editable
// Is it a valid loops
for(let i=0; i<7;) {
  console.log("i = ", i)
}
// Don't run it.
```

## While

The `while` keyword can be used to run a loop while a condition is `true`.

```javascript,editable
let i=0;
while(i<7) {
  console.log("i = ", i)
  i++;
}
```

Let's understand it's syntax.

- `while`: This is the keyword (reserved word) used to define.
- `let i=0` or **declaration**: These can further be divided in 2 types
- `i<7` or **condition**: This is the keyword (reserved word) used to define.
- `i++` or **increment**: These represent the body of the `if` and `else`. when the condition is true, code withing if block will get execute or the code with within `else` block will get executed.

## Do while

The `do` keyword is used to start the body of the loop and `while` keyword is used at the end to declare the condition.

```javascript,editable
let i=0;
do {
  console.log("i = ", i)
  i++;
}while(i<7);
```

Let's understand it's syntax.

- `do`: This is the keyword (reserved word) used to define.
- `let i=0` or **declaration**: These can further be divided in 2 types
- `i<7` or **condition**: This is the keyword (reserved word) used to define.
- `i++` or **increment**: These represent the body of the `if` and `else`. when the condition is true, code withing if block will get execute or the code with within `else` block will get executed.
- `while`: This is the keyword (reserved word) used to define.

As you can see the condition is checked at the end, the content of the loop will always execute at-least once (even when the condition is false).
