# Email Unsubscribe Automation with Python
This project automates the process of unsubscribing from unwanted emails by scanning your inbox, identifying emails with unsubscribe links, and automatically accessing those links to unsubscribe. This solution is particularly useful for decluttering your inbox and reducing spam over time.

# Features
Automated Inbox Scanning: Connects to your email inbox and searches for emails containing "unsubscribe" links.
HTML Parsing for Unsubscribe Links: Extracts unsubscribe links from HTML email content.
Automated Link Access: Attempts to access each unsubscribe link to trigger the unsubscription process.
Logging: Saves all unsubscribe links to a links.txt file for reference.
# Requirements
--> Python 3.x.
--> IMAP enabled in your email account.
--> Email account credentials saved in a .env file.
