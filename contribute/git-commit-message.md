# Commit Message Guidelines for OpenEBS Projects

This document borrows concepts, conventions, and text mainly from the following sources, extending them in order to provide a sensible guideline for writing commit messages for OpenEBS projects.
- Tim Pope's [article](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) on readable commit messages
- Thanks to @stephenparish https://gist.github.com/stephenparish/9941e89d80e2bc58a153
- Thanks to @abravalheri https://gist.github.com/abravalheri/34aeb7b18d61392251a2

These conventions are aimed at tools to automatically generate useful documentation, or by developers during debugging process.

## Proposed Commit Message Format

Any line of the commit message cannot be longer than 80 characters! This allows the message to be easier to read on github as well as in various git tools. To read more about conventional commits refer [here](https://www.conventionalcommits.org/en/v1.0.0/#specification).

```
<type>(<scope>): <subject> <meta>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

### Allowed `<type>`

* **feat**: A new feature
* **fix**: A bug fix
* **docs**: Documentation only changes
* **style**: Changes that do not affect the meaning of the code 
  (white-space, formatting, missing semi-colons, etc)
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **perf**: A code change that improves performance
* **test**: Adding missing tests
* **chore**: Changes to the build process or auxiliary tools and libraries
   such as documentation generation
* **build**: Changes related to buildscripts or building mechanism.
* **ci**: Changes related to CI/CD, ex. github worklow.
* **example**: Changes related to adding examples, related code, configuratiuon, deployment
* **security**: Changes related fixes for security vulnerabilities.

### Allowed `<scope>`

Scope could be anything specifying impacted module/package.
For example: when committing to openebs/openebs repo, the scope can be
- components : kubectl-plugin, helm-chart, etc.
- generic    : ci, etc.

### `<subject>` text

Subject line should contains succinct description of the change. 

* use imperative, present tense: “change” not “changed” nor “changes”
* don't capitalize first letter
* no dot (.) at the end

### Message body

* just as in `<subject>` use imperative, present tense: “change” not “changed” nor “changes”
* includes motivation for the change and contrasts with previous behavior

### Message footer

* Should be the developer sign off. Ref:
https://github.com/openebs/community/blob/develop/CONTRIBUTING.md#sign-your-work

### Revert

If the commit reverts a previous commit, it should begin with revert:, followed by the header of the reverted commit. In the body it should say: This reverts commit <hash>., where the hash is the SHA of the commit being reverted.

### Examples

Here are some PRs that follow the convention proposed in this document.
- https://github.com/openebs/openebs/pull/1876
- https://github.com/openebs/mayastor/pull/1791