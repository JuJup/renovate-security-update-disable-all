# #42682 - Vulnerability PRs are not created when Dependency is disabled via PackageRule

## Current behavior

No PR for pypi "requests" security update is coming.

## Expected behavior

Renovate should create a security update. In the logs the updates are found and have the attribute `"branchName": "renovate/pypi-requests-vulnerability"`.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/42682
