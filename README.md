# workflow-python-lint
Only allows code that passes common linters for Python (black, etc) to merge into main

In the repo settings, open Branches, add a rule for main, and enable Require a pull request before merging.
Turn on Require status checks to pass and select Python CI or the ci job as a required check.
