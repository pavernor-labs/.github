# Contributing

Thanks for looking. This is a small organisation, so the rules are short.

## Before you write code

Open an issue describing the problem. For anything larger than a typo, wait for
a reply — it avoids two people building the same thing differently.

## Pull requests

- One concern per pull request. A refactor and a feature in the same diff will
  be asked to split.
- Describe **why**, not just what. The diff already shows the what.
- Include the command you ran to verify the change, and its output.
- Keep the subject line in the imperative mood: `fix: reject heals below
  threshold`, not `fixed the thing`.

## Commit messages

```
type(scope): summary

Why this change exists, wrapped at 72 columns.
```

Types: `feat`, `fix`, `docs`, `test`, `refactor`, `chore`, `ci`.

## What gets rejected

- Claims of accuracy that are not backed by a reproducible benchmark run.
- Tests that assert on the implementation instead of the behaviour.
- Dependencies added for something the standard library already does.

## Security

Never open a public issue for a vulnerability. See [SECURITY.md](SECURITY.md).
