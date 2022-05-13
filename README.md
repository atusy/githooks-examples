# A demo to introduce Git Hooks

## Prerequiste

``` bash
# Mange project with poetry
poetry install

# Apply commit template with emoji prefix
git config --local commit.template .gitmessage

# Apply Git Hooks
rsync -a .hooks/ .git/hooks
```

