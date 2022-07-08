# Functional Programming
#Programming #SML #OOP
1. no mutation
2. [[Functions|using functions as values]]

+ basically, a functional language should support: 
	1. immutable data
	2. [[Function Closures]]
	3. [[Functions#First class and Higher-order functions]]

# Functional vs OOP
- Functional and OOP are exactly opposite ways to look at the same things, so it's not a matter of *this is better than that*, but rather of *which one to use, depending on the way the code is going to grow*:

## Functional
> Creating new functions is faster, creating new types is slower
* Adding a new function means creating a new [[Case expressions|case expression]] (fast)
* Adding a new type means adding a new case for all of the case expressions (slow)

## OOP
> Creating new types is faster, creating new functions is slower
* Adding a new function means adding it to all of the classes (slow)
* Adding a new type means implementing all functions for it (fast)