[TOC](index.md) | [Formal Languages](formal.md) | [Finite Automata](finite.md) | [Regular Grammar](regular.md) | [Context Free Languages](contextF.md) | [Pushdown Automata](pushdown.md) | [Context Sensitive Language](contextS.md) | [Turing Machines](turing.md)

## Regular Grammar

Type 3 has two types of gammer Left linear grammer and Right linear grammer.

### What is grammer?

A grammar G can be formally written as a 4-tuple (V, T, P, S) where −

V or N is a set of variables or non-terminal symbols.

T or ∑ is a set of Terminal symbols.

S is a special variable called the Start symbol, S ∈ N

P is Production rules for Terminals and Non-terminals. A production rule has the form α → β, where α and β are strings on V ∪ ∑ and least one symbol of α belongs to V.

### Regular expressions

The language accepted by finite automata  can be easily described by simple expressions called Regular Expressions.

The languages accepted by some regular expression are referred to as Regular languages.

if r1 and r2 is regular expression then:

```
r1 ∪ r2 = regular expession
(r1) = regular expession
r1 * r2 = regular expession
r* ={ε} ∪ r ∪ r2 ∪
```

### Algebraic method using Arden’s theorem

#### Finite Automata to Regular Expression

Let P and Q be two regular expressions.

If P does not contain null string, then R = Q + RP has a unique solution that is R = QP*

**Proof −**

```
R = Q + (Q + RP)P [After putting the value R = Q + RP]

= Q + QP + RPP

When we put the value of R recursively again and again, we get the following equation −

R = Q + QP + QP2 + QP3…..

R = Q (ε + P + P2 + P3 + …. )

R = QP* [As P* represents (ε + P + P2 + P3 + ….) ]

Hence, proved.
```

Assumptions for Applying Arden’s Theorem

- The transition diagram must not have NULL transitions
- It must have only one initial state

### Equivalence of Finite Automata and Regular expressions

### Properties of regular languages

![prop][https://swaminathanj.github.io/fsm/rlproperties.html]

### Pumping lemma

[TOC](index.md) | [Formal Languages](formal.md) | [Finite Automata](finite.md) | [Regular Grammar](regular.md) | [Context Free Languages](contextF.md) | [Pushdown Automata](pushdown.md) | [Context Sensitive Language](contextS.md) | [Turing Machines](turing.md)
