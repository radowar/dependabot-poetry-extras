# dependabot-poetry-extras

Dependabot fails to keep extras in lock file

For some PRs when the repo is using Poetry to track dependencies, Dependabot will strip Redis when it is an extra of another dependency from the lockfile.
This repo is to demonstrate the issue.
