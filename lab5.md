**1. The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some sense of what the failure-inducing input is.**
<br>**Title:** Issue with list-examples-grader Script Execution
<br>**Post:**
Hi everyone,

I’m encountering an issue while trying to run the grading script for our list examples project. When I run `grade.sh`, I receive an unexpected output and the grading process doesn't complete as expected. Attached is a screenshot of the terminal output I get.

From what I can tell, it seems like there might be an issue with the file paths or maybe the Java compilation. Has anyone experienced something similar or has an idea of what might be going wrong?

**Screenshot:**
imgtxt

**2. A response from a TA asking a leading question or suggesting a command to try.**
<br>**Title:** Re: Issue with list-examples-grader Script Execution
<br>**Post:**
Hi Wayne,

It looks like there might be an issue with how the paths are set in your script. Could you try running the following command and share the output?

`ls -R'

This will list all the files and directories recursively from your current location. It might help us identify if there’s a discrepancy in your file structure.

**3. Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is.**
<br>**Title:** Re: Issue with list-examples-grader Script Execution
<br>**Post:**
Hi TA Edwin,

Thanks for the suggestion. Here’s the output from running `ls -R`.

It seems like the `ListExamples.java` file is located in a different directory than the script expects. The script is looking for the file in the `src` directory, but it’s actually in the `examples` directory.

The bug is likely due to incorrect file paths in the `grade.sh` script. I’ll try updating the paths and see if that resolves the issue.

**Screenshot:**
imgtxt

**4a.** The file & directory structure needed

**Screenshot:**
imgtxt

**4b.** The contents of each file *before* fixing the bug

**ListExamples.java**
imgtxt

**TestListExamples.java**
imgtxt

**grade.sh**
imgtxt

**4c.** The full command line (or lines) you ran to trigger the bug

`bash grade.sh`

**4d.** A description of what to edit to fix the bug

Update the file paths in the `grade.sh` script to correctly point to the `examples` directory where `ListExamples.java` is located.

<br>**Corrected `grade.sh`**
imgtxt

By changing the path from `src/ListExamples.java` to `examples/ListExamples.java`, the script will now correctly locate and compile the necessary Java files, allowing the tests to run successfully.
