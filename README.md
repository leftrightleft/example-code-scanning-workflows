# example-code-scanning-workflows

Just a bunch of example workflow files for code scanning.  Take a look at .github/workflows.

## Workflows
* [Code scanning in an alternate branch](https://github.com/leftrightleft/example-code-scanning-workflows/blob/new-branch/.github/workflows/different-branch.yml) - this workflow shows how to introduce code scanning on only a different branch. The workflow file is committed to the alternate branch and only scans on changes to that alternate branch.
* [Python excluding tests](https://github.com/leftrightleft/example-code-scanning-workflows/blob/main/.github/workflows/codeql-python-exclude-tests.yml) - this change shows how to exclude test files and specific directories.

## Config files
* [Single query from query pack](https://github.com/leftrightleft/example-code-scanning-workflows/blob/main/.github/codeql-configs/python-single-query-from-query-pack.yml) - This config file illustrates how to call a single query from a community codeql query pack
