# TypeScript
![typescript](https://github.com/danielurra/TypeScript/assets/51704179/f34e4b73-8bc3-4bd9-b1e1-c943a81c0f7b)<br>
In a syntactic sense TypeScript is a superset of JavaScript, so long as your JavaScript program doesn’t have any syntax errors then it is also a TypeScript program.<br>
It’s quite likely that TypeScript’s type checker will flag some issues with your code, TypeScript will still parse your code and emit JavaScript.<br>
TypeScript is a superset of JavaScript, this means that any valid JavaScript is automatically syntactically valid TypeScript.<br>
TypeScript brings object-oriented concepts such as classes and modules to JavaScript<br>
But TypeScript is so much more than a simple superset of JavaScript, because it adds some very useful functionality. <br>

TypeScript is four things:<br>

1) Programming language<br>
A language that includes all the existing JavaScript syntax, plus new TypeScript-specific syntax for defining and using types<br>

2) Type checker<br>
A program that takes in a set of files written in JavaScript and/or TypeScript, develops an understanding of all the constructs (variables, functions…​) created, and lets you know if it thinks anything is set up incorrectly<br>

3) Compiler<br>
A program that runs the type checker, reports any issues, then outputs the equivalent JavaScript code<br>

4) Language service<br>
A program that uses the type checker to tell editors such as VS Code how to provide helpful utilities to developers<br>
## TypeScript Playground website
https://www.typescriptlang.org/play?<br>
![typescript-playground](https://github.com/danielurra/TypeScript/assets/51704179/7a57be95-8f7a-496f-8290-3d2e4b0470fc)<br>
## Addition
Typescript code:<br>
```typescript
var x:number=10;
console.log(x);

function add(num1:number,num2:number):number{
return num1+num2;
}
console.log(add(5,2));
```
JavaScript code:<br>
```javascript
"use strict";
var x = 10;
console.log(x);
function add(num1, num2) {
    return num1 + num2;
}
console.log(add(5, 2));
```
