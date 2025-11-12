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



## Data Calculations and Actions

- Calculations: pure functions
- Actions: impure functions
- We want to leave actions as simple as possible


#### ACTION definition: "an instruction for which the time and order in which it is called matters"
  - they have side effects (calling them causes some change in a system)
  - You have to be careful with actinos
  - But the program need actions, there can't be a program with ONLY pure functions
- Techniques to handle actions:
  - Ways to safely change state over time
  - Ways to guarantee ordering
  - Ways to ensure actions happen only once
- DATA and CALCULATIONS don't matter when they are called
  - because they don't change things in the system, just accept a value and return a value
#### DATA definition: "Facts about events"
  - Data does no work
  - Types of data: Immutable (cannot be changed after is initialized) & Mutable (can change after is initialized)
  - Functional paradigm tries to work as much as possible with IMMUTABLE DATA
  - Techniques for data:
    - Organize data for efficient access
    - Disciplines for storing data
    - Principles for capturing what is important using data
#### CALCULATIONS definition: "Computation from input to output"
  - Have no side effects
  - Called pure funtions
  - The same calculation performed on the same input ALWAYS produces the same output
  - Setters are not pure functinos (because they actually change the state of a variable)
  - Getters ARE pure functions
  - Functional programming prefer calculations over actions as much as possible
  - Referential transparency: a function is referentially transparent if a call to the function could be replaced by the value returned by the function without changing the program
  - **Calculations are referentially transparent.**
  - Techniques for calculations:
    - Functional programmers prefer calculations over actions bbecause:
    - Calculations are composable
    - IDEs can automatically analyze calculations and check for correct usage
    - Calculations are much easier to test over actions.
   

#### Data > Calculations > Actions

All three categories are useful but:
- Prefer **DATA** over both, calculations and actions
  - **IMMUTABLE** data over mutable data
- **CALCULATIONS** over actions
- **ACTIONS** should be as stupid as possible, so that just by looking at the code you can tell if it is doing the right thing or not\

-- Simpler actions, data and calculations can hide in complex actions. -- 


### Functional core & Imperative shell

- <img width="526" height="410" alt="image" src="https://github.com/user-attachments/assets/0d0c95d9-862b-4046-82ff-e05f515fe41f" />
- Functional core:
  - All immutable data and pure functions
  - App logic goes here
  - No direct reference to 'messy outside' (files, databases, network, ...)
 
- Imperative shell
  - Minimal logic (delegated to functionsl core)
  - Sequences operations (what order should things happen in?)
  - Interacts with 'messy outside world)
  - **Coordinates data between shell and core.**

### Records, data classes, Enums and interfaces

#### Using Records / data classes to represent data

- A java racord can be used to represent a data type
- A type that simply holds information
- There are no methods in there

#### ENUMS

- Represent a specific fixed set of values
- Better than strings because the compiler helps you detect invalid usages or values

#### Sealed interfaces

- It is the same as a normal interface
  - it will define some methods, usually only the signature of them
  - So that all the classes that implement it, must have an implementation for each of the methods declared in the interface
 
- A sealed interface allows you to explicitly define which classes can implement the interface
  ``public sealed interface name { record Type1() implements name{}; record Type2() implements name {}; }``
- sealed interfaces can define only methods or nested data types (like records)
- You can define class variables in interfaces, but not instance variables
- you can define class members
- Usually the different types on sealed interfaces have completely different methods themselves
  - So it is common to only define data types like records in sealed interfaces
- A type that has a predefined set of subtypes

### Inputs and outputs

- **Input**: external information that a function uses in its computations
  - Can be arguments
  - Global variables
  - input from the user
- Explicit input: **Parameters**
- Implicit input: all the other inputs, a function might have
<br>

- **Output**: the information that leaves a function or effects a function causes
  - Returned values
  - writting to a file
  - Print to screen
  - store to a db
  - ... 
- Explicit output: the **returned** value itself
- Implicit output: All other side effects a function might have.
  - Everytime an input changes its value in some way, those are implicit outputs
  - You can have an explicit output value, but if the input, changes its value AND THEN returns the changed input, that's an explicit output and an implicit output (changing the input)
 

### Extracting calculations from actions

1. Identify portion of action that is a calculation and extract it into a separate subroutine
2. Identify new subroutine's implicit inputs and outputs
3. Convert implicits to explicits
   - First convert implicit outputs to return values
   - Then convert implicit inputs to parameters

- If we can't eliminate actions, improve them by -- Reducing implicit inputs and outputs as much as possible --
- Dependency inection: set the inputs to explicits, that way you are injecting the dependency to the method doing the job
- Loosely coupled functions
- 








