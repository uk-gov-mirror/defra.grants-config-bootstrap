# Repository Guidelines

## Project Structure & Module Organization

This repository bootstraps grants configuration resources. The package code is in `npm/`; supporting process notes are in `docs/` and `.ai/`. Keep generated or local-only files out of the repository.

## Build, Test, and Development Commands

- `npm --prefix npm install`: install package dependencies.
- `npm --prefix npm test`: run the package tests when present.
- `npm --prefix npm run lint`: run linting when the script is present.

## Coding Style & Naming Conventions

Follow the local package configuration in `npm/package.json`. Prefer small, explicit scripts and descriptive filenames that match the bootstrap operation they perform.

## Domain Language

Use `CONTEXT.md` as the source of truth for grants configuration bootstrap language. When adding scripts, docs, or generated changes, prefer the glossary terms there.

## Developer Addenda

Developers can add their own `AGENTS.local.md` and should be read as an addendum to this file. Keep that file local to your machine and do not commit it.

## Testing Guidelines

Run the narrowest relevant package command first, then run lint or the full test command before opening a PR when those scripts exist.

## Commit & Pull Request Guidelines

Keep commits focused and explain whether the change affects bootstrap behaviour, package release behaviour, or documentation only.
