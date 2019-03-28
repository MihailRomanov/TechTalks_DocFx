# Introduction to Abstract data type (ATD) and Collections

In computer science, an **abstract data type (ADT)** is a mathematical model for _data types_, where a data type is defined by its behavior (semantics) from the point of view of a user of the data, specifically in terms of possible values, possible operations on data of this type, and the behavior of these operations. This contrasts with _data structures_, which are concrete representations of data, and are the point of view of an implementer, not a user.

**Collection** or **container** is a grouping of some variable number of data items (possibly zero) that have some shared significance to the problem being solved and need to be operated upon together in some controlled fashion. Generally, the data items will be of the same type or, in languages supporting inheritance, derived from some common ancestor type.

## Linear collections
Many collections define a particular linear ordering, with access to one or both ends.

E.g.:
- [List](list.md)
- [Stack](~/articles/stack.md)
- [Queue](xref:queue_intro)
- Double-ended queue (deque)

## Associative collections

Other collections can instead be interpreted as sort of function: given an input, the collection yields an output. Important associative collections include

- Sets
- Multisets
- Associative arrays