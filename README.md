# Purppose of this Repo
Docksal provides an addon for Codeclimate CLI, which is great!
https://github.com/docksal/addons/tree/master/codeclimate

The purpose of this repo is to help supplement this addon with commands and config
templates to make it easier to get set up and going.

## Commands
### run-codeclimate
This command will run code climate with sensible defaults.

Examples:
```$xslt
# Run codeclimate against entire project codebase.
fin run-codeclimate
```

```$xslt
# Run codeclimate on only files which have been modified in the current feature branch. 
# --compare-branch defaults to "develop" if omitted.
fin run-codeclimate --changed-only --compare-branch=master
```