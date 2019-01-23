# Introduction to Go

The Programming Langauge Go.
First two letters of "Google".
Fed up with infinitely long compile times,
and the 8 megabytes of lexing that the compiler had to do for
every byte of source code.

## Go Top Trumps

Static type system.
Runtime checks.
Safe.
Garbage Collected.

Looks like C, but with types following names.

Generally fairly explicit, not very magic.

Some non-orthogonal design decisions for certain types.

Fairly fast.

Goroutines (a pun on coroutines) and channels provide a
multithreading model that originated in
C. A. R. Hoare's Communicating Sequential Processes.

Code of Conduct

## Go Types

integer types, signed and unsigned, up to 64 bit.

float, 64-bit only; complex.

string


compound types:
function
struct
array
slice
map

structs are embeddable, creating an ersatz hierarchy.

interface (like a pointer plus a vtable)

types are extensible in three ways:

- you can write a method that acts on a type;
- you can embed one struct in another;
- you can create or use an interface type.

## Practicalities
