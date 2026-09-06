# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **binary distribution repository**, not a source code repository. The binaries are not committed to git (see `.gitignore`) — they are published as **GitHub Release assets**. Current artifacts on release `v2.0.0`:

- `JobCuveOneClick.exe` — a compiled Windows application (~88 MB, ProductVersion 2.0.0). The version metadata embeds a commit hash from a separate (private) source repository where the application is actually built.
- `JobCuveOneClick-2.0.0-arm64.dmg` — the macOS build (~42 MB, Apple Silicon only). Ad-hoc signed, not notarized, so users must allow it once via System Settings → Privacy & Security. Built from the same source repository.

There is no source code, build system, test suite, or linter here. There is nothing to build or run in a development sense.

## Working in this repository

- Typical changes are limited to uploading a new build as a release asset (`gh release upload <tag> <file>`) and updating the release notes. Do not attempt to "fix" or decompile the binaries — changes to the application belong in its source repository.
- The default branch is `master`.
- Commit messages in this repo are written in Korean.
