Natas-Solutions
==========================

Natas2
--------------------------



Step 1: <b><br>
In the first step, i examined the code of the webpage like normal, but this time, I had to be a little bit more clever about finding the password. Notice a comment that says, "<!-- This stuff in the header has nothing to do with the level -->"
<b>
My natural reaction to that line was, "I'll see about that", and it turns out in the end it was telling the truth. Examining the code within the header is interesting, but not what we're looking for.

Step 2: <b><br>
After I concluded that the header code was useless, I looked further down the code and saw a path to an image file, "img src="files/pixel.png">".

Step 3: <b><br>
Since I have some expirience with web servers, I knew i could append a path at the end of the url to access files. The pixel.png file itself isn't important, but the fact that it's contained within a folder named "files"

Step 4: <b><br>
After navagating to the files page, I saw users.txt, and within that file was the password to the next level.
