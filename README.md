# RPA-EXPERIMENT-10
### Name: SARGURU K
### Reg No: 212222230134
## AIM:
   To create a UiPath workflow that sends an email using a Gmail account through SMTP or Outlook activities.
   
## ALGORITHM:
Step 1: Setup Gmail for SMTP Access Enable 2-Step Verification on your Gmail account. Go to https://myaccount.google.com/apppasswords Generate an App Password (e.g., for "Mail on Windows Computer"). Copy and save the app password securely — you’ll use it in UiPath.
Step 2: Create a New UiPath Process Open UiPath Studio and create a new process named GmailSenderBot.
Step 3: Use Send SMTP Mail Message Drag the Send SMTP Mail Message activity (found in UiPath.Mail.SMTP.Activities).
Fill in the properties:
* Property Value To "recipient@example.com" Subject "Test Email from UiPath" Body "Hello! This is a test email from UiPath automation." Port 587 Server "smtp.gmail.com" Email "your_email@gmail.com" Password Paste your Gmail App Password securely SecureConnection StartTls
Step 4: Run the Workflow Save and run the bot.
* The email will be sent to the recipient from your Gmail account.

## PROGRAM:
![image](https://github.com/user-attachments/assets/ac50d002-a54e-480c-b0ba-1896058e15b9)
![Screenshot 2025-05-24 212313](https://github.com/user-attachments/assets/c96e6671-3070-482b-95cf-c4e60d7301be)

## OUTPUT:
![Screenshot 2025-05-24 212654](https://github.com/user-attachments/assets/6bf8f10e-dee9-4403-8f24-cb181197fe81)

## RESULT:
The UiPath workflow successfully sends an email from a Gmail account using SMTP configuration.
