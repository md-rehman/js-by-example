# Comparison & Logical Operators

The previous page looked complicated because of a phenomena called information overload. And to deal with that we have break the problem down. So, let me do that for you.

- [Logical](#logical)

  - NOT (`!`)
  - OR (`||`)
  - AND (`&&`)

- [Comparison](#comparison)

  - Equal to (`==` & `===`)
  - Not Equal to (`!=` & `!==`)
  - Less than and Less than equal to (`<` & `<=`)
  - Greater than and Greater than equal to`>` & `>=`

> NOTE:
> There was specific reason why I overloaded you with that much information in the last page. Because in real-life you'll only see code like that, actually even worse than that. The key is not get over-whelmed but go line-by-line. Identify what you know, and predict the unknown.

## Logical

If you're aware of the terms like _truth table_, _logical gate_. Then next 3 operator will be self explanatory to you. If not, then don't worry they are very simple (and important).

### NOT (`!`)

Let's look only at the **NOT(`!`)** operator.

```javascript,editable
console.log('!true = ', !true);
console.log('!false = ', !false);
```

Did you get it?
If not, try reading it out **!true** => **NOTtrue**. Meaning if it is not `true`, then it must be `false`. Therefore,
If you put `!` before `true`, it makes it `false` and vice-versa.
But that's for boolean, how about numbers?
Try guessing the output before running the example.

```javascript,editable
console.log('!7 = ', !7);
console.log('!false = ', !0);
```

Did you get it?
This is happening because in javascript every value is either [Truthy](https://developer.mozilla.org/en-US/docs/Glossary/Truthy) or [Falsy](https://developer.mozilla.org/en-US/docs/Glossary/Falsy). You can either play with code and figure out, or read the mentioned link.

> Remember all the [Falsy](https://developer.mozilla.org/en-US/docs/Glossary/Falsy) values, all the other value should be [Truthy](https://developer.mozilla.org/en-US/docs/Glossary/Truthy).

Before proceeding with the rest of [Logical]() operators, we'll understand the [Comparison]() operators.
