<br>**1 (Failure-Inducing Input JUnit Test):**
<br>![Image](lab3pic1.png)

<br>**2 (Non-Failure-Inducing Input JUnit Test):**
<br>![Image](lab3pic2.png)

<br>**3 (Failing Test):**
<br>![Image](lab3pic5.png)

<br>**3 (Passing Test):**
<br>![Image](lab3pic6.png)

<br>**4 (Before Bug Fix):**
<br>![Image](lab3pic3.png)

<br>**4 (After Bug Fix):**
<br>![Image](lab3pic4.png)

<br>**5 (Why Fix Works):**
<br>
The original code was overwriting the first half of the array with the second half before those values could be swapped, thus losing the original values. The fixed version of the code uses a temporary variable to hold the value being replaced, and it only iterates over the first half of the array (`arr.length / 2`). This ensures that each element is swapped only once, preserving the order of the elements in reverse.
