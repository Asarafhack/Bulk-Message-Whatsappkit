# Bulk-Message-Whatsappkit
WhatsApp Bulk Message Sender This repository provides instructions for setting up and running a Python script to send bulk WhatsApp messages using WhatsApp Web. This setup is compatible with Windows, Linux, and macOS.
Prerequisites
Python 3.x: Ensure Python is installed on your system.
Google Chrome: Required for WhatsApp Web.
WhatsApp Web: Must be logged in on your Chrome browser.
Installation Instructions
1. Clone the Repository
Open a terminal or command prompt and run:

bash
Copy code
git clone https://github.com/yourusername/whatsapp-bulk-message-sender.git
cd whatsapp-bulk-message-sender
2. Install Python Packages
Ensure you have pip installed. Install the required Python packages by running:

bash
Copy code
pip install pywhatkit pandas
3. Prepare Your CSV File
Create a CSV file named contacts_and_messages.csv in the repository directory. The CSV should be formatted as follows:

csv
Copy code
PhoneNumber,Message
9994371082,Hello! This is a test message.
6369193629,Hi there! How are you doing?
4. Configure WhatsApp Web
Open WhatsApp Web in Google Chrome.
Log in by scanning the QR code with your mobile WhatsApp.
Ensure your contacts and chat list are visible in WhatsApp Web.
Running the Script
Save the Python Script

Save the provided Python script as whatsapp_bulk_sender.py in your repository directory.

Execute the Script

Run the script using Python. In your terminal or command prompt, execute:

bash
Copy code
python whatsapp_bulk_sender.py
Monitor the Execution

The script will send messages as specified in your CSV file. Ensure WhatsApp Web remains open during execution to allow messages to be sent successfully.

Output
Console Output: The script will print messages to the console indicating which contact the message is being sent to.
WhatsApp Web: Messages will be sent to the contacts listed in your CSV file. Monitor WhatsApp Web to verify that messages are delivered.
Troubleshooting
Message Sending Issues: Ensure WhatsApp Web is open and logged in. Adjust the time.sleep() duration in the script if messages are not sent correctly.
Driver Errors: If encountering issues related to the browser driver, ensure Google Chrome is installed and up to date.
Notes
WhatsApp Policies: Use the script responsibly. Excessive messaging may lead to temporary or permanent bans.
Security: Be cautious with automation tools. Ensure they are from trusted sources.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.
