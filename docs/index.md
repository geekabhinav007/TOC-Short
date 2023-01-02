# Theory Of Computation

In theoretical computer science, the theory of computation is the branch that deals with
whether and how efficiently problems can be solved on a model of computation, using an
algorithm. The field is divided into three major branches: automata theory, computability theory
and computational complexity theory.

Automata theory is the study of `abstract` machines (or more appropriately, abstract 'mathematical' machines or systems) and the computational problems that can be solved using these machines. These abstract machines are called `automata`.

This automaton consists of

- states (represented by circles),
- transitions (represented by arrows).

> Uses of Automata: compiler design and parsing.

## Formal Languages

*Languages*: The languages we consider for our discussion is an abstraction of natural languages. That is, our focus here is on formal languages that need precise and formal definitions. Programming languages belong to this category.

*Symbols*: Symbols are indivisible objects or entity that cannot be defined. That is, symbols are the atoms of the world of languages. A symbol is any single object such as a, 0, 1, #, begin, or do.

### Basics of strings

A string or word over an alphabet $\sum$ is a finite sequence of concatenated symbols of $\sum$ .

*Length of a string* : The number of symbols in a string w is called its length, denoted by |w|.

*Example* : | 011 | = 4, |11| = 2, | b | = 1

### Alphabets

*Alphabets*: An alphabet is a finite, nonempty set of symbols. The alphabet of a language is normally denoted by $\sum$.

### Formal language

### Chomsky Classification of languages

### Languages and their relation

### Operations on languages

- Complement
- Reverse
- Union
- Intersection
- Difference
- Concatenation
- kleen * closure

![1](/image/1.png)
![2](/image/2.png)

### Closure properties of language classes

#### Kleen Star ($\sum$*)

It is an infinite set of all possible strings over all posible length over alphabet ($\sum$), `Excluding` $\lambda$

#### Kleen Positive($\sum$+)

It is an infinite set of all possible strings over all posible length over alphabet ($\sum$), `including` $\lambda$

> Where $\lambda$ is an null string.

## Finite Automata

### Deterministic Finite Automata

### Acceptance by Finite Automata

### Transition systems

### Non-Deterministic Finite Automata

### Equivalence of DFA and NDFA

### Moore and Mealy machines

### Equivalence of Moore and Mealy machine

### Minimization of Finite Automata

### Applications and limitations of Finite Automata

## Regular Grammar

### Regular grammars

### Regular expressions

### Algebraic method using Arden’s theorem

### Equivalence of Finite Automata and Regular expressions

### Properties of regular languages

### Pumping lemma

## Context Free Languages

### Introduction

### Leftmost and Rightmost derivation trees

### Ambiguity

### Simplification of context free grammar

### Normal forms

#### Chomsky Normal Form

#### Greibach Normal Form

### Pumping lemma2

## Pushdown Automata

### Description and definition

### Acceptance by Push Down Automata

### Equivalence of Push Down Automata and context free grammars and languages

## Context Sensitive Language

### Context Sensitive language

### Model of linear bounded automata

### Relation between linear bounded automata and context sensitive language

## Turing Machines

### Definition and Model

### Representation of Turing Machine

### Design of Turing Machine

### Variants of Turing Machine

### Decidability and recursively enumerable languages

### Halting problem

### Post correspondence problem
