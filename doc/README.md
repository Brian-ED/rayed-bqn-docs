*View this file with results and syntax highlighting [here](https://brian-ed.github.io/rayed-bqn/doc/index.html).*

# Rayed-bqn documentation

Working BQN library for making games.
Not stable, though usable. Breaking changes, when intentional, will be explained in the BQN forum.

Rayed-bqn's documentation describes what features it has, how to use them, and why they were chosen.
The rayed-bqn documentation will avoid talking about bqn specifics like primitives, for those you may refer to the (BQN documentation)[https://mlochbaum.github.io/BQN]

## REST OF DOCUMENTATION IS WORK IN PROGRESS

Overview:
- [Styles](style.md)
- [Naming conventions](naming.md)
- [Primitives](primitive.md)
- [Navigation](nav.md) (for example when to look in raylib.bqn vs rayed.bqn)
- See also [help index](../help/README.md); [summary gist](https://gist.github.com/dzaima/52b47f898c5d43f72dc2637d6cdadedd)

References:
- [Glossary](glossary.md)
- [BQN-Dyalog dictionary](fromDyalog.md)
- [BQN-J dictionary](fromJ.md)
- [BQN as combinatory logic](birds.md)

Concepts:
- [Tokens and constants](token.md)
- [Expression syntax](expression.md)
  - [Context-free grammar](context.md)
- [Arrays](array.md)
  - [Based array theory](based.md)
  - [Array notation and display](arrayrepr.md)
  - [Array indices](indices.md)
  - [Fill elements](fill.md)
  - [The leading axis model](leading.md)
- [Functions and modifiers](ops.md)
  - [Functional programming](functional.md)
- [Tacit programming](tacit.md)
  - [Function trains](train.md)
- [Blocks](block.md)
  - [Lexical scoping](lexical.md)
  - [Control flow](control.md)
- [Namespaces](namespace.md)
  - [Object-oriented programming](oop.md)

Primitives:
- [Arithmetic: `+-×÷⋆√⌊⌈|≤<>≥=≠`](arithmetic.md)
- [Array depth: `≡` and `⚇`](depth.md)
- [Array dimensions: `≢=≠`](shape.md)
- [Assert and Catch: `!` and `⎊`](assert.md)
- [Atop and Over: `∘○`](compose.md)
- [Before and After: `⊸⟜`](hook.md)
- [Cells and Rank: `˘⎉`](rank.md)
- [Choose: `◶`](choose.md)
- [Constant: `˙`](constant.md)
- [Deshape and Reshape: `⥊`](reshape.md)
- [Enclose: `<`](enclose.md)
- [Find: `⍷`](find.md)
- [Fold and Insert: `´˝`](fold.md)
- [Group: `⊔`](group.md)
- [Identity functions: `⊢⊣`](identity.md)
- [Indices and Replicate: `/`](replicate.md)
- [Join and Join To: `∾`](join.md)
- [Logical functions: `∧∨¬`](logic.md)
- [Mapping: `¨⌜`](map.md)
- [Match: `≡≢`](match.md)
- [Ordering functions: `∧∨⍋⍒`](order.md)
- [Pair: `⋈`](pair.md)
- [Pick: `⊑`](pick.md)
- [Prefixes and Suffixes: `↑↓`](prefixes.md)
- [Range: `↕`](range.md)
- [Repeat: `⍟`](repeat.md)
- [Reverse and Rotate: `⌽`](reverse.md)
- [Scan: `` ` ``](scan.md)
- [Search functions: `⊐⊒∊`](search.md)
- [Select: `⊏`](select.md)
- [Self and Swap: `˜`](swap.md)
- [Self-search functions: `⊐⊒∊⍷`](selfcmp.md)
- [Shift functions: `»«`](shift.md)
- [Solo, Couple, and Merge: `≍>`](couple.md)
- [Take and Drop: `↑`](take.md)
- [Transpose: `⍉`](transpose.md)
- [Under: `⌾`](under.md)
- [Undo: `⁼`](undo.md)
- [Valences: `⊘`](valences.md)
- [Windows: `↕`](windows.md)

Environment:
- [Embedded BQN](embed.md)
- [ReBQN](rebqn.md)
