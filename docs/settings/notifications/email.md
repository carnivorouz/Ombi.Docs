# Email Notifications

## Setting up email notifications

1. Go to Email Notifications in the Ombi menu, and make sure "Enabled" is checked.  
If your mail provider requires authentication, ensure that "Enable SMTP authentication" is also checked.  
If you want to activate user email notifications as well, make sure that is checked.  
1. In the SMTP Host name or IP field, enter the address of your SMTP server.  
**Office 365:** "smtp.office365.com"  
**Gmail:** "smtp.gmail.com"  
1. In the SMTP port field enter the port your server uses.  
**Office 365:** 587  
**Gmail:** 587  
1. In the Email sender field enter the email address you wish the notifications to come from.  
Generally, this is your own email address. If you have a service such as Office 365 or Gmail then adding an an alias to your account will allow you to use a different address to your actual one.  
1. Set email recipient to any email you want to test against.  
1. Fill in your full email address and password in the username and password field.  
_**Note:**_ If you're using 2FA on your Google account you'll first need to [generate an app password.](https://support.google.com/accounts/answer/185833?hl=en) and use this in place of your normal password.

Submit these settings, and then you can run a test. This will confirm whether or not everything is working.

***

## Troubleshooting

Sometimes Gmail requires you to enable "access for less secure apps". This setting can be found [here](https://myaccount.google.com/lesssecureapps).  
If you have 2 factor authentication turned on with your Gmail account, you will need to create an App Password with Google. More information can be found [here](https://support.google.com/accounts/answer/185833)