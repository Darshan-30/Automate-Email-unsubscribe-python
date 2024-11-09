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

# How It Works
1. Connect to Mail Server: The connect_to_mail() function connects to your email's IMAP server and accesses your inbox.

2. Search for Unsubscribe Emails: The search_for_email() function searches your inbox for emails containing "unsubscribe" in the body.

3. Extract Unsubscribe Links: The extract_links_from_html() function parses the HTML content of each email and identifies all "unsubscribe" links.

4. Access Unsubscribe Links: The click_link() function attempts to access each unsubscribe link, simulating a click to complete the unsubscription.

5. Save Unsubscribe Links: All identified unsubscribe links are saved to a links.txt file for reference.

# Note
This project is meant for personal use to simplify email management. Always handle email credentials securely and review email provider policies to ensure compliance.
