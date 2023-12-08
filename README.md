<h1>Updating a file through a Python algorithm </h1>

 

<h2>Description</h2>
In this scenario, access to restricted content within the organisation is controlled with an allow list of IP addresses. The "allow_list.txt" file identifies these IP addresses. A separate remove list identifies IP addresses that should no longer have access to this content as they may no longer be a part of the company or have moved departments, which no longer grants them access. I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access. This algorithm involved opening the file, converting it to a string to be read, and then converting this string to a list stored in the variable ip_addresses. I then iterated through the IP addresses in remove_list. With each iteration, I checked if the element was part of the ip_addresses list. If it was, I used the 'remove' function to remove the element from ip_addresses. I then used the 'join' function to convert the variable ip_addresses back into a string so that I could write over the contents of the "allow_list.txt" file with the revised list of IP addresses
<br /> .


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program Walk-through:</h2>

<p align="center">
Opening the file that contains the allow list as a string: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/Python%20-%20Create%20algorithm%20-%20task%202.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Reading the file contents: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/Python%20-%20Create%20algorithm%20-%20task%203.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Converting the string into a list using the 'split' function to make changes: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/Python%20-%20Create%20algorithm%20-%20task%204.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Iterating through the remove list using the 'for' function to create a loop for a specific sequence: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/Python%20-%20Create%20algorithm%20-%20task%205.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Removing IP addresses that are on the remove list: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/Python%20-%20Create%20algorithm%20-%20task%206.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Updating the file with the revised list of IP addresses: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/Python%20-%20Create%20algorithm%20-%20task%207.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
