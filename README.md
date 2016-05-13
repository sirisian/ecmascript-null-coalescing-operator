# ES7 Proposal: Null Coalescing Operator

Current Mailing List Thread: https://esdiscuss.org/topic/proposal-for-a-null-coalescing-operator

http://wikipedia.org/wiki/Null_coalescing_operator

Essentially x ?? y will return x when not null or undefined else it will return y.

A nice Javascript explanation of the current problems with using || that can cause unforeseen bugs:

stackoverflow.com/a/476445

Also an assignment operator ??= would be added.

## Spec

Section 11.7 needs to add ?? and ??=

There also needs to be a section explaining the behavior.
