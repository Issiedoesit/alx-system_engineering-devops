## 0x02. Shell, I/O Redirections and filters

File 0-hello_world - Writes a script that prints “Hello, World”, followed by a new line to the standard output.

File 1-confused_smiley - Writes a script that displays a confused smiley "(Ôo)'

File 2-hellofile - Displays the content of the /etc/passwd file

File 3-twofiles - Displays the content of /etc/passwd and /etc/hosts

File 4-lastlines - Displays the last 10 lines of /etc/passwd

File 5-firstlines - Displays the first 10 lines of /etc/passwd

File 6-third_line - a script that displays the third line of the file iacta without using sed

File 7-file - Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line(Basically tricky file naming and escaping characters)

File 8-cwd_state - a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it

File 9-duplicate_last_line - a script that duplicates the last line of the file iacta

File 10-no_more_js - a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders

File 11-directories - a script that counts the number of directories and sub-directories in the current directory, current and parent directories are not be taken into account, hidden directories are not counted

File 12-newest_files - a script that displays the 10 newest files in the current directory, One file per line, Sorted from the newest to the oldest

File 13-unique - a script that takes a list of words as input and prints only words that appear exactly once, Input format: One line, one word, Input format: One line, one word, words are sorted

File 14-findthatword - Displays lines containing the pattern “root” from the file /etc/passwd

File 15-countthatword - Displays the number of lines that contain the pattern “bin” in the file /etc/passwd

File 16-whatsnext - Displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd

File 17-hidethisword - Displays all the lines in the file /etc/passwd that do not contain the pattern “bin”

File 18-letteronly - Displays all lines of the file /etc/ssh/sshd_config starting with a letter, including capital letters as well

File 19-AZ - Replaces all characters A and c from input to Z and e respectively

File 20-hiag - Creates a script that removes all letters c and C from input

File 21-reverse - a script that reverse its input

File 22-users_and_homes - a script that displays all users and their home directories, sorted by users, based on the the /etc/passwd file

File 100-empty_casks - a command that finds all empty files and directories in the current directory and all sub-directories
- Only the names of the files and directories should be displayed (not the entire path
- Hidden files should be listed
- One file name per line
- The listing should end with a new line
- You are not allowed to use basename, grep, egrep, fgrep or rgrep

File 101-gifs - a script that lists all the files with a .gif extension in the current directory and all its sub-directories
- Hidden files should be listed
- Only regular files (not directories) should be listed
- The names of the files should be displayed without their extensions
- The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
- One file name per line
- The listing should end with a new line
- You are not allowed to use basename, grep, egrep, fgrep or rgrep

File 102-acrostic - a script that decodes acrostics that use the first letter of each line
- The ‘decoded’ message has to end with a new line
- You are not allowed to use grep, egrep, fgrep or rgrep

** An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval

File 103-the_biggest_fan - a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests
- Order by number of requests, most active host or IP at the top
- You are not allowed to use grep, egrep, fgrep or rgrep
