# Contributing

## Repository organization

`main` is the reference branch. Only finished, working and verified work can be put on it, and work can only be added to it through a pull request.

`dev` is the working "main" branch. Everything must go through it before reaching main. It is used to check that what has been done works correctly and to keep an editable record of what will end up on main.

Branches starting by `poc-` are proof of concepts meant to keep a trace of studied technologies that we decided to try working with. They are not meant to feed actual work straight to the project.


## Commit messages

```
<type> (<scope>) <summary>
```

Types used in this project's history:

- `new` — new feature
- `fix` — bug fix
- `style` — change that doesn't affect the meaning of the code (formatting, …)
- `test` — adding or fixing tests
- `refactor` — change that doesn't add a feature and only modifies what already exists (optimization, cleaner code, etc...)
- `docs` — documentation
- `revert` — reverting a previous commit

Formatting rules:

- the summary does not start with a capital letter and does not end with a period;
- one commit = one coherent change. Split a rename, a bug fix and the addition of a feature into several commits rather than mixing everything together.

No hook automatically rejects a malformed message as of now: \
it is a convention to follow, not a check enforced by tooling.

## Pull requests

A **[pull request template](./.github/pull_request_template.md)** is available to quickly describe what your changes do. \
You may remove sections that don't apply to your work but stay clear and precise.


## Issues

You have **[2 issues templates](./.github/ISSUES_TEMPLATE/)** availble to choose from to quickly create a new issue. \

a **[bug template](./.github/ISSUE_TEMPLATE/bug_report.md)** to warn with issues on the existing parts of the project.
and a **[feature template](./.github/ISSUE_TEMPLATE/feature_request.md)** to request new features on the project.

