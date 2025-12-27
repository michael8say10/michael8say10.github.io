Here’s a very simple Makefile that works well on FreeBSD for compiling a basic C program.

Example project

Assume you have:

main.c

output program named hello

How to use

```
make        # build
make clean  # remove compiled program
```

Notes (FreeBSD-specific)

cc is the default system compiler on FreeBSD (usually Clang).

This Makefile is portable and works with FreeBSD’s make.
