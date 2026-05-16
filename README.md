# Math Notes

Notes on algebra, probability theory, and linear algebra. Each topic builds from first principles, explaining not just what the definitions are but why the axioms are chosen, what they make possible, and what breaks without them.

## Structure

```
notes/
  algebra/          — algebraic structures from binary operations to algebras over fields
  probability/      — measure-theoretic foundations of probability
  linear_algebra/   — vector spaces, matrices, and linear maps (coming soon)
```

## Algebra

A build-up of the algebraic structures that appear at the start of abstract algebra and probability theory.

Most chapters follow this pattern:

1. **Definition** — the formal object.
2. **Central intuition** — what the structure is really trying to model.
3. **What the axiom buys us** — what becomes possible.
4. **What breaks without it** — why the axiom is not decorative.
5. **Natural examples** — examples that are not merely artificial.
6. **Place in the build-up** — how the structure connects to earlier and later ones.

1. [Binary operations and associativity](notes/algebra/01-binary-operations-and-associativity.md)
2. [Semigroups and monoids](notes/algebra/02-semigroups-and-monoids.md)
3. [Groups and reversibility](notes/algebra/03-groups-and-reversibility.md)
4. [Symmetries and groups](notes/algebra/04-symmetries-and-groups.md)
5. [Commutativity and abelian groups](notes/algebra/05-commutativity-and-abelian-groups.md)
6. [Rings and distributivity](notes/algebra/06-rings-and-distributivity.md)
7. [Fields and scalar arithmetic](notes/algebra/07-fields-and-scalars.md)
8. [Vector spaces](notes/algebra/08-vector-spaces.md)
9. [Algebras over fields](notes/algebra/09-algebras-over-fields.md)
10. [One-page map of the structures](notes/algebra/11-map-of-structures.md)

## Probability Theory

- [Sigma-algebras](notes/probability/10-sigma-algebras.md)

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
