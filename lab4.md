**STEP 4**
<br>**Command:** `ssh wlsu@ieng6.ucsd.edu`
<br>**Effect:** This command initiates an SSH connection to the ieng6.ucsd.edu server using the username wlsu.
<br>![Image](lab4pic1.png)

**STEP 5**
<br>**Command:** `git clone git@github.com:UCSDWLSU/lab7.git`
<br>**Effect:** This command clones the repository located at git@github.com:UCSDWLSU/lab7.git into a local directory.
<br>![Image](lab4pic2.png)

**STEP 6**
<br>**Command:** `cd lab7` / `bash test.sh`
<br>**Effect:** This command runs the test.sh script in the bash shell, executing the tests defined within. Pressing <enter> executes the command, and you'll see the output of the tests, which should demonstrate that they initially fail.
<br>![Image](lab4pic3.png)

**STEP 7**
<br>**Command:** `vim ListExamples.java` / `<Down x14> <Right x22> <i> <Backspace x3> <Down x29> <Left x6> <Backspace x1> <2> <Esc> <:wq>` / `bash test.sh`
<br>**Effect:** 
<br>![Image](lab4pic5.png)
<br>![Image](lab4pic6.png)

**STEP 8**
<br>**Command:** `bash test.sh`
<br>**Effect:** 
<br>![Image](lab4pic4.png)

**STEP 9**
<br>**Commands:** `git add ListExamples.java` / `git commit -m "lab report 4"` / `git push`
<br>**Effects:** This sequence reuses the bash test.sh command by accessing the command history with the up arrow and running it again to demonstrate that the tests now pass after the changes made in Step 4.
<br>![Image](lab4pic7.png)
