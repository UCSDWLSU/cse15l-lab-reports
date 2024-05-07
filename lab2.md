<br>**ChatServer.java Code/Image:**
![Image](Lab2ChatServerCode.png)

<br>**Server.java Code/Image:**
![Image](Lab2ServerCode.png)

<br>**Image:**![Image](lab2pic1.png)
<br>**Which methods in your code are called:** `handle` method in ServerHttpHandler class
<br>**What are the relevant arguments to those methods, and the values of any relevant fields of the class:** Argument 1: `HttpExchange exchange` represents the HTTP request and response exchange / Argument 2: `URI url` the URL object representing the request URL / Field 1: `handler` field in ServerHttpHandler class, which is an instance of ChatHandler / Field 2: `chatlog` field in ChatHandler class, which stores the chat messages
<br>**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why:** The `chatlog` field in ChatHandler class changes as it concatenates the new chat message. In this case, it will append `"jpolitz: Hello\n"` to the existing `chatlog` string.

<br>**Image:**![Image](lab2pic2.png)
<br>**Which methods in your code are called:** "handle" method in ServerHttpHandler class
<br>**What are the relevant arguments to those methods, and the values of any relevant fields of the class:** Argument 1: `HttpExchange exchange` represents the HTTP request and response exchange / Argument 2: `URI url` the URL object representing the request URL / Field 1: `handler` field in ServerHttpHandler class, which is an instance of ChatHandler / Field 2: `chatlog` field in ChatHandler class, which stores the chat messages
<br>**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why:** The `chatlog` field in ChatHandler class changes as it concatenates the new chat message. In this case, it will append `"yash: How are you\n"` to the existing `chatlog` string.

<br>**Image:**![Image](privatekey.png)
<br>**Image:**![Image](publickey.png)
<br>**Image:**![Image](terminalinteraction.png)

<br>**What I learned from Week 2 and/or 3:**
Since I took this course back in Fall Quarter, I already know/remember most of the material taught in Weeks 2 and 3. The few things I forgot/don't remember are the following five commands: `echo` `>` `scp` `scp -r` `ssh-copy-id -i`. Also, I learned how to connect to a remote server on VS Code (I don't think my previous professor taught this. Either that or I don't remember him teaching this.). The things I learned last time I took it though are the following: how to connect to a server via "ssh" command / how to run a server through terminal / how to setup SSH Keys.
