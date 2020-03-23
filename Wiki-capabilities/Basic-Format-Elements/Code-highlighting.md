[[_TOC_]]


## Introduction

Highlight suggested code segments using code highlight blocks. To indicate a span of code, wrap it with three backtick quotes (```) on a new line at both the start and end of the block. 

Within a markdown file, text with four spaces at the beginning of the line automatically converts to a code block. 

To indicate code inline, wrap it with one backtick quote (`). 

## Example - block: 

\```
$ sudo npm install vsoagent-installer -g  
\```


## Result - block:

```
$ sudo npm install vsoagent-installer -g  
```

## Example - inline:
To install the Microsoft Cross Platform Build & Release Agent, run the following: \`$ sudo npm install vsoagent-installer -g\`.

## Result - block:
To install the Microsoft Cross Platform Build & Release Agent, run the following: `$ sudo npm install vsoagent-installer -g`.



## Language identifier

Set a language identifier for the code block to enable syntax highlighting for any of the [supported languages](http://highlightjs.readthedocs.io/en/latest/css-classes-reference.html#language-names-and-aliases). 

### Syntax
\```  language
code
\```

### Additional examples

#### Javascript
\``` js
const count = records.length;
\```

``` js
const count = records.length;
```

#### C#
\``` csharp
Console.WriteLine("Hello, World!");
\```

``` csharp
Console.WriteLine("Hello, World!");
```

