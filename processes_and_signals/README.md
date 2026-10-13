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

### 7. Highlander (mandatory)

Write a Bash script that displays:

- `To infinity and beyond` indefinitely
- With a `sleep 2` in between each iteration
- `I am invincible!!!` when receiving a `SIGTERM` signal

Make a copy of your `6-stop_me_if_you_can` script, name it `67-stop_me_if_you_can`, that kills the `7-highlander` process instead of the `4-to_infinity_and_beyond` one.

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `7-highlander` (and `67-stop_me_if_you_can`)

### 8. Beheaded process (mandatory)

Write a Bash script that kills the process `7-highlander`.

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `8-beheaded_process`

### 10. Process and PID file (mandatory)

Write a Bash script that:

- Creates the file `/var/run/myscript.pid` containing its PID
- Displays `To infinity and beyond` indefinitely
- Displays `I hate the kill command` when receiving a SIGTERM signal
- Displays `Y U no love me?!` when receiving a SIGINT signal
- Deletes the file `/var/run/myscript.pid` and terminates itself when receiving a SIGQUIT or SIGTERM signal

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `10-process_and_pid_file`

### 11. Manage my process (mandatory)

Write a `manage_my_process` Bash script that indefinitely writes `I am alive!` to `/tmp/my_process`, pausing 2 seconds between each message.

Write a Bash (init) script `11-manage_my_process` that manages it, with the arguments `start`, `stop` and `restart`, using the PID file `/var/run/my_process.pid`. Any other argument displays `Usage: manage_my_process {start|stop|restart}`.

- **Repo:** `alu-shell`
- **Directory:** `processes_and_signals`
- **File:** `11-manage_my_process`, `manage_my_process`
