# kampanos-coding-guidelines

## Readable Code

Here are the basics core fundamentals for creating a readable code.
JavaScript coding guidelines

https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/JavaScript

Typescript coding guidelines
https://www.itwinjs.org/learning/guidelines/typescript-coding-guidelines/


### Variables
<p>
All variables must be camelCase and self-descriptive. It shouldn't be necessary to add a comment for additional documentation to the variable.  Boolean variables should have a verb as prefix:
</p>
<p>
  <img alt="variables example" src=".github/example.png" width="100%">
</p>

**Global Variables**
  
* A global JavaScript/Typescript variable is declared at the top of a project/file.
* A global JavaScript/Typescript variable is written in camelCase if it is mutable.
* A global JavaScript/Typescript variable is written in UPPERCASE if it is immutable.


### Functions
Like variables functions must be descriptive and should always have a verb as prefix:
* getSomething()
*	saveSomething()
*	handleSomething()

Use "async" "await", instead of “. then()” syntax whenever it's possible to make the code more readble.

<p>
  <img alt="variables example" src=".github/example6.png" width="100%">
</p>

This way it's easier to know the function purpose and also identify promises.

<p>
  <img alt="variables example" src=".github/example5.png" width="100%">
</p>

```
$ git checkout -b featureName main
```

## Single Responsibility Principle

A class, a component or a function should have only __one__ responsibility.
</br>
Entities that have more than one responsibility should be split into different independent entities.
</br>
Independent and isolated entities its easier for:

*	Code reusability
*	Refactoring
*	New implementations
*	Automated tests
*	Less bugs/easier to isolate and fix bugs

### Wrong approach
In the code below the getUserTimestamps() function has too many responsabilities.
<p>
  <img alt="variables example" src=".github/example9.png" width="100%">
</p>



<p>
  <img alt="variables example" src=".github/example4.png" width="100%">
</p>


<p>
  <img alt="variables example" src=".github/example5.png" width="100%">
</p>


<p>
  <img alt="variables example" src=".github/example6.png" width="100%">
</p>


<p>
  <img alt="variables example" src=".github/example7.png" width="100%">
</p>
