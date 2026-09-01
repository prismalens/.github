# prismalens/.github

Organization-wide default community health files and issue templates for
`prismalens`. GitHub applies anything here to any repo in the org that lacks
its own copy of the same file — see
[Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## What lives here

- `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md` — propagate
  to any repo lacking its own copy.
- `.github/ISSUE_TEMPLATE/` — the default bug report and feature request forms,
  plus `config.yml`.

## Warning for future maintainers: the suppression is per-directory, not per-file

Inheritance of issue templates works on the whole `.github/ISSUE_TEMPLATE/`
directory, not file by file. If a repo has **any** file in its own
`.github/ISSUE_TEMPLATE/` — even a bare `config.yml` with no templates in it —
GitHub drops this repo's entire default `ISSUE_TEMPLATE` folder for that repo.
There is no way to keep the org's default templates while only overriding the
chooser config.

So: a repo that wants these default templates must have **no**
`.github/ISSUE_TEMPLATE/` directory of its own at all. A repo that needs even
one local template must carry a full local set, because it is getting none of
this one.

## What does not propagate

`LICENSE` cannot be centralized this way. GitHub never applies a default
license file to a repo lacking one; every repo must commit its own.
