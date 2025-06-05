# Contributing Guidelines

_Pull requests, bug reports, feature requests and all other forms of contributions are welcomed and highly encuraged!_

### Contents

- [Code of Conduct](#book-code-of-conduct)
- [Asking questions](#question-asking-questions)
- [Issues](#inbox_tray-issues)
  - [Security Issues](#lock-security-issues)
  - [Reporting bugs and other problems](#exclamation-reporting-bugs-and-other-problems)
- [Feature Requests](#love_letter-feature-requests)
- [Triage](#mag-triaging-issues)
- [Submitting Pull Requests](#arrow_down-submitting-pull-requests)
- [Writing Commit Messages](#memo-writing-commit-messages)
- [Code Review](#white_check_mark-code-review)
- [Coding Style](#nail_care-coding-style)
- [Certificate of Origin](#medal_sports-certificate-of-origin)



> These guidelines are meant to set clear standards for our community and to help us create a positive experience for everyone. Please take a moment to read them before contributing.

## :book: Code of Conduct
Please review our [Code of Conduct](https://). It is in effect all the time and everywhere across the org. We expect it to be honored by everyone who contributes (Participating in discussions already counts as contributing!). Acting against it will not be tolerated.

## :question: Asking questions
Please reference our [Support Guide](https://). In short: GitHub Issues for bugs and features, discussions for questions regarding the project. Utilize the docs and Stack Overflow.

## :inbox_tray: Issues
Before you create an issue, please check whether you are using the latest version - or if applicable an LTS release - of the project. If you are not, please update to a supported version and check if the issue still exists.
If it still exists continue.

### :lock: Security Issues
Review our [Security Policy](https://). Do not file a public issue for security vulnerabilities.

### :exclamation: Reporting bugs and other problems
If you have a problem and would like it to be fixed, please include relevant details. We always appreciate when a bug report is well-written and thorough.

*TL;DR: You likely are a dev yourself, please write an issue in a way you would like to receive it yourself.*

- **Review docs, guides and the [support guidelines](https://)** before opening an issue.
- **Do not open a duplicate issue.** Search through existing issues and if one already exists add to it. This helps us prioritize common issues much more.
- **Do not "+1" or "same here" in the comments.** To show, that you have the same problem you can use the :heavy_plus_sign: [reaction](https://github.blog/news-insights/product-news/add-reactions-to-pull-requests-issues-and-comments/) on an existing issue.
- **Use [GitHub-flavoured MD](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)**. Put code examples or console output into backticks (\`\`\`). This improves readability.
- **Use the provided issue templates.** The bug report template requests all the information we need to quickly and efficiently address your issue. Be clear, concise, and descriptive. Provide as much information as you can, including steps to reproduce, stack traces, compiler errors, library versions, OS versions, and screenshots (if applicable).

## :love_letter: Feature Requests
We love feature requests. But: While we will consider all requests, we won't guarantee accepting any requests. We would like to avoid [Feature Creep](https://en.wikipedia.org/wiki/Feature_creep). So even if your idea may be great, it may just be out-of-scope for the project.
If we accept a feature request we will not commit to a timeline for implementation and/or release. You are however welcome to submit a pull request to help!

- **Do not open duplicate feature requests.** Search through existing pull requests first. If one already exists add to it instead of opening a new one.
- **Use the provided issue template.** The feature request template asks for all necessary information for us to begin a productive conversation.
- **Be precise about the proposed feature.** If possible include implementation details. Don't say you want something to be colored if you want it to be yellow.


## :mag: Triaging Issues
You can help triaging issues by reproducing bugs or asking for additional information if applicable (e.g. version numbers, reproduction steps). Any help to quickly resolve an issue is welcome.

## :arrow_down: Submitting Pull Requests

We love pull requests! Before forking and creating a pull request, it is usually best to open an issue for discussing changes first. Alternatively discuss your suggested approach in the comments for an existing issue.

*Note: All contributions will be licensed under the project's license.*

-   **Smaller is better.** Keep pull requests focused and manageable. Smaller changes are easier to review and merge.
-   **Coordinate big changes.** Discuss larger features or architectural changes before implementation to ensure alignment with project goals.
-   **Understanding > Cleverness.** Prioritize clear and maintainable code over overly complex or "clever" solutions.
-   **Follow existing coding style and conventions.** Maintain consistency with the project's established coding style to improve readability and collaboration.
-   **Include tests.** Ensure new features and bug fixes are accompanied by relevant tests to maintain code quality and prevent regressions.
-   **Update docs and examples.** Keep documentation and examples up-to-date to reflect changes in the codebase and help users understand new features.
-   **Branch from and merge to ```develop```.** We use Git Flow. Base your work on the `develop` branch and merge back into it to integrate changes into the main development line.
-   **Resolve merge conflicts.** Handle any merge conflicts that arise during the pull request process to ensure a clean integration of changes.
-   **Address any CI failures.** If your changes don't pass all continuous integration checks, please push a fix.
- **When writing comments, use properly constructed sentences, including punctuation.** Comments and documentation are meant to help with understanding code, not add to unclarity.
- **Use spaces, not tabs.** This is technically already included in coding style but as this is a quasi-religious discussion specifically calling this out is warranted.

## :memo: Writing Commit Messages

We adopted a [modified version of Conventional Commits](https://cis-oss.github.io/commit-spec). Please follow it.

## :white_check_mark: Code Review
- **Review the code, not the author.** Look for and suggest improvements without disparaging or insulting the author. Provide actionable feedback and explain your reasoning.

- **You are not your code.** When your code is critiqued, questioned, or constructively criticized, remember that you are not your code. Do not take code review personally.

- **Always do your best.** No one writes bugs on purpose. Do your best, and learn from your mistakes.

- Kindly note any violations to the guidelines specified in this document.

## :nail_care: Coding Style

Consistency is the most important. Following the existing style, formatting, and naming conventions of the file you are modifying and of the overall project. Failure to do so will result in a prolonged review process that has to focus on updating the superficial aspects of your code, rather than improving its functionality and performance.

For example, if all private properties are prefixed with an underscore `_`, then new ones you add should be prefixed in the same way. Or, if methods are named using camelcase, like `thisIsMyNewMethod`, then do not diverge from that by writing `this_is_my_new_method`. You get the idea. If in doubt, please ask or search the codebase for something similar.

When possible, style and format will be enforced with a linter.

## :medal_sports: Certificate of Origin

```
Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

