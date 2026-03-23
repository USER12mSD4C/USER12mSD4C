# USER12mSD4C

Systems programming. OS development, compilers, tooling.

---

## Projects

### [`utms7`](https://github.com/USER12mSD4C/utms7)
x86‑64 OS, C + NASM.

- Hybrid kernel
- Custom UFS filesystem
- `upac` package manager
- QEMU for testing, Arch Linux as build host

Currently in active development.

### [`wond-c`](https://github.com/USER12mSD4C/wond-c)
Compiler from custom syntax to NASM.

- `sc.true` / `sc.false` - syscalls vs bare metal
- Custom syntax → IR → optimization → NASM
- Static typing (`u64`, pointers, etc.)
- Designed to be portable

### [`umk`](https://github.com/USER12mSD4C/umk)
Simple Build System.

- Cleaner syntax, flags instead of command chains
- Pattern rules, conditionals, wildcards
- Timestamp checking, dry‑run mode


Written in ~5 hours out of boredom, used daily by me


## Toolchain

- Arch Linux (x86_64)
- GCC cross‑compiler
- NASM, QEMU
- umk for builds

---
