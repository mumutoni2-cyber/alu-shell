# Processes and Signals

Bash scripts exploring processes and signals.

## Tasks

### 0. What is my PID (mandatory)

Write a Bash script that displays its own PID.

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `0-what-is-my-pid`

### 1. List your processes (mandatory)

Write a Bash script that displays a list of currently running processes.

Requirements:

- Must show all processes, for all users, including those which might not have a TTY
- Display in a user-oriented format
- Show process hierarchy

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `1-list_your_processes`

### 3. Show your Bash PID made easy (mandatory)

Write a Bash script that displays the PID, along with the process name, of processes whose name contains the word `bash`.

Requirements:

- You cannot use `ps`

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `3-show_your_bash_pid_made_easy`

### 4. To infinity and beyond (mandatory)

Write a Bash script that displays `To infinity and beyond` indefinitely.

Requirements:

- In between each iteration of the loop, add a `sleep 2`

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `4-to_infinity_and_beyond`

### 5. Don't stop me now (mandatory)

We stopped our `4-to_infinity_and_beyond` process using `ctrl+c` in the previous task, there is actually another way to do this.

Write a Bash script that stops the `4-to_infinity_and_beyond` process.

Requirements:

- You must use `kill`

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `5-dont_stop_me_now`

### 6. Stop me if you can (mandatory)

Write a Bash script that stops the `4-to_infinity_and_beyond` process.

Requirements:

- You cannot use `kill` or `killall`

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `6-stop_me_if_you_can`
