# AI Scripts

This repository is a set of scripts to automate parts of my development workflow.

### Install Requirements
1. Ruby
2. llm - https://llm.datasette.io/en/stable/setup.html

## Scripts
### auto_commit
This script can be executed like this `auto_commit .`. It will:
* stage all file changes
* use llm to generate commit message based on the changes
* commit the change
* push the changes up to your remote repository

