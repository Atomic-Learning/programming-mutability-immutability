One of the important distinctions between types in programming is whether objects of that type can be modified after they are created. This distinction divides types into two categories: **mutable** and **immutable**.

# Mutable Objects

A **mutable** object is one that can be changed or modified after it is created. You can alter the contents or state of a mutable object without having to create a completely new object. What types of objects are mutable and exact behaviours can vary significantly between languages.

# Immutable Objects

An **immutable** object cannot be changed after it is created. If you want to modify an immutable object (or create a variation of it), you must create an entirely new object. The original object remains unchanged (although it may be discarded if no longer referenced).

# Why Does Mutability Matter?

Understanding mutability is important for several reasons:

## Sharing and Aliasing

In some languages, when the same mutable object is referenced by multiple variables or in multiple parts of a program, changes made in one place may be visible elsewhere. This can lead to unexpected behavior if you're not aware of it.

## Performance and Optimization

Because immutable objects cannot change, the programming language and runtime environment can make certain optimizations. Mutable objects require more careful handling to maintain correctness when they're shared between different parts of a program.

## Predictability

Immutable objects provide predictability: once created, their value is guaranteed never to change. This makes reasoning about code easier. Mutable objects require more care because their contents might change unexpectedly.
