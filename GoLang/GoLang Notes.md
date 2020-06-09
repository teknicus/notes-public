# GoLang Notes



[TOC]



### Why GoLang?

- Fast Execution
- Memory Garbage collection
- Simpler Objects
- Efficient Concurrency



### Introduction to GoLang

> In Compilation, Translation happens only once
> In Interpretation, Translation happens during execution

- Go is a compiled language but has some of the useful features of an Interpreted language
- Go is a Weakly Object-oriented  language. It does not use classes, only structs. No inheritance concepts

> Concurrency : In computer science, concurrency is the ability of different parts or units of a program, algorithm, or problem to be executed out-of-order or in partial order, without affecting the final outcome.

- Go implements concurrency with:
  - Goroutines
  - Channels
  - Select
- In Go, code is organized into packages
- Execution starts in the `main` package



### Variables

- Declaration :
  - `var x int`
  - `var x,y int`
  - `var x int = 100`
  - `var x = 100 //Auto assigns the datatype. Not ideal`
  - Short Declatation
    - `x := 100`
    - can be done only inside a function
- Types
  - `int`
  - `float`
  - `string`
- Type Declatations
  - Define Aliases
    - `type Celsius float64`
    - `type IDnum int`
    - Helps improve clarity and readability
    - 





