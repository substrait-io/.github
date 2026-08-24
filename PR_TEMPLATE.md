Thank you for submitting a pull request to the Substrait project. As part of your submission, please fill out the following sections by deleting the instructions, but retaining the headers.

While writing your PR, please:

* Assume that a real person will read what you write in your code and on Github.
* Be respectful of reviewer time and make what you write clear and to the point.

Reviewers are empowered to ask for simplifications in text communication whenever they see fit.

## Change Summary [REQUIRED]
This section aims to provide your reviewer (and other future readers) with a high-level description of your change.

The PR title and Change Summary section should combine into a valid Conventional Commit style message. It will become the commit message for your changes, as contributors use this section when squash merging your PRs (potentially with edits).

Use BREAKING CHANGE footers to communicate breaking changes.

Example

```
feat!: drop deprecated field X

Users should utilize Y instead.

BREAKING CHANGE: field X has been removed
BREAKING CHANGE: function Z now consumes a Y
```

## Motivation [REQUIRED]
Explain what this change is about. This can either be:
* A link to an existing issue which motivates the change.
* A brief description of what motivates the change.

If you find yourself writing a long Motivation section, consider filing an issue first to make sure the community agrees it is an issue.

## Reviewer Context [OPTIONAL]
Provide any additional context that could assist reviewers. This includes, but is not limited to:
* High-level invariants.
* Key design decisions that influenced code.
* Non-obvious implementation constraints.

Don't feel like you have to document every decision up-front. If reviewers have questions or require clarifications, they will ask them. More context is not necessarily better.

Avoid stating things that can be gleaned from the changes themselves, like:
* Lists of files touched — those are in the diff.
* Claims that CI-verified things pass — "tests pass", "formatting clean". That's what CI is for.
* Process notes that are already implicit — "opened as draft pending review".
