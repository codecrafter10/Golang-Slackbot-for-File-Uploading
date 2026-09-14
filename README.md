This repository contains a Slackbot built with Golang to enable users to upload files directly to a Slack channel. The bot leverages the Slack API to allow teams to share files quickly and efficiently, enhancing communication and collaboration within Slack.

Features
Upload files to a Slack channel with ease.
Authenticate and communicate with the Slack API using OAuth tokens.
Handle multiple file types and sizes.
Simple, modular, and easy-to-configure codebase for customizing additional functionalities.
Requirements
Golang 1.16+ installed.
A Slack workspace with admin permissions to create and manage Slack apps.
A Slack App with files:write, chat:write, and channels:read permissions.
Slack OAuth Token and Bot Token.
Getting Started
Step 1: Clone the repository
bash
Copy code
git clone https://github.com/codecrafter10/Golang-Slackbot-for-File-Uploading.git
cd Golang-Slackbot-for-File-Uploading
Step 2: Set up environment variables
Create a .env file in the root directory and add the following variables:

bash
Copy code
SLACK_OAUTH_TOKEN=xoxb-your-slack-bot-token
SLACK_CHANNEL_ID=your-slack-channel-id
Step 3: Install dependencies
Ensure Go modules are enabled and install the required packages:

bash
Copy code
go mod tidy
Step 4: Run the bot
bash
Copy code
go run main.go
The bot will now be running and listening for file uploads that can be sent to your Slack channel.

Customization
You can easily modify the Slackbot to include additional commands or actions by extending the main.go file and adding new handlers for various Slack events.

Contributing
Feel free to submit issues, fork this repository, and send pull requests. Contributions are welcome to make this Slackbot more versatile!

License
This project is licensed under the MIT License. See the LICENSE file for more details.


Contact Information 
Name: Zaid Ali
Email: Zaidali.za2635@gmail.com
