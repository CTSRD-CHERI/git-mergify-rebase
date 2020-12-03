# git-mergify-rebase

git-mergify-rebase is a replacement for [mergify], written using git-rebase
rather than pure shell for an order-of-magnitude improvement in performance.
Most features of the original are supported, with the -c/-p/-s options for
start being omitted.

[mergify]: https://github.com/brooksdavis/mergify
