# 593 C Style Guide

A collaboratively maintained C style guide for MCIT students in CIT 593.

Originally created by Jia-Jia Zhu, Spring 2026.

## Who is this for

MCIT students who want to learn and collaborate on C conventions for 593 (maybe 595?). This document is a reference when reading another classmate’s code base for collaborative assignments or even when completing solo assignments.

No prior C experience assumed beyond 593.

## What this is

A reference for C conventions — what the compiler requires vs. what we've agreed on as a group. Useful when writing your own code or reading a classmate's.

## What this is not

- A substitute for assignment instructions (those always take precedence)
- A guide to correctness, efficiency, or design choices (refining should come later anyways)

## Why a guide

- Consistency helps one learn and keeps away bad habits
- Consistency helps others read our code
- This guide includes the *why* certain patterns are preferred. Then you make your own choices as an engineer
- Take the cognitive load off of formatting and keep it on conceptual application and logic

## C version

C17 since Codio as of Spring 2026 runs Clang 14 with no other visible flags.

## How to navigate

### The guide
- [`docs/01-compiler-requirements.md`](./docs/01-compiler-requirements.md) — what the compiler enforces
- [`docs/02-conventions.md`](./docs/02-conventions.md) — agreed group conventions
- [`docs/03-common-pitfalls.md`](./docs/03-common-pitfalls.md) — — common C mistakes to avoid
- [`docs/04-c-vs-java.md`](./docs/04-c-vs-java.md) — translation reference for Java students
- [`docs/05-c-vs-python.md`](./docs/05-c-vs-python.md) — translation reference for Python students

### Contributing
- [`CONTRIBUTING.md`](./CONTRIBUTING.md) — how to propose changes and submit PRs
- [GitHub Issues](../../issues) — active proposals and bug reports
- [GitHub Discussions](../../discussions) — questions, C topics, open-ended conversation
