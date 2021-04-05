
# Course Materials

(under construction ... currently being adapted for 2021 ... subject to change)

**Quick Links**: [Installing Haskell](https://hackmd.io/@alexhkurz/Hk86XnCzD) ... [BNFC](BNFC-installation.md) ... [Haskell projects](haskell-projects.md) ... [videos](videos.md)

### What we (will) have learned

To clarify the learning outcomes: What we have learned in [Part 0]() and [Part 1](what-we-have-learned-1.md) and [Part 2](what-we-have-learned-2.md) and [Part 3](what-we-have-learned-3.md) and [Part 4](what-we-have-learned-4.md) and [Part 5](what-we-have-learned-5.md) and [Part 6](what-we-have-learned-6.md).

### Part 0: Functional Programming (0)

[First Haskell Steps](https://hackmd.io/@alexhkurz/SJgHGZ_nw)

### Part 1: A Calculator in Haskell (2)

In this part, we will learn about parsing and write our first interpreter for a programming language that only has arithmetic expressions.

- **A Calculator in Haskell (Abstract Syntax)** ... [notes](https://hackmd.io/@alexhkurz/SyxKCkR6U)
- **A Calculator in Haskell (Concrete Syntax)** ...  [notes](https://hackmd.io/@alexhkurz/HJVtVl068)
- [Assignment 1](assignments.md): Haskell, recursion over abstract data types, a calculator.

Videos:
  - [gcd and Euclid's algorithm](https://youtu.be/ZcJMj0antos)
  - [Recursion over algebraic data types in Haskell](https://youtu.be/2YLfJvOtLwA)
  - [Precedence levels in CFGs](https://youtu.be/jf1xhZSpCvg)  
  - [Uniqueness of parse trees](https://youtu.be/3ZLkPwB_c9g) 

In this part we only look at small grammars. Writing a grammar for a mainstream programming language is a difficult, but very interesting task. It contains important lessons about software engineering and even the scientific method in general. We will look at this in detail in next semester's class on Compiler Construction. (If you are interested in a quick preview of the assignment on parsing, we will start from this [grammar for a fragment of C++](https://github.com/alexhkurz/compiler-construction-2021/blob/master/Sources/Cpp/Cpp.cf) and then add the features as described in this [language specification](http://www.grammaticalframework.org/ipl-book/assignments/assignment1/assignment1.html).)

### Part 2: Semantics of Programming Languages (2)

- [What is Abstraction?](https://hackmd.io/@alexhkurz/HJONiNfCw)
- [Operational and Denotational Semantics](https://hackmd.io/@alexhkurz/Hkf6BTL6P) 
- Computation as Proof [](https://hackmd.io/@alexhkurz/SkYfWCU6w) 
- Normalisation by Evaluation [](https://hackmd.io/@alexhkurz/BkQ7VEp_r)
- Optional: [Adding Variables]()

### Part 3: Lambda Calculus (3)

- **Syntax of Lambda Calculus** ... [video preview](https://youtu.be/D0kH1BpNr14) ... [notes](https://hackmd.io/@alexhkurz/S1D0yP8Bw) ... video reviews on parsing [1](https://youtu.be/eYstx7uuE6c) and [2](https://youtu.be/yls1NEUlzZA)
- [Variables, Binding, Scope and Substitution](https://hackmd.io/@alexhkurz/SkQzDC6n7)
- **Semantics of Lambda Calculus** ...[video preview](https://youtu.be/h4aT42t7v9c) ... [notes](https://hackmd.io/@alexhkurz/H1e4Nv8Bv) ... [video review](https://youtu.be/for3Meg1Lbc)
- [Assignment 2, Part 1](assignments.md): An interpreter for lambda calculus. The [Work Cycle](https://github.com/alexhkurz/programming-languages-2020/blob/master/Lab1-Lambda-Calculus/README.md). I use scripts like [lambdanat](lambdanat) to automate part of the work cycle. Feel free to adapt to your own needs.
- **Typed Lambda Calculus** ... [notes](https://hackmd.io/@alexhkurz/S1Sopqo6w) ...
- **Polymorphism** ... [to be written](https://hackmd.io/IdPfOHUBQnW2wLLqcvKAbQ)

Videos:
  - [Syntax of Lambda Calculus](https://youtu.be/D0kH1BpNr14)
  - [Parsing Lambda Calculus Expressions 1](https://youtu.be/eYstx7uuE6c)
  - [Parsing Lambda Calculus Expressions 2](https://youtu.be/yls1NEUlzZA)
  - [Operational Semantics of Lambda Calculus](https://youtu.be/h4aT42t7v9c)
  - [Reducing Lambda Expressions](https://youtu.be/for3Meg1Lbc). While watching this video, do the reductions in your own text editor. Frequently stop the video and guess the next step. Work along, it is all just the beta rule.
  - [Extensions of lambda-calculus](https://hackmd.io/@alexhkurz/rJEeYqZtw) ... video review [Fixed Point Combinator](https://youtu.be/XvDOwbSh3xE)



### Part 4: Rewriting (2)

Lectures:
- [Rewriting: Examples](https://hackmd.io/@alexhkurz/rkzITG4nD). Abstract Reduction Systems: [Definition and Examples](https://hackmd.io/@alexhkurz/BJfvFVK8v)
- [Confluence and Normal Forms](https://hackmd.io/@alexhkurz/r1hRZaG8v).
- [Termination](https://hackmd.io/@alexhkurz/BJoZF44Iw)
- [Invariants](https://hackmd.io/@alexhkurz/BkMoUhXvD).

Supplementary materials:
- [Discrete Mathematics: Relations](https://hackmd.io/@alexhkurz/SJ1cc-dDr)
- Video on [merge sort](https://youtu.be/W2CknJGgzr0)
- [Exercises](https://hackmd.io/@alexhkurz/BJ23jmpIw)

### Part 5: Imperative Programming (1)

An interpreter for an imperative programming language.


### Part 6: Verification (2)

There are many approaches to software reliability. You will be familiar with testing, which is part of the wider area of program analysis. In this section of the course we will look at program verification.

- [Hoare Logic](https://hackmd.io/Df57tnuCSGaW8wqqsl57FQ) ... [Exercises](https://hackmd.io/@alexhkurz/rkhVZNzjH)



---

## Bonus Lectures

In previous years, this course was more theoretical and less focussed on Haskell. I put here some material I dropped for 2020. I hope to bring back some of it for 2021.

#### Logic and Reasoning 

- [Rules of logic](https://hackmd.io/xJ8NOiK4S5qnYvEI85bHig)
- [Induction and Equational Reasoning](https://hackmd.io/02w2FuLsT_uKYQxkPSdvtw)
- [Theorem Proving](https://hackmd.io/JrBBURefROGD1xMN44Zivw)

#### Universal Algebra and Category Theory

 - Abstract Data Types
 - What is Structure?
 - Structure Preserving Maps
 - Universal Properties

