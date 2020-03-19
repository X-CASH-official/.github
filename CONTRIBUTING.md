# 🤝 Contributing to the X-Cash Foundation

Welcome ! 🙏 Thank you for proposing to contribute to the X-Cash Foundation

Further down are presented a set of guidelines to help you contribute to X-Cash and its derived programs, hosted in the [X-Cash Foundation](https://github.com/X-CASH-official) organization on GitHub.

> This set of guidelines is not mandatory, although it will greatly help the organizations and maintainers job and keep the contributing environment clean 🧼.

#### Table Of Contents

  * [Code of Conduct](#code-of-conduct)
  * [Before Getting Started](#before-getting-started)
  * [How Can I Contribute?](#how-can-i-contribute-)
    + [Reporting Bugs 🐛](#reporting-bugs---)
    + [Suggesting New Features/Enhancements 🌟](#suggesting-new-features-enhancements---)
    + [Code Contribution & Bounties 👨‍💻](#code-contribution---bounties------)
    + [Pull Requests](#pull-requests)
  * [Commit Styleguide](#commit-styleguide)


## Code of Conduct

The project is governed by the [X-Cash Foundation Code of Conduct](https://github.com/X-CASH-official/.github/blob/master/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the project team at [developers@xcash.foundation](mailto:developers@xcash.foundation).

## Before Getting Started 

When contributing to any X-Cash Foundation repository, please first discuss the change you wish to make via issues, email to [developers@xcash.foundation](mailto:developers@xcash.foundation), or any other method with the owners of this repository before making a change.

You are also expected to check the current and previously closed issue for duplicate before opening a new one. 

## How Can I Contribute? 

### Reporting Bugs 🐛

First of all, you will need to determine which program repository relates to your bug (do not post an issue on [xcash-core](https://github.com/X-CASH-official/xcash-core) if you are experiencing a problem with the [desktop-wallet](https://github.com/X-CASH-official/desktop-wallet)).

When you are creating a bug report, please [include as many details as possible](#submit-a-good-bug-report). Fill out [the required template](https://github.com/X-CASH-official/.github/blob/master/ISSUE_TEMPLATE/bug_report.md). The provided information helps us targeting the issue quicker.

#### Before Submitting A Bug Report

Before creating but reports, please check the repository's issues to see if the problem has already been reported. 

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Submit A Good Bug Report

Bugs are tracked alongside new features request as [GitHub issues](https://guides.github.com/features/issues). After you have determined which repository your bug is relating to, create an issue on that repository and provide the necessary information by filling in [the required template](https://github.com/X-CASH-official/.github/blob/master/ISSUE_TEMPLATE/bug_report.md).

Explain the problem and include as many details as possible to help the project team to reproduce the problem: 

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots** if it helps describing the issue.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened.

### Suggesting New Features/Enhancements 🌟

First of all, you will need to determine which program repository would profit from the proposed enhancement. 

When you are creating a new feature request, please [include as many details as possible](#submit-a-good-feature-request). Fill out [the required template](https://github.com/X-CASH-official/.github/blob/master/ISSUE_TEMPLATE/feature_request.md), the information it asks for helps us see clearly what you are referring to.

#### Before Submitting A New Feature Request

Before creating a new feature request, please check the repository's issues to see if the feature has already been requested or if it's already integrated.

> **Note:** If you plan to work on a new feature, please make sure it has been discussed with the core team

#### Submit A Good Feature Request

Feature request are tracked alongside bug reports as [GitHub issues](https://guides.github.com/features/issues). After you have determined which repository your feature request is relating to, create an issue on that repository and provide the necessary information by filling in [the required template](https://github.com/X-CASH-official/.github/blob/master/ISSUE_TEMPLATE/feature_request.md).

Explain the problem and include as many details as possible to help the project team to reproduce the problem: 

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots** to help describe the suggested improvment.
* **Describe a possible solution** if you have an idea already. 

### Code Contribution & bounties 👨‍💻

While everyone is free to participate in the development and undertake issues, we are proposing bounties to give rewards to some contributions.

These rewarded issues will have a `bounty` tag, and can be undertaken by anyone in the community after the team assigned the issue through the [bounty assignation process](#bounty-assignation-process). 



#### Bounty Assignation Process

Please refer to the **[Builder's Program]()** for more information on how to contribute to these bounties.

### Pull Requests

> **Before creating a PR:** Make sure that your pull request is fixing and issue or is relating to a feature request listed in the repository's issues. If not, please create an issue to on your 

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](https://github.com/X-CASH-official/.github/blob/master/PULL_REQUEST_TEMPLATE.md)
2. Follow the [commit styleguides](#commit-styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Commit Styleguide

### Signing Commits *(optional)*

> This is not mandatory but highly recommended for every project you are working on.

Please sign your commits when you are pushing new changes to your branch. You can follow a tutorial [**here**](https://help.github.com/en/github/authenticating-to-github/signing-commits)

When you sign your Git commit, you can prove that the code you submitted came from you and wasn't altered while you were transferring it. You also can prove that you submitted the code and not someone else.

### Writing Comprehensive Commits

> These guidelines are based on the Angular Convention [commit guideline](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit)

Please use the following guidelines to format all your commit. This helps the maintaners quickly gathering what the commit relates, and bring some readibility to the overall project: 

```txt
<type>: <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```
#### `<type>`

The commit title should start with the `<type>`, which can be: 
* **feat** for features
* **fix** (bug fix)
* **docs** (documentation)
* **style** (formatting, missing semicolons, …)
* **refactor**
* **test** (when adding missing tests)
* **chore** (maintain repository, changed CI configuration, ...)

#### `<subject>`

The commit `<subject>` should follow the following guidelines: 

* Use the imperative, present tense ("change" not "changed" nor "changes")
* Don't capitalize the first letter
* Do not end the line with a dot (.)
* Limit to 50 characters or less

#### `<body>`

The message `<body>` should follow the same guidelines as the [`<subject>`](#subject), with small variations: 

* Use the imperative, present tense ("change" not "changed" nor "changes")
* Don't capitalize the first letter
* Do not end the line with a dot (.)
* **Limit to 72 characters or less**
* Seperate subject from body with a blank line
* Explain what and why vs. how
* Can use multiple lines with "-" for bullet points in body

#### `<footer>`

The `<footer>` should indicate the referenced GitHub issues that this commit closes.

**Commit Message Example:** 

```txt
fix: add delegate name

- add handler for delegate name
- fix display behavior for delegate field

fixes issue #1245
```

