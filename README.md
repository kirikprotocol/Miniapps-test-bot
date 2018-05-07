# Miniapps test bot

The bot’s language is Russian. This bot exemplifies usage of the following plugins:

    - msisdn confirmation
    - secret input
    - send file
    - Smartcash
    - tiPay payment

Msisdn-confirmation

It gives an example of how to use Verification by MSISDN plugin. The bot’s goal is to get the user’s mobile phone number verified.

To verify the phone number the bot offers several options:

-    c2s
-    SMS
-    USSD
-    discharge previous verifications.

Secret-input-sample

It shows how secret input plugin is used.
The bot provides the user with means to input a password in a Telegram chat, so that it is not saved in the chat history.
At the first page the bot informs the user that the next is the password input page. The next page contains the password input field and buttons “Done”, “Cancel”. If the password was input, the bot confirms successful password input.

Send file

The bot exemplifies the usage of Sender plugin. The bot offers to send:
- BASE64 image
- An image from a static resource
- Location
- PDF file


