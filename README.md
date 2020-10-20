# weeks7and8
Kali and Wordpress
Exploit 1: XSS Vulnerability in Comments
Walkthrough
1. Our malicious user "Doug Spill" types malicious script into comment (See hacking.gif)
2. When the admin goes to read the comment, the script is executed! (See hacked.gif)

Exploit 2:
1. Doug Spill, now given author commands, is able to execute arbitrary code with admin permissions by getting an admin to hover over a link he has posted (See author.png)
2. When the admin simply mouses over the text, the script is activated! (See xssalert.gif)
