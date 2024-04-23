**Command Run:** `cd`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because no argument is given, the absolute path/working directory is set to the home directory.
<br>**Output Error? If So Why:** No.
<br>**Image:** ![Image](cd1.png)

**Command Run:** `cd lecture1`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because a directory argument is given, the absolute path/working directory is changed to the argument.
<br>**Output Error? If So Why:** No.
<br>**Image:** ![Image](cd2.png)

**Command Run:** `cd Hello.java`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because a file argument is given, not a directory argument, the terminal says "cd: Hello.java: No such file or directory".
<br>**Output Error? If So Why:** The output is an error because the argument, Hello.java, is a file not a directory, and you can't cd into a file.
<br>**Image:** ![Image](cd3.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Command Run:** `ls`
<br>**Absolute Path Before Running Command:** `workspaces/lab1`
<br>**Why The Output:** Because no argument is given, the files within the absolute path/working directory are listed.
<br>**Output Error? If So Why:** No.
<br>**Image:** ![Image](ls1.png)

**Command Run:** `ls lecture1`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because a directory argument is given, the files within the argument [directory] are listed.
<br>**Output Error? If So Why:** No.
<br>**Image:** ![Image](ls2.png)

**Command Run:** `ls Hello.java`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because a file argument is given, not a directory argument, the terminal says "ls: cannot access 'Hello.java': No such file or directory".
<br>**Output Error? If So Why:** The output is an error because the argument, Hello.java, is a file not a directory, and you can't ls a file.
<br>**Image:** ![Image](ls3.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Command Run:** `cat`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because no argument is given, the cat command will read data from its standard input and write them to its standard output.
<br>**Output Error? If So Why:** No.
<br>**Image:** ![Image](cat1.png)

**Command Run:** `cat lecture1`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because a directory argument is given, not a file argument, the terminal says "cat: lecture1: Is a directory".
<br>**Output Error? If So Why:** The output is an error because the argument, lecture1, is a directory not a file, and you can't cat a directory.
<br>**Image:** ![Image](cat2.png)

**Command Run:** `cat Hello.java`
<br>**Absolute Path Before Running Command:** `/workspaces/lab1`
<br>**Why The Output:** Because a file argument is given, and the file isn't within the absolute path/working directory, the file cannot be concatenated.
<br>**Output Error? If So Why:** No.
<br>**Image:** ![Image](cat3.png)
