# Haskell 101

## What is Haskell?

Haskell is a statically-typed, purely functional programming language. It is named after the mathematician and logician Haskell Curry. Haskell is renowned for its elegant and concise code that emphasizes a declarative and pure functional programming style.

## Why Haskell?

Haskell is an excellent choice of programming language for many projects due to its purely functional paradigm, strong type system, and expressive nature. With its emphasis on immutability and absence of side effects, Haskell allows developers to write more predictable and maintainable code. Its type inference capabilities and powerful type system catch errors at compile-time, enhancing code safety while reducing the need for explicit type annotations. The language's lazy evaluation supports efficient handling of infinite data structures and enables better performance optimization. Haskell's concurrency and parallelism support, coupled with its elegant abstractions and growing ecosystem, make it suitable for a wide range of applications. However, adopting Haskell might require some initial learning investment for developers not familiar with functional programming, and its limited adoption in comparison to mainstream languages could influence resource availability and job opportunities. Nevertheless, for projects that benefit from its functional nature and value formal proofs and verification, Haskell can be a highly rewarding and productive choice.

## How to install Haskell?

Haskell can be installed on most platforms using the [Haskell Stack Platform](https://docs.haskellstack.org/en/stable/). For more information, see the [Haskell Wiki](https://wiki.haskell.org/Haskell). In Visual Studio Code, you need to install extension named haskell and haskelly.

## How to Initialize Haskell Using Stack?

To initialize a new Haskell project, run the following command in the terminal:

```

stack new <project-name> <template-name>

```

where `<project-name>` is the name of the project and `<template-name>` is the name of the template to use. For example, to create a new project named `hello-world` using the `simple` template, run the following command:
For example, if you want to create a simple "Hello World" program using stack and template called
`simple`, then use this command:

```

stack new hello world --bare -t simple
cd./hello/ && code. # open with Visual Studio Code or any other editor of your choice

```


