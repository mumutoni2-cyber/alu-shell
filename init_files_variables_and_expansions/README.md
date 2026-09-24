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

## Task 2. Best friend

Add `/action` to the `PATH`.

`/action` should be the last directory the shell looks into when looking for a program.

File: `2-path`

## Task 3. If the path be beautiful, let us not ask where it leads

Create a script that counts the number of directories in the `PATH`.

File: `3-paths`

## Task 4. Global variables

Create a script that lists environment variables.

File: `4-global_variables`

## Task 6. Create a local variable

Create a script that creates a new local variable.

- Name: `BEST`
- Value: `School`

File: `6-create_local_variable`

## Task 8. Unique

Write a script that prints the result of the addition of 128 with the
value stored in the environment variable `TRUEKNOWLEDGE`, followed by a
new line.

File: `8-true_knowledge`

## Task 9. Divide and rule

Write a script that prints the result of `POWER` divided by `DIVIDE`,
followed by a new line.

- `POWER` and `DIVIDE` are environment variables

File: `9-divide_and_rule`

## Task 10. Love exponent breath

Write a script that displays the result of `BREATH` to the power `LOVE`.

- `BREATH` and `LOVE` are environment variables
- The script should display the result, followed by a new line

File: `10-love_exponent_breath`

## Task 7. Create a global variable

Create a script that creates a new global variable.

- Name: `BEST`
- Value: `School`

File: `7-create_global_variable`
