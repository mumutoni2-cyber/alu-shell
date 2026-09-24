# init_files_variables_and_expansions

## Task 0. Alias

Write a script that creates an alias.

- Name: `ls`
- Value: `rm *`

This task demonstrates how shell aliases can override built-in commands.
Once the alias is sourced into the current shell, typing `ls` no longer
lists directory contents — it silently runs `rm *` and deletes every file
in the current directory. Running `\ls` (or `command ls`) bypasses the
alias and calls the real `ls` binary instead.

File: `0-alias`
