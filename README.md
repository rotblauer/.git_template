`git config --global init.templatedir '~/.git_template'`

pre-push tweeter hook depends on twitter cli client [t](https://github.com/sferik/t)

Note that re-running `git init` in pre-existing git repos will
non-destructively update hooks such as thus. But it will get rid of the .sample
hooks.
