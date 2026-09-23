# alu-shell

This repository contains shell scripting exercises covering I/O redirections, filters, and other Bash fundamentals.

## io_redirections_and_filters

### Task 0
File: `0-hello_world`

Script that prints "Hello, World", followed by a new line, to the standard output.

### Task 1
File: `1-confused_smiley`

Script that displays a confused smiley: `"(Ôo)'`.

### Task 2
File: `2-hellofile`

Script that displays the content of the `/etc/passwd` file.

### Task 3
File: `3-twofiles`

Script that displays the content of `/etc/passwd` and `/etc/hosts`.

### Task 4
File: `4-lastlines`

Script that displays the last 10 lines of `/etc/passwd`.

### Task 5
File: `5-firstlines`

Script that displays the first 10 lines of `/etc/passwd`.

### Task 6
File: `6-third_line`

Script that displays the third line of the file `iacta`, without using `sed`.

### Task 7
File: `7-file`

Script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` followed by a new line.

### Task 8
File: `8-cwd_state`

Script that writes the result of `ls -la` into the file `ls_cwd_content`. If the file already exists, it is overwritten; if it doesn't exist, it is created.

### Task 9
File: `9-duplicate_last_line`

Script that duplicates the last line of the file `iacta`.

### Task 10
File: `10-no_more_js`

Script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.

### Task 11
File: `11-directories`

Script that counts the number of directories and sub-directories in the current directory. The current and parent directories are not counted, and hidden directories are included.

### Task 12
File: `12-newest_files`

Script that displays the 10 newest files in the current directory, one per line, sorted from the newest to the oldest.

### Task 13
File: `13-unique`

Script that takes a list of words as input (one word per line) and prints only the words that appear exactly once, sorted, one per line.

### Task 14
File: `14-findthatword`

Script that displays lines containing the pattern "root" from the file `/etc/passwd`.

### Task 15
File: `15-countthatword`

Script that displays the number of lines that contain the pattern "bin" in the file `/etc/passwd`.

### Task 16
File: `16-whatsnext`

Script that displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd`.

### Task 17
File: `17-hidethisword`

Script that displays all the lines in the file `/etc/passwd` that do not contain the pattern "bin".

### Task 18
File: `18-letteronly`

Script that displays all the lines of the file `/etc/ssh/sshd_config` starting with a letter (including capital letters).

### Task 19
File: `19-AZ`

Script that replaces all characters `A` and `c` from input with `Z` and `e` respectively.

### Task 20
File: `20-hiago`

Script that removes all letters `c` and `C` from input.
