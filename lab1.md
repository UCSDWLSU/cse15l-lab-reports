**Command Run:** `cd`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because no argument is given, the absolute path/working directory is voided.
<br>**Output Error? If So Why:** No.

**Command Run:** `cd lecture1`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because a directory argument is given, the absolute path/working directory is changed to the argument.
<br>**Output Error? If So Why:** No.

**Command Run:** `cd Hello.java`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because a file argument is given, not a directory argument, the terminal says "cd: Hello.java: No such file or directory".
<br>**Output Error? If So Why:** No.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Command Run:** `ls`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because no argument is given, the files within the absolute path/working directory are listed.
<br>**Output Error? If So Why:** No.

**Command Run:** `ls lecture1`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because a directory argument is given, the files within the argument [directory] are listed.
<br>**Output Error? If So Why:** No.

**Command Run:** `ls Hello.java`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because a file argument is given, not a directory argument, the terminal says "ls: cannot access 'Hello.java': No such file or directory".
<br>**Output Error? If So Why:** No.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Command Run:** `cat`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because no argument is given, the terminal enters a loop.
<br>**Output Error? If So Why:** The ouput is an error because the terminal enters enters a loop. Commands no longer work until you exit the loop by pressing "Ctrl+C".

**Command Run:** `cat lecture1`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because a directory argument is given, not a file argument, the terminal says "cat: lecture1: Is a directory".
<br>**Output Error? If So Why:** No.

**Command Run:** `cat Hello.java`
<br>**Absolute Path Before Running Command:** /workspaces/lab1
<br>**Why The Output:** Because a file argument is given, and the file isn't within the absolute path/working directory, the file cannot be concatenated.
<br>**Output Error? If So Why:** No.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![Image](cd1.png)
![Image](cd2.png)
![Image](cd3.png)
![Image](ls1.png)
![Image](ls2.png)
![Image](ls3.png)
![Image](cat1.png)
![Image](cat2.png)
![Image](cat3.png)
