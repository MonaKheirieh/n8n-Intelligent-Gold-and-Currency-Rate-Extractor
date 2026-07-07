Intelligent Gold and Currency Rate Extractor
This project is an intelligent automation workflow designed in n8n that automatically extracts real-time market prices in Iran and sends notifications to Telegram.

🚀 How it Works
The bot runs at two scheduled times daily to fetch the following prices from tgju.org and sends them to your Telegram account:

18k Gold

Emami Gold Coin

USD

🛠 Tech Stack
n8n: Workflow automation platform.

HTTP Request Node: Used to fetch raw content from the website.

Code Node (JavaScript): Used for parsing and extracting precise data from the HTML structure.

Telegram Node: Used to deliver the final report directly to your Telegram chat.

⚙️ Setup Instructions
To implement this workflow:

Have an active n8n instance running.

Copy the JSON code provided in this repository.

Create a new Workflow in your n8n environment and Paste the JSON code.

Configure your Telegram Bot Token and Chat ID within the Telegram node credentials.

Set the workflow to Active to begin the automated schedule.
