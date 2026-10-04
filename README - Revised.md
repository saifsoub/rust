# rust (Seif's fork) — plain-language README

## What this is
This is Seif's copy (a "fork") of **rust-lang/rust**, the official home of the Rust programming language. It holds the compiler (the program that turns Rust code into a working app), the standard library (ready-made building blocks every Rust program can use), and the tests and tools around them.

## Who it's for
People who want to read, build, or change the Rust language itself. If you only want to *use* Rust, install it from the official site instead; you don't need this repo.

## What it does today
- It's a copy of the upstream project.
- **Seif's changes vs upstream:** none found. There are no commits by Seif, so it looks unchanged.

## How to run it
Building the compiler from source is a big job. Follow `INSTALL.md` in this repo. The build tool is `x.py` (also `./x` on Mac/Linux and `x.ps1` on Windows), for example:
```
./x build
```
Check `INSTALL.md` for what you need first and the exact steps.

## Current status and known gaps
- Why Seif forked it: not yet confirmed.
- The fork may be behind upstream; how far is not yet confirmed.

## Where things live
| Folder / file | What's in it |
|---|---|
| `compiler/` | The Rust compiler |
| `library/` | The standard library |
| `src/` | Tools, docs and the build system |
| `tests/` | Tests |
| `README.md`, `INSTALL.md` | The upstream readme and build guide |
| `LICENSE-MIT`, `LICENSE-APACHE` | License: MIT or Apache-2.0 |
