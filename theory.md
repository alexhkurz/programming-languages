## Summary of Some Theoretical Concepts

(under construction ... just a more or less random collection for now ... links to be added ... )

I list some theoretical concepts that will come up during the courses on Programming Languages and Compiler Construction. Some concepts, such as rewriting, normal forms, invariants, DFA and NFA, will be discussed in some detail, others will be only mentioned in passing to provide some general background. In each case, I will take care to explain how the theoretical concepts solve practical problems. 

Of course, this incomplete list is already way too long to treat everything in detail ... get in touch if you want to here more about any of the below ...

Programming Languages and Compiler Construction is related to many different areas of Computer Science and Mathematics:

- graph theory, 
- concurrency, transition system, 
- automata theory, finite state machine, DFA, NFA, regular expression, Kleene's theorem, ...
- computability, Turing machine, halting problem, decidability
- complexity theory, space and time complextity, Big O notation, ...
- lambda calculus, higher order functions, alpha and beta reduction/equivalence, 
- verification, Hoare logic, partial correctness, loop invariants, ...
- type theory, dependent types, propositions as types
- set theory
- universal algebra
- category theory
- logic, propositional logic, predicate logic, quantifiers, induction, proofs, theorem proving, ...
- rewriting, term-rewriting, graph-rewriting, ...
- semantics of programming languages

In particular, we will learn more about the following:

- relation: reflexive, symmetric, transitive, equivalence ... see [the lecture on discrete maths]().
- non-determinism, backtracking, ...
- invariants, ...
- termination, well-founded ordering, ...
- call by name, call by value, lazy evaluation, ...
- monad, 

- 2-dimensional syntax

- compositionality, ...

- terms, variables, equations

    Terms are built from operations. Finitely many rules are used to describe   infinitely many terms.
    For example, we defined numbers by two rules which can be written in [BNF]  (https://en.wikipedia.org/wiki/Backus–Naur_form) as

            num ::= 1 | num + 1

    Then we also extended numbers to form expressions using + and * by  adding, again in BNF,

            exp ::= num | exp + exp | exp * exp

    And then to "algebraic expressions", which also may contain variables, by   replacing the above with

            exp ::= num | exp + exp | exp * exp | x

    where x is ranging over a given set of "variables".

- rewriting, term-rewriting, confluence, termination, Church-Rosser, normal form: see [the lecture on ARSs]().

- syntax, semantics, soundness, completeness ... see [this lecture]() for details.

- abstract syntax

- syntactic sugar ... [wikipedia](https://en.wikipedia.org/wiki/Syntactic_sugar)

    Syntactic sugar refers to notational conventions that make syntax easier to digest for human consumption. For example, in the language of arithmetic defined by 

        num ::= 1 | num + 1
        exp ::= num | exp + exp | exp * exp
        
    the two occurrences of `+` refer to two different operations, the first is successor, the second addition. But we use the same notation to ease reading and calculation in concrete examples.

- formal system

    As a generic term, the notion "formal system" does not have a precise   definition. The idea is that a formal system is defined by rules that     specify how to manipulate symbols in an effective way, that is, in a way    that can be carried out by a machine. Examples inlcude large parts of  mathematics or games such as chess. Indeed, by definition, formal systems    coincide exactly with what can be implemented on a computer. Particular    formal systems that we will study, will have precise definitions. Our  first example is a formal language for arithmetic.
