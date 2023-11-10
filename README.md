This repo implements the `cabal doctest` command with cabal's support for
external commands.

# Installation

Provision these scripts on your PATH by whatever means you
normally do for your distribution.

# Usage

```
# Run doctests for a component
cabal doctest <component>

# Prepare the doctest executable, but do not run the tests
cabal doctest-init

# Display a useful help message
cabal help doctest
```

