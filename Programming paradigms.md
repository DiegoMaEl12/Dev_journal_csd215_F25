# Course notes

## Programming paradigmns overview

- Why programming paradigms?
  - Manage complexity
  - write better code
  - Avoid non-essential complexity (the things we as a programmers add by not using the correct tools, or writing messy code)
  - We should create code that is
    - Simple (not a lot of comments explaining complex stuff)
    - Reusable
    - Readable
    - Easy to change

### **Programming paradigm definition**
\
An approach to programming using a specific, constrained set of techniques with the goal of making it easier to write, read, maintain, andn reuse complex software.
\
Examples: 
- Structured
- Object Oriented Programming (OOP)
- Functional Programming
- Procedural
- Logical
- Reactive
\
Programming languages usually support one or more paradigms.\
Language features to make wrriting in the style of a paragigm simpler.
- Add features that provide simple ways yo write paradigmatic code
- Purposely leave out features that work against paragmatic constraints
\
**Structured Programming**
- Use flow-of-control programming structures like
  - Conditionals
  - Loops
  - Function calls and returns
  - Try/catch
  - ... more
 
- Before these, there was goto
  - jump to anyline of code using line number or label
 - <img width="629" height="191" alt="image" src="https://github.com/user-attachments/assets/bc80e56b-78db-4b98-b40f-acff5e516f2e" />
- Structured programming defined a set of structures that are known to be usefull before with gotos
- But now we don't have all the power associated with GoTo statements, because the code can become complex and messy really quick.

**Object Oriented Programming**
- Everything is an object.
- Programs are written using a set of related objects that can communicate with each other to accomplish tasks.
  - Classes and objects:
    - Related state: instance variables
    - Behaviour: methods
  - Code among sub-types can be shared:
    - Hirerarchies
    - Inheritance
  - Calling the same method on different sub-types may result in different behaviour
    - Polymorphism
  - Write code using a related set of objects (class instances) that call each other's methods.
\
Before OOP:
\
- It was possible to write code in an OOP style, but it required conscious discipline
  - keep methods and related instance variables in same file by convention
  - Must manually provide this parameter to methods
  - Use function parameters to accomplish inheritance
  - **None of these are enforced or enables by the language**
- That's how OOP languages help
- Because there is a lot of syntax built into the language to enforce those kinds of things
- Allowing programmers to tackle harder problems without drowning in complexity
- The language will guide you through the specifics of OOP, letting you don't focus on OOP complex concepts, but just write code with what the language let you do.
\
**Shines when there are many things, each with a fixed set of operations**
- Adding/ removing things is easy: adding/removing classes
- Adding/removing operations is harder: adding/removing methods on many classes.
\
**Functional Programming**
- Writing code using pure functions as much as possible, with techniques for making side effects easier to manage
- Pure functions are the ones that depends only on their parameters, and has no side effects
- A side effect is anything a function does other than return a value
  - print to screen
  - Send email
  - update database
  - update instance variables
- Side effects cause problems when you want a value but not a side effect
- It is hard to write a functional application with just pure functions
- In functional languages, there are features that help to enforce the use of only pure functions
- Data should be immutable, and changes to data shoud be represented by creating new values with those changes applied
- Two kinds of FP languages:
  - **(more or less pure) functional languages**: Clojure, common Lisp, racked, scheme, elixir, erlanf, f#, haskel, OCaml
  - **languages that support 'functional style**': C++, C#, Go, Java, JavaScri[t, Kotlin, PHP, Python, Rust, Scala, Swift.
\
- First class functions
- Functinos are values
- so they can be:
  - assigned to variables
  - Passed arguments to other functions
  - Returned from functions
 - Higher order functions: any function that accepts as a parameter or return as a value another function
\
**Shines when there are many operations, that work with a fixed set of things** 
- Adding/removing operations is easy: add/remove functions
- Adding/removing things is harder: add/remove parameters on many functions.










