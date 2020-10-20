# weeks7and8
Kali and Wordpress
Exploit 1: XSS Vulnerability in Comments
Walkthrough
1. Our malicious user "Doug Spill" types malicious script into comment
![Gif 1](https://raw.githubusercontent.com/SBourke87/weeks7and8/main/hacking.gif?token=AQVOP2ZDZDG2JIFZQ7RN5HS7R5VXA)
2. When the admin goes to read the comment, the script is executed!
![Gif 2](https://raw.githubusercontent.com/SBourke87/weeks7and8/main/Hacked!.gif?token=AQVOP2ZEFX5JMJF34BSXBSS7R5VZQ)

Exploit 2:
1. Doug Spill, now given author commands, is able to execute arbitrary code with admin permissions by getting an admin to hover over a link he has posted
![Img 1](https://raw.githubusercontent.com/SBourke87/weeks7and8/main/author.png?token=AQVOP23IIC7LS2WMJBXQDMK7R5VNY)
2. When the admin simply mouses over the text, the script is activated!
![Gif 3](https://raw.githubusercontent.com/SBourke87/weeks7and8/main/xssalert.gif?token=AQVOP27PET2ZG5NWVSS3V6S7R5VRG)
