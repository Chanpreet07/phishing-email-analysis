# phishing-email-analysis
Offline phishing analysis using Thunderbird 
# Offline Phishing Lab

This is a safe, offline lab for learning phishing email analysis and email security techniques.

All experiments are **offline and controlled , so no real users are affected.

## Screenshot

Here is an example of an email opened in Thunderbird:
#   **Email Recieved **
<img width="1920" height="1003" alt="phishing mail" src="https://github.com/user-attachments/assets/30425228-1554-4699-acbd-c105ecce5a49" />

# ** The email shows emergency which is odd and looks suspicious **
<img width="1920" height="1003" alt="phising 2" src="https://github.com/user-attachments/assets/6e856ccf-791a-4137-a15e-c39a1c1edb98" />

#** Checking the headers and trying to gain some information on who is the sender and the html script **
<img width="1920" height="1003" alt="phising 3" src="https://github.com/user-attachments/assets/f66ca208-2b15-4ec6-b0df-15afceddfb1b" />


## Example Email HTML Snippet

```html
<html>
<body>
<h2>Account Verification Required</h2>
<p>Click the link below to verify your account:</p>
<a href="http://localhost:8000/login.html">Verify Account</a>
<img src="http://localhost:8000/tracking_pixel.png" width="1" height="1" alt="">
</body>
</html>
