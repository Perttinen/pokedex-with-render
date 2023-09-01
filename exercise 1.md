Tools available in the Python ecosystem for Continuous Integration (CI) setup:

pytest for testing: A mature full-featured Python testing tool. Also Behave is very suitable and popular test framework with python.
flake8 for linting: A tool that checks your code for stylistic errors and violations of the PEP 8 style guide. According to Linkedin, flake8 is the most used python linter.
tox for testing and building: A generic virtualenv management and test command line tool which provides the following features: o Checking that packages install correctly with different environments o Running your tests in each of the environments with the test tool of choice o Acting as a frontend to continuous integration servers, greatly reducing boilerplate and merging CI and shell-based testing
Alternatives to Jenkins and GitHub Actions for CI setup:

Travis CI: A hosted continuous integration service used to build and test software projects hosted at GitHub and Bitbucket.
CircleCI: A cloud-based continuous integration and delivery platform.
Azure Pipelines: A cloud-based continuous integration and delivery service.
GitLab CI: A continuous integration tool built into GitLab.
A cloud-based environment would be a good choice for a team of six people. It is easier to scale and requires less maintenance. There are also other factors such as budget and the complexity of application that should be considered before making a final decision.
