# ALX-SWE 0x02 - SHELL REDIRECTIONS

## 0. Hello World
Write a script that prints `"Hello World"`, followed by a new line to th standard output.

**File:** `0-hello_world`

## 1. Confused Smiley
Write a script that displays a confused smiley `"(Ôo)'`.

**File:** `1-confused_smiley`

## 2. Let's display a file
Display the content pf the `/etc/passwd` file.

**File:** `2-hellofile`

## 3. What about 2?
Display the content of `/etc/passwd` and `/etc/hosts`

**File:** `3-twofiles`

## 4. Last lines of a file
Display the las 10 lines of `/etc/passwd`

**File:** `4-lastlines`

## 5. I'd prefer the first ones actually
Display the first 10 lines of `/etc/passwd`

**File:** `5-firstlines`

## 6. Line #2
Write a script that displays the third line of the file `iacta`.
- The file `iacta` will be in the working directory.
- You're not allowed to use `sed`.

**File:** `6-third_line`

## 7. It is a good file that cuts iron without making a noise
Write a shell script thta creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.

**File:** `7-file`

## 8. Save current state of directory
Write a script theat writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.

**File:** `8-cwd_state`

## 9. Duplicate last line
Write a script that duplicates the last line of the file `iacta`
- The file `iacta` will be in the working directory.

**File:** `9-duplicate_last_line`

## 10. No more javascript
Write a script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory an all its subfolders.

**File:** `10-no_more_js`

## 11. Don't just count your directories, make your directories count
Write a script that counts the number of the directories and sub-directories in the current directory.
- The current and parent directories should not be taken into account
- Hidden directories should be counted

**File:** `11-directories`

## 12. What's new
Create a script that displays the 10 newest files in the current directory.

*Requirements:*
- One file per line
- Sorted from the newest to the oldest

**File:** `12-newest_files`

## 13. Being unique is better than being perfect
Create a script that takes the list of words as input and prints only waords that appear exactly once.
- Input format*:* One line, one word
- Output format*:* One line, one word
- Words should be sorted

**File:** `13-unique`

## 14. It must be ib that file
Display lines containing the pattern `"root"` from the `/etc/passwd`

**File:** `14-findthatword`

## 15. Count that word
Display the number of lines that contain the pattern `"bin"` in the file `/etc/passwd`

**File:** `15-countthatword`

## 16. What's next?
Display lines containing the pattern `"root"` and the 3 lines afte them in the file `/etc/passwd`

**File:** `16-whatsnext`

## 17. I hate bins
Display all the lines in the file `/etc/passwd` that do not contain the pattern `"bin"`.

**File:** `17-hidethisword`

## 18. Letters only please
Display all the lines of the file `/etc/ssh/sshd_config` starting with a letter.
- include capital letters as well

**File:** `18-letteronly`

## 19. A to Z
Replace all characters `A` and `c` from the input to `Z` and `e` respectively.

**File:** `19-AZ`

## 20. Without C, you would live in hiago
Create a script that removes all letters `c` and `C` from input.

**File:** `20-hiago`

## 21. esreveR
Write a script that reverse its input.

**File:** `21-reverse`

## 22. DJ Cut Killer
Write a script that diospplays all users and their home directories, sorted by users.
- Based on the `/etc/passwd` file

**File:** `22-users_and_homes`

## 23. Empty casks make the most noise
Write a comman that finds all empty files and directories in the current directory and all sub-directories.
- Only the names of the files and directories should be displayed (not the entire path)
- Hidden files should be listed
- One file name per line
- The lsiting should end with a new line
- You are not allowed to used `basename`,`grep`,`egrep`,`fgrep` or`grep`

**File:** `100-empty_casks`

## 24. A gif is worth ten thousand words
Write a script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.
- Hidden file should be listed
- Only regular files (not directories) should be listed
- The names of the files should be displayed without their extensions
- Thef iles should be sorted by byte values, but cas-insensitive (file `aaa` should be listed before `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after `jay`)
- One file name per line
- The listing should end with a new line
- You are not allowed to used `base name`, `grep`, `egrep`, `fgrep`, or `rgrep`

**File:** `101-gifs`

## 25. Acrostic
Create a script that decodes acrostics that use the first letter of each line.
- The 'decoded' message has to end with a new line
- You are not allowed to use `grep`, `egrep`, `fgrep`, or `rgrep`

**File:** `102-acrostic`

## 26. The biggest fan
Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
- Order by number of requests, most active host or IP at the top
- You are not allowed to use `grep`, `egrep`, `fgrep`, or `rgrep`

**File:** `103-the_biggest_fan`
