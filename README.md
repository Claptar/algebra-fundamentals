# Algebraic Fundamentals: A Motivated Build-Up

These notes are a compact conceptual guide to the algebraic structures that usually appear at the beginning of abstract algebra and probability theory.

The goal is not only to list definitions, but to explain **why the axioms are chosen**, what they allow us to do, what breaks when they are absent, and what natural examples should live in your head.

## Suggested reading order

1. [Binary operations and associativity](chapters/01-binary-operations-and-associativity.md)
2. [Semigroups and monoids](chapters/02-semigroups-and-monoids.md)
3. [Groups and reversibility](chapters/03-groups-and-reversibility.md)
4. [Symmetries and groups](chapters/04-symmetries-and-groups.md)
5. [Commutativity and abelian groups](chapters/05-commutativity-and-abelian-groups.md)
6. [Rings and distributivity](chapters/06-rings-and-distributivity.md)
7. [Fields and scalar arithmetic](chapters/07-fields-and-scalars.md)
8. [Vector spaces](chapters/08-vector-spaces.md)
9. [Algebras over fields](chapters/09-algebras-over-fields.md)
10. [Sigma-algebras](chapters/10-sigma-algebras.md)
11. [One-page map of the structures](chapters/11-map-of-structures.md)

## Recurring chapter pattern

Most chapters follow this pattern:

1. **Definition** — the formal object.
2. **Central intuition** — what the structure is really trying to model.
3. **What the axiom buys us** — what becomes possible.
4. **What breaks without it** — why the axiom is not decorative.
5. **Natural examples** — examples that are not merely artificial.
6. **Place in the build-up** — how the structure connects to earlier and later ones.

## Big guiding idea

Algebra is largely the study of **operations and their laws**.

A law is interesting when it lets us treat complicated expressions coherently:

- associativity lets binary composition become finite composition;
- an identity element lets us include the empty composition;
- inverses let us undo actions;
- commutativity makes order irrelevant;
- distributivity links addition and multiplication;
- scalar multiplication lets an external field control an additive world;
- bilinearity lets multiplication inside a vector space respect linear combinations;
- sigma-closure lets a language of events survive countable logical operations.

The point is not memorizing axioms. The point is seeing what each axiom makes possible.
