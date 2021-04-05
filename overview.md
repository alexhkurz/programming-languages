## Overview 

Together with Compiler Construction this course is the first one of a pair of courses in which we are going to learn the basic theory and practice of designing and implementing a programming language.

#### Summary

The course will have a practical and a theoretical component.

- *The theoretical component* will teach some of the mathematics underpinning the design of programming languages. These will include some of the basics of logic, rewriting, ordered structures, universal algebra, and category theory (type theory will be deferred to next semester's course on compiler construction). Just enough theory to help the writing of interpreters and to gain an outlook on some of the questions guiding programming languages research. I made a [list of theoretical concepts](theory.md) that appear regularly in programming languages blogs and which we will learn about something. 

- *The practical component* will be about building interpreters for small programming languages. We will start with a calculator, that is, an interpreter for the language of high-school arithmetic, then go on to the smallest proper programming language known as lambda calculus. Lambda calculus provides variables and functions and other programming languages can be seen as extensions of lambda calculus. Thus, once we have an interpreter for lambda caclulus, we will approximate more realistic programming languages by extending lambda calculus: conditionals, recursion, data types, assignment, while loops, addresses (pointers), memory allocation, dereferencing, arrays. There will be room for invention and adventure if you feel like it. But there will also be many guided exercises.

#### Detailed Description

The course is divided in a practical and theoretical component. 

On the practical side, students will learn 
- the basics of Haskell
- how to build interpreters in Haskell for small programming languages of increasing complexity:
  - numbers, addition, multipliciation, fractions, ...
  - calculator
  - lambda-calculus
  - a small functional programming language
  - a small imperative programming language

This will include the basics of parsing and the use of a parser generator. The aim is to treat programming languages that only have a small number of features. We will see that these methods scale in next semester's course on compiler construction.

On the theoretical side, students will learn the fundamental ideas of

- lambda calculus
- operational and denotational semantics    
- term rewriting   
- invariants and well-founded orders     
- program verification and Hoare logic    
- structural induction, universal algebra, and category theory    

On the way, students will encounter different programming languages such as Dafny and Haskell and , if time permits, Lisp (Scheme), theorem provers such as Isabelle, dependently typed programming languages such as Idris as well as programming concepts such as algebraic data types, recursion, variable binding, polymorphism, and more.

During the course we will pay special attention to compositionality. For example, from a software engineering point of view, we see compositionality in the division between syntax and semantics, or, parsing and interpretation; the programming technique of recursion over abstract syntax trees is another incarnation; in program verification, we will separate termination from partial correctness, which will allow us to give a compositional calculus for program verification known as Hoare logic.


