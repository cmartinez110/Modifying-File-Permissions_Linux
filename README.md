<h1>Modify File Permissions Using Linux</h1>


<h2>Description</h2>
In this project, I used linux command line to navigate to a directory, list the files inside, and modify the permissions. I may add to this project to show the creation of the directory and files, as well as a user or group creation/deletion.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b> 

<h2>Environments Used </h2>

- <b>Linux</b>

<h2>Project walk-through:</h2>

<p align="center">
First, I used 'CD' to navigate to the research_team directory and 'ls - la' to list permissions of the files. 'chmod' was used to remove write for the 'other' group on project_k. Read was removed from group on project_m. Write removed from 'user' and 'group' on the secret file project_x. Finally, 'group' was given read permission to project_x: <br/>
<img src="https://i.imgur.com/dNRyxxA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, I navigated to the drafts directory and modified permissions for 'group' to no longer have execute ability:  <br/>
<img src="https://i.imgur.com/YATWwKt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To conclude this lab, I ran 'ls -la' once more to verify the modified permissions: <br/>
<img src="https://i.imgur.com/esOr8rx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
