# Contributing with our projects

Some of our open-source projects are under very active development and also being used by many customers. We're still working out the kinks to make contributing to our projects as easy and transparent as possible, but we're not quite there yet. Hopefully this document will make the contribuing process clear and answers the questions you may have.

## [Code of Conduct](CODE_OF_CONDUCT.md)

Pagar.me has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](CODE_CONDUCT.md) to understand what actions will and will not be tolerated.

## Our Development Process

Some of the core team will be working directly on GitHub. These changes will be public from the beginning.

### `master` is unsafe

We will do our best to keep `master` in good shape, with tests passing at all times. But in order to move fast, we will make API changes in some of our projects that your application might not be compatible with. We will do our best to communicate these changes and always version appropriately so you can lock into a specific version as needed.

### Tests

Make sure that all the tests are passing if you have changed any code in a project. All of them should be relevant and test real world cases.

### Pull Requests

**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

The core team will be monitoring pull requests. When we get one, we'll run specific integration tests on it first. From here, we'll need to get another person to sign off on the changes and then merge the pull request. For API changes, further discussions might be necessary since huge impact can be caused on a lot of customers, which could cause some delay. We'll do our best to provide updates and feedback throughout the process.

*Before* submitting a pull request, please make sure the following is done…

1. Fork the repo and create your branch from `master`.
2. If you've added code that should be tested, add tests!
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Don't bump versions or update the CHANGELOG.
6. Make sure your code lints we've done our best to make sure these rules match our internal linting guidelines.
7. If you haven't already, complete the CLA.

### Contributor License Agreement (CLA)

In order to accept your pull request, we need you to submit a CLA. You only need to do this once, so if you've done this for another Pagar.me open source project, you're good to go. If you are submitting a pull request for the first time, just let us know you have completed the CLA and we can cross-check with your GitHub username.

[Complete your CLA here.](https://code.pagar.me/cla)

## Bugs

### Where to Find Known Issues

We will be using GitHub Issues for our public bugs. We will keep a close eye on this and try to make it clear when we have an internal fix in progress. Before filing a new task, try to make sure your problem was not reported by someone else in other issue.

### Reporting New Issues

The best way to get your bug fixed is to provide a reduced test case explaining how to reproduce the bug.

### Security Bugs

Pagar.me has a very strict security culture. Therefore, if any of our projects have any vulnerability that can affect our customers, we have an email for safe disclosure. With that in mind, please do not file public issues; go through the process outlined below.

Please send an email to [suporte@pagar.me](mailto:suporte@pagar.me) and describe the bug and the best way to reproduce them. We will reply as soon as possible and do our best to fix the bug as fast as possible too.

### Licensing

By contributing to our open-source projects, you agree that your contributions will be licensed under the project license.
