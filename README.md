## Variables & Programming-like Features

The language supports basic programming constructs to make documents dynamic and reusable. These features allow defining variables, creating functions, using conditions, and iterating over data.

---

### Variable Declaration

Variables are declared using the `let` keyword.
A variable can store text, numbers, or formatted document elements such as headings or styled content.

A semicolon at the end is optional.

**Syntax**

```
let varname = value
```

---

### Constants

Constants are defined using the `const` keyword.
Once declared, their values cannot be modified.

**Syntax**

```
const varname = value
```

---

### Examples

```
let title = "Introduction to Computer Networks"
let section_heading = {=Important Concepts}
let bold_note = {*This text is important*}
let count = 5;

const version = "1.0"
const MAX_ITEMS = 10
```

Variables can contain normal values (strings, numbers) or formatted blocks such as headings and styled text.




### Expressions

Expressions allow performing computations or combining values.

**Syntax**

```
let total = price * quantity
let area = length * width
let message = "Total pages: " + page_count
```

---

### Functions

Functions allow reusable blocks of logic.
Functions are defined using the `fn` keyword.

**Syntax**

```
let add = fn(a, b){
    return a + b
}
```

---

### Function Arguments

Functions can take one or more arguments.

**Syntax**

```
let greet = fn(name, role){
    return "Hello " + name + ", your role is " + role
}
```

---
### Function Call

Once a function is defined, it can be called by using the function name followed by parentheses containing the required arguments.

**Syntax**

```
function_name(argument1, argument2)
```

**Example**

```
let result = add(5, 10)

let message = greet("Aman", "Maintainer")
```


### Function Return

Functions return values using the `return` keyword.

**Syntax**

```
let square = fn(x){
    return x * x
}
```

---

### Conditional Blocks

Conditional statements allow executing blocks of content based on conditions.

**Syntax**

```
if(score > 90){
    Grade = "A"
}
else if(score > 75){
    Grade = "B"
}
else{
    Grade = "C"
}
```

---

### Loops

Loops allow repeating a block of content multiple times.

**Syntax**

```
for(let i = 0; i < 5; i = i + 1){
    Print item number {i}
}
```

---

### Iteration Over Collections

You can iterate over arrays or collections of blocks.

**Syntax**

```
for(let block_var in all_blocks){
    render(block_var)
}
```

---

## Text Formatting

This section explains the basic text formatting syntax supported in the language. These formatting tools help highlight or structure text within a document.

---
### All in one place

| Feature               | Syntax         | Output                                        |
| --------------------- | -------------- | --------------------------------------------- |
| Bold                  | `*text*`       | **This project simplifies document creation** |
| Italic                | `_text_`       | *Readable and clean formatting matters*       |
| Underline             | `__text__`     | <u>Important note for contributors</u>        |
| Strikethrough         | `~text~`       | ~~This sentence is outdated~~                 |
| Monospace / Code Font | ` ```text``` ` | `int main() { return 0; }`                    |
| Inline Code           | `` `text` ``   | Use `gcc program.c` to compile                |
| Superscript           | `^text^`       | The area of the square is m²                  |
| Subscript             | `^^text^^`     | H₂O is my favourite drink                                          |

----

- ### Bold

Use `*text*` to make text **bold**.

**Syntax**

```
*This text is bold*
```

**Output**

**This text is bold**

---

- ### Italic

Use `_text_` to make text *italic*.

**Syntax**

```
_This text is italic_
```

**Output**

*This text is italic*

---

- ### Underline

Use `__text__` to underline text (double underscore).

**Syntax**

```
__This text is underlined__
```

**Output**

<u>This text is underlined</u>

---

- ### Strikethrough

Use `~text~` to strike through text.

**Syntax**

```
~This text is strikethrough~
```

**Output**

~~This text is strikethrough~~

---

- ### Monospace / Code Font

Use triple backticks to display text in a monospace (code-style) font.

**Syntax**

````
```printf("Hello World");```
````

**Output**

`printf("Hello World");`

---

- ### Inline Code

Use single backticks for short pieces of code within a sentence.

**Syntax**

```
Use `gcc main.c` to compile the program.
```

**Output**

Use `gcc main.c` to compile the program.

---

- ### Superscript

Use `^text^` to write superscript text.

**Syntax**

```
Area is measured in m^2^.
```

**Output**

Area is measured in m<sup>2<sup>.

---

- ### Subscript

Use `^^text^^` to write subscript text.

**Syntax**

```
H^^2^^O is my favourite drink.
```

**Output**

H<sub>2</sub>O is my favourite drink.

---
