# Contribution Guide

This project enforces (see [workflows](../.github/workflows/)) the following
formatters:
- `clang-format` version 19 for all the C files, source and headers (or any
  protobuf if any, in the future).

The following tools are not (automatically) enforced but mandatory:
- `shfmt -ci -i 4 -ln posix` for shell formatting.

The codebase is better compiled and checked with `-Wall`. Ideally, no warning
should show.
