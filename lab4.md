**STEP 4**
<br>**Command:** `ssh<space>wlsu@ieng6.ucsd.edu<enter>`
<br>**Effect:** This command connects to the remote server `ieng6.ucsd.edu` using SSH with the username `wlsu`.
<br>![Image](lab4pic1.png)

**STEP 5**
<br>**Command:** `git<space>clone<space>git@github.com:UCSDWLSU/lab7.git<enter>`
<br>**Effect:** This command clones the repository located at `git@github.com:UCSDWLSU/lab7.git` into the local directory.
<br>![Image](lab4pic2.png)

**STEP 6**
<br>**Command:** `cd<space>lab7<enter>` / `bash<space>test.sh<enter>`
<br>**Effect:** First, the command changes the current working directory to `lab7`. Then, the `bash test.sh` command runs the `test.sh` script located in the `lab7` directory.
<br>![Image](lab4pic3.png)

**STEP 7**
<br>**Command:** `vim<space>ListExamples.java<enter>` `<Down>x14<Right>x22<i><Backspace>x3<Down>x29<Left>x6<Backspace>2<Esc>:wq<enter>`
<br>**Effect:** `vim ListExamples.java` opens the file `ListExamples.java` in the Vim text editor. Navigated down 14 lines, then moved right 22 characters to position the cursor. Entered insert mode, deleted 3 characters using the backspace key. Moved down 29 lines, then left 6 characters to position the cursor again. Deleted 1 character, replaced it with the character `2`. Exited insert mode and saved the changes by writing and quitting Vim with `:wq`.
<br>![Image](lab4pic5.png)
<br>![Image](lab4pic6.png)

**STEP 8**
<br>**Command:** `bash<space>test.sh<enter>`
<br>**Effect:** This command reruns the `test.sh` script to test the changes made in the `ListExamples.java` file.
<br>![Image](lab4pic4.png)

**STEP 9**
<br>**Commands:** `git<space>add<space>ListExamples.java<enter>` / `git<space>commit<space>-m<space>"lab<space>report<space>4"<enter>` / `git<space>push<enter>`
<br>**Effects:** `git add ListExamples.java` stages the changes in ListExamples.java for the next commit. `git commit -m "lab report 4"` commits the staged changes with the message "lab report 4". `git push` pushes the local commits to the remote repository.
<br>![Image](lab4pic7.png)
