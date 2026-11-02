GitHub Event Notifier Bot

Instant Telegram alerts for repository activities without checking web dashboards constantly.

Features
- Track pull requests and issues instantly
- Receive custom push notification filters
- Manage webhook settings via commands

Local Setup
1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Copy .env.example to .env and insert your BOT_TOKEN
4. Run python main.py

Cloud Deployment
Deploy easily on Render or Koyeb using a background worker service connected to your GitHub repository.