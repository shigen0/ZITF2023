# Reconnaissance

Here we are in the zira's lab. We guess that there's a use of the include fonction in php because we can go to the page that we want with the page parameter. If you're trained to php challenges you detect that there's a potential file inclusion !

![i2](21.jpg)

 # Exploitation

The exploitation part is very short because it could be made fastly with that following payload allowing us to read the login page (that we see by exploring the site) but encoded in base64

![i2](12.jpg)

The result decoded gives us the login page code (at the start of the code line 6 in the screen), with precious ids

![image](https://user-images.githubusercontent.com/75220653/226102650-8a080701-32a4-45a5-a631-b3fd1f795bf4.png)

Flagged !
