# Contributing to Shutterstock Code

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to the [Shutterstock Organization](https://github.com/shutterstock) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

These suggestions are repository-agnostic - for each repository, read the CONTRIBUTING.md document in that repository for specific instructions on how to contribute.

## Table Of Contents

- [Code of Conduct](#code-of-conduct)
- [What should I know before I get started?](#what-should-i-know-before-i-get-started)
- [How Can I Contribute?](#how-can-i-contribute)
	- [How Do I Submit A (Good) Bug Report? 🐞🐛🐜](#how-do-i-submit-a-good-bug-report-)
	- [Your First Code Contribution](#your-first-code-contribution)
- [Styleguides](#styleguides)
	- [Git Commit Messages](#git-commit-messages)
	- [Code](#code)

## Code of Conduct

This project and everyone participating in it is governed by the [Shutterstock Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [open-source@shutterstock.com](mailto:open-source@shutterstock.com).

## What should I know before I get started?

Shutterstock is a large organization with a lot of open source modules, all of which we use to keep the Shutterstock website and our codebase working. We use many different languages, and have a lot of different use cases. Because of this, unlike some organizations like [atom](https://github.com/atom) or [nodejs](https://github.com/nodejs), our repositories here are not all thematically similar. However, all of them fall under our purview.

We don't open source packages unless we think that they might be useful to the wider community, and we're interested in long term maintenance of our packages.

Here's a list of some of the more popular repositories:

* [rickshaw](https://github.com/shutterstock/rickshaw) - Rickshaw is a JavaScript toolkit for creating interactive time series graphs. Rickshaw relies on the fantastic D3 visualization library to do lots of the heavy lifting for stacking and rendering to SVG.
* [node-common-errors](https://github.com/shutterstock/node-common-errors) - Common error classes and utility functions for Node. This is a full suite of node.js Error classes like you'd find in most other modern languages. You can append stack traces from other asynchronously generated Errors, generate your own custom Error classes in one line, and map HTTP status codes to Errors for automatic handling in web services and applications.
* [lil-brother](https://github.com/shutterstock/lil-brother) - Li'l Brother tracks clicks on web pages, without blocking any interaction.

## How Can I Contribute?

You can contribute in many ways! You can comment on issues with your opinions, suggest labels for comment threads, review code on pull requests, suggest changes to the code by submitting your own pull requests, open issues suggesting enhancements or filing bugs, and so on. **Not all contributions are code related.**


#### How Do I Submit A (Good) Bug Report? 🐞🐛🐜

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository your bug is related to, create an issue on that repository. Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. When listing steps, **don't just say what you did, but explain how you did it**. 
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

### Your First Code Contribution

_We're working on filing more of these! For now, if you don't see any, don't worry._

Unsure where to begin contributing? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings

### Code

Conform to the coding style set for each repository you submit to. Each repository should have a CONTRIBUTING doc that outlines contributing information specific to that repository.

[beginner]:https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Abeginner+label%3Ahelp-wanted+user%3Ashutterstock+sort%3Acomments-desc
[help-wanted]:https://github.com/issues?q=is%3Aopen+is%3Aissue+label%3Ahelp-wanted+user%3Ashutterstock+sort%3Acomments-desc+-label%3Abeginner