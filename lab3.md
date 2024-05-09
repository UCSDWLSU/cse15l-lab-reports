<br>**1:**
<br>![Image](lab3pic1.png)

<br>**2:**
<br>![Image](lab3pic2.png)

<br>**3(fail):**
<br>![Image](lab3pic5.png)

<br>**3(success):**
<br>![Image](lab3pic6.png)

<br>**4(before):**
<br>![Image](lab3pic3.png)

<br>**4(after):**
<br>![Image](lab3pic4.png)

<br>**5:**
<br>
The original code was overwriting the first half of the array with the second half before those values could be swapped, thus losing the original values. The fixed version of the code uses a temporary variable to hold the value being replaced, and it only iterates over the first half of the array (`arr.length / 2`). This ensures that each element is swapped only once, preserving the order of the elements in reverse.
