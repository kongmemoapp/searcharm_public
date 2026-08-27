# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **binary distribution repository**, not a source code repository. It contains a single artifact:

- `files/JobCuveOneClick.exe` — a compiled Windows application (~92 MB, ProductVersion 2.0.0). The version metadata embeds a commit hash from a separate (private) source repository where the application is actually built.

There is no source code, build system, test suite, or linter here. There is nothing to build or run in a development sense.

## Working in this repository

- Typical changes are limited to replacing `files/JobCuveOneClick.exe` with a new build and committing it. Do not attempt to "fix" or decompile the executable — changes to the application belong in its source repository.
- The default branch is `master`.
- Commit messages in this repo are written in Korean.
