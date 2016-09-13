# Stan scripts for phylogenetic analyses

## Quickstart

Running this:
`./scripts/phystan.py -m JC69 -i examples/sim6.fa -t examples/sim6.tree`

Will apply variational inference under the Jukes-Cantor 69 model to the tree in sim6.tree and alignment in sim6.fa

## Prerequisites

You will need to install python, numpy, cython, dendropy.
A custom version of pystan is also required, available from:
[https://github.com/koadman/pystan](https://github.com/koadman/pystan)

To build:

```
  git clone https://github.com/koadman/pystan
  cd pystan
  git submodule update --init --recursive
  python setup.py install
```
