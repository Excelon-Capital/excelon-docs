---
layout: doc
title: Setting up your @exceloncapital.com email
nav_order: 5
date: 2025-02-13
---

Last updated: {{ page.date | date: "%B %d, %Y" }}

1. [Introduction](#introduction)
2. [What email client to use?](#what-email-client-to-use)
3. [Setup with various email clients](#email-clients)
- [Gmail](#gmail)
- [Other email clients](#other-email-clients)
4. [Resettting your password](#resetting-your-password)

## Introduction
Excelon Capital provides all employees with an email address. You should have received an email from [it@exceloncapital.com](mailto:it@exceloncapital.com) with your login credentials. If you have not received this email, please contact the aforementioned email address.

## What email client to use?
You can use any major email client, such as Gmail, Outlook, Apple Mail, and Thunderbird. Most people use Gmail, but you will have to follow a [step-by-step process](#gmail) in order to set up Gmail with your Excelon email address. This guide makes that process easy to follow, but if you'd prefer to avoid the hassle or use other email clients, skip to the the [other email clients](#other-email-clients) section. If you have any specific concerns not covered in this article, email [it@exceloncapital.com](mailto:it@exceloncapital.com).

## Setup with various email clients
### Gmail

You will need to be logged in to an existing Gmail account for this. You will only be able to send emails using your provided Excelon email from the Gmail account you were logged into when performing these steps. You can use other Gmail accounts, but you will need to repeat these steps for each one you want to use.

1. Click on the gear icon in the top right corner of your Gmail inbox.
2. Select "*See all settings*", then navigate to the "*Accounts and Import*" tab.
3. Click on "**Add another email address**".
    ![Gmail setup step 1](/assets/gmail-setup-image-1.png)
4. You will see this form. Enter your full name and provided Excelon email address. Uncheck "*Treat as an alias*", then click "**Next Step**".

    ![Gmail setup step 2](/assets/gmail-setup-image-2.png)

5. Type `smtp.purelymail.com` into the *SMTP Server* field. Select `465` as the port. Enter your provided Excelon email address and password. Keep "*Secured connection using SSL*" checked, and click **Add Account**.

    ![Gmail setup step 3](/assets/gmail-setup-image-3.png)

6. Navigate back to the *Accounts and Import* tab and click **Add a mail account**.

    ![Gmail setup step 4](/assets/gmail-setup-image-4.png)

7. Enter your provided Excelon email address and click **Next**.

    ![Gmail setup step 5](/assets/gmail-setup-image-5.png)

8. You might see the following prompt. Just click **Next**.

    ![Gmail setup step 6](/assets/gmail-setup-image-6.png)

9. Type `pop3.purelymail.com` into the *POP Server* field. Select `995` as the port. Enter your provided Excelon email address and password. Check "*Leave a copy of retrieved message on the server.*" and "*Always use a secure connection (SSL) when retrieving mail*". You are free to check or not check the other options. Click **Add Account**.

10. You are all good to go! When you are composing an email, make sure to select your Excelon email in the "*From*" field. You will only be able to do this from the Gmail account you were logged into when performing these steps.

### Other email clients

If you are using an email client other than Gmail, all you will probably need to do is to enter your provided Excelon email address and password. There might be an indicator that shows that it's automatically downloaded the correct settings, and if there is, you can proceed. If there isn't an indicator, but you can successfully log in, everything should be good to go.

If you *are* prompted to enter server settings, use the following:

- **Incoming/POP3 mail server**: `pop3.purelymail.com`
- **Incoming/POP3 mail server port**: `995`
- **Outgoing/SMTP mail server**: `smtp.purelymail.com`
- **Outgoing/SMTP mail server port**: `465`

If you are still having trouble, contact [it@exceloncapital.com](mailto:it@exceloncapital.com).

## Resetting your password
If you need to reset your password, email [it@exceloncapital.com](mailto:it@exceloncapital.com) with either your full name or your provided Excelon email address. You will receive an email similar to the email sent with your initial login credentials.