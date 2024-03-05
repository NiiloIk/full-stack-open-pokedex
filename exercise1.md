I'm doing a coding project with python and 6 developers.

For linting the options I came across were Pylint, PyFlakes and pydocstyle. I choose PyLint because it's well-maintained and battle-hardened because it's the oldest. The downside of it is that PyLint is slower than other linters but atleast it will detect most of the errors.

For testing the options were unittest, nose/nose2 or pytest. I would choose either unittest or nose2 since they both seem to be simple to use. If the project would be a django project we would use Django's own tester that is based off of unittest.

There are multiple continuous integration alternatives to Jenkinks and GitHub Actions. There are CircleCI, TeamCity, Bamboo, GitLab, Buddy, Travis CI, Codeship, and so on. They range from being open source to being a bit more pricey. Also many of these seem to be for only Linux distributions but there are options that support all major OS's. Jenkins seems to be the best option because it's free and it supports all of the major OS.

Our setup would be better in a could-based environment because the project is fairly small and there is no benefit for us to use time to build a self-hosted environment.