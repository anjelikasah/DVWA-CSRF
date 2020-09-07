# DVWA CSRF writeup
## Low Security
Fow low sercurity, run the file <b>script.html</b> on any web browser. Click on the <b>Change Password</b> button and your password will be changed.

## Medium Security
<p>For Medium Security, create a directory and name it <b>127.0.0.1</b>. Add <b>script.html</b> file inside the directory. Run the html code through your local server (localhost) so that you get 
  http://localhost/127.0.0.1/script.html
  as the URL. 
  Now click on the <b> Change Password</b> button and your password will be changed.
  
 <br><br>
 <b>Note:</b> Inside script.html, change the action address to your dvwa csrf address and value of new password and confirm password according to your wish.
