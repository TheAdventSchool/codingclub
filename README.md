# codingclub

A glossary of terms
-------------------

**Statement** A single instruction that tells the computer to do something.
```Javascript
print('Hello World');
```

**Syntax** Rules that say what is a valid statement and what isn't. Usually this means where punctuation goes (for example, the semicolon ; after 'Hello World' and the quote in 'Hello World')

**Variable** A "box" in which you can store a single thing - like a number or text or an object.
```Javascript
var myFavoriteFlavor = 'Pistachio';
```

**Function** A group of statements that take some arguments and can return a value.
```Javascript
function addThese(a,b) {
  return a + b;
}
print('3 + 5 is ' + addThese(3,5));
```

**Object** A group of variables and functions that share a "box" called **this** in Javascript.
```Javascript
var myObject = {
  name: 'Advent School',
  sayMyName: function () {
    print(this.name);
  }
}
```

<hr/>
<sub>Note - I've taken some liberties here with inexact descriptions (like object) to make things simpler. Don't hold it against me. Or fix it, either way.</sub>
