# codingclub

The first rule of Coding Club is you talk to everybody about Coding Club. We'll put all of our work here for others to see and build from. The short link to this page is [http://is.gd/codingclub](http://is.gd/codingclub)

Before you get started understanding how to write code, try some of the fantastic and fun exercises at code.org: [Hour of Code](https://code.org/learn) and [Code Studio](https://studio.code.org/). Generally you should be able to do Code Studio 1-3 before you start writing code yourself.

A glossary of terms
-------------------

**Statement** A single instruction that tells the computer to do something.
```Javascript
print('Hello World');
```

**Syntax**: Rules that say what is a valid statement and what isn't. Usually this means where punctuation goes (for example, the semicolon ; after 'Hello World' and the quote in 'Hello World')

**Variable**: A "box" in which you can store a single thing - like a number or text or an object.
```Javascript
var myFavoriteFlavor = 'Pistachio';
```

**Literal**: A number or string.
```Javascript
var stringLiteral = 'This is a test';
var numberLiteral = 6;
```

**Function**: A group of statements that take some arguments and can return a value.
```Javascript
function addThese(a,b) {
  return a + b;
}
print('3 + 5 is ' + addThese(3,5));
```

**Object**: A group of variables and functions that share a "box" called **this** in Javascript.
```Javascript
var myObject = {
  name: 'Advent School',
  sayMyName: function () {
    print(this.name);
  }
}
```

**Loop**: A group of statements that run over and over again until some test fails. There are generally two types of loops - while loops (run while this is true) and for loops (run some number of times).
```Javascript
// This will print the numbers from 0 to 9 (not 1 to 10!)
for (var i = 0; i < 10; i++) {
  print(i);
}

// This will print he numbers from 1 to 10 (because i = i + 1 happens before printing)
var i = 0;
while (i < 10) {
  i = i + 1;
  print(i);
}
```

**Program** A collection of statements, functions, objects, and literals that are executed by the computer from top to bottom.

<hr/>
<sub>Note - I've taken some liberties here with inexact descriptions (like object) to make things simpler. Don't hold it against me. Or fix it, either way.</sub>
