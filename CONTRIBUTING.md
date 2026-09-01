# Contributing

This is the organization-wide default. It covers only what is common across
`prismalens` repositories. **Build steps, toolchain versions, clone
instructions, and anything else project-specific live in that repository's
own README or CONTRIBUTING**. Read those first.

## Ground rules, common to every repo here

- **`main` is protected.** Every change lands through a pull request; direct
  pushes to `main` are not allowed, including for the maintainer.
- **The PR title must be a valid [Conventional Commit](https://www.conventionalcommits.org/)**
  (`feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`, `ci:`, `perf:`,
  …). Most of these repos squash-merge, so the title becomes the trunk
  commit subject, and CI checks it.
- **CI must be green before merge.**
- **No unresolved review threads.** A finding matters exactly as much as the
  thread it lives in; pushing a fix does not clear a thread, only a reply
  plus resolution does.
- **Never commit secrets.** No API keys, tokens, connection strings, or
  private content, in code or in issues.

## Reporting bugs and requesting features

Use that repository's issue templates. For anything security-sensitive, do
not open a public issue. See its `SECURITY.md`.
