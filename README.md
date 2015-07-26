# Ookell
A simple [`Ook!`](http://esolangs.org/wiki/ook!) interpreter in Haskell. Mostly a lexer, as it leverages [brainfucker](https://github.com/expede/brainfucker) for the rest.

# Installation

```bash
stack install
```

# Tests
## Run Tests
```bash
stack test
```

## Build Status
| Branch | CircleCI |
|--------|-------------------------|
| Master | [![Circle CI](https://circleci.com/gh/expede/brainfucker/tree/master.svg?style=svg)](https://circleci.com/gh/expede/ookay/tree/master) |

## [Tasty](http://documentup.com/feuerbach/tasty)
> Tasty is a modern testing framework for Haskell.
> It lets you combine your unit tests, golden tests, QuickCheck/SmallCheck properties, and any other types of tests into a single test suite.

## [Doctest](https://github.com/sol/doctest)
> `doctest` is a small program, that checks examples in Haddock comments.
> It is similar to the popular Python module with the same name.
