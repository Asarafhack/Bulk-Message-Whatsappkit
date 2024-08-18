WhatsApp Bulk Messaging Automation
Automate the process of sending bulk messages via WhatsApp Web with this Python script. Perfect for businesses, marketers, or individuals who need to send messages to multiple contacts efficiently.

Features
Automated Bulk Messaging: Send messages to multiple contacts at once.
Customizable: Easily modify messages and contact lists.
User-Friendly: Simple setup with clear instructions.
Project Structure
bulk_messages.py: Main Python script for sending messages.
contacts.csv: CSV file with phone numbers and messages.
chromedriver.exe: WebDriver executable for Chrome (ensure it matches your Chrome version).
Prerequisites
Python 3.x: Ensure Python is installed on your system.
Google Chrome: The web browser used for automation.
ChromeDriver: WebDriver executable compatible with your version of Chrome.
Installation Instructions
1. Clone the Repository
In your terminal or command prompt, execute:

bash
Copy code
git clone https://github.com/yourusername/whatsapp-bulk-messaging.git
cd whatsapp-bulk-messaging
2. Install Python Packages
Install the required Python package (selenium) using pip:

bash
Copy code
pip install selenium
3. Download and Set Up ChromeDriver
Download ChromeDriver: Obtain the ChromeDriver executable that matches your Chrome version.

Place ChromeDriver: Put the chromedriver.exe file in the project directory or adjust the path in the script accordingly.

4. Prepare the Contacts File
Create a contacts.csv file in the project directory with the following format:

csv
Copy code
phone_number,message
9994371082,Hello from Python!
6369193629,This is a test message.
Configuration
Update Script: Open bulk_messages.py and ensure the path to chromedriver.exe is correctly specified.
Usage
1. Start WhatsApp Web
Open WhatsApp Web in Google Chrome.
Scan the QR code to log in to your WhatsApp account.
2. Run the Python Script
Execute the script with:

bash
Copy code
python bulk_messages.py
3. Monitor the Execution
The script will send messages to contacts listed in contacts.csv. Ensure that you keep the browser open and do not interrupt the script.

Example Output
Console Output:
plaintext
Copy code
Sending message to +919994371082...
Message sent to +919994371082
Sending message to +916369193629...
Message sent to +916369193629
WhatsApp Web: Messages will appear in the chat windows of the specified contacts.
Troubleshooting
ChromeDriver Issues: Ensure that ChromeDriver is the correct version for your Chrome installation and located in the project directory.
Selenium Errors: Ensure all required Python packages are installed and updated. Check that chromedriver.exe is correctly referenced in the script.
Notes
Compliance: Adhere to WhatsApp’s policies regarding automated messaging to prevent account suspension.
Performance: Execution time may vary based on network conditions and WhatsApp Web’s responsiveness.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Contributions are welcome! To contribute, please open an issue or submit a pull request with your improvements or bug fixes.

