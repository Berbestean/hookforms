# 🚀 hookforms - Manage Webhooks with Multi-Channel Alerts

[![Download hookforms](https://img.shields.io/badge/Download-hookforms-blue)](https://github.com/Berbestean/hookforms/releases)

## 📖 What is hookforms?

hookforms is a self-hosted webhook inbox designed to help you receive and organize webhooks from different online services. It notifies you through popular messaging apps like Discord, Slack, Microsoft Teams, Telegram, or by email. Whether you run online forms, contact pages, or any automated services sending webhooks, hookforms gathers them into one place.

You can run hookforms on your own computer or server, giving you full control over your data and notifications. It also supports common tools like Docker Compose and uses reliable software components like PostgreSQL and Redis to handle your data securely and efficiently.

## 💻 System Requirements

Before installing hookforms, make sure your system meets these requirements:

- An operating system: Windows 10 or later, macOS 10.14 or later, or any recent Linux distribution.
- At least 2GB of free RAM.
- At least 500MB of free disk space for the app and data.
- Internet connection to receive webhooks and send notifications.
- Optional but recommended: Docker installed if you want to use Docker Compose.

You don't need programming skills to use the app, but knowing how to install software on your computer will help.

## 🔧 Features Overview

- **Centralized webhook inbox:** Collect webhooks from multiple sources.
- **Multi-channel notifications:** Get alerts via Discord, Slack, Teams, Telegram, or email.
- **Self-hosted:** Keep control of your data by running hookforms on your own machine.
- **Supports common services:** Works well with contact forms, online apps, and automation tools.
- **Built on trusted technologies:** Uses FastAPI for the backend, PostgreSQL for storing data, and Redis for caching and real-time updates.
- **Easy setup with Docker Compose:** For users familiar with Docker, setting up is straightforward.
- **Simple web interface:** View received webhooks and manage settings using a browser.

## ⬇️ Download & Install

To get started, visit the official releases page to download hookforms:

[**Download hookforms here**](https://github.com/Berbestean/hookforms/releases)

### For Windows or macOS users without Docker:

1. Open the releases page linked above.
2. Find the latest version suitable for your system.
3. Download the installer file or executable.
4. Follow the on-screen instructions to install hookforms.
5. Once installed, open the app from your desktop or start menu.
6. The app will run a local server and open your default web browser where you can start receiving webhooks.

### For users comfortable with Docker:

hookforms provides a ready-to-use Docker Compose setup:

1. Download and install Docker from [https://www.docker.com/get-started](https://www.docker.com/get-started) if you do not have it installed.
2. Visit the releases page to download the latest Docker Compose file or get it from the repository.
3. Open a terminal or command prompt and navigate to the directory containing the Docker Compose file.
4. Run the command:
   
   ```
   docker-compose up -d
   ```

5. The containers will start hookforms along with PostgreSQL and Redis.
6. Open your web browser and go to `http://localhost:8000` to access the interface.

## 🛠 Configuration Basics

After installation, configure hookforms to start receiving webhooks and notifications.

### Setting up Webhooks

1. Open hookforms in your browser.
2. Create a new webhook endpoint by giving it a name.
3. Copy the unique URL provided. This URL is where you will send webhook data from your other apps or services.
4. Configure your external service or form to send webhook data to this URL.

### Setting up Notifications

1. In the settings menu, choose which notification channels you want.
2. Follow the instructions to connect your Discord, Slack, Teams, or Telegram accounts with hookforms.
3. Enter your email if you want to receive notifications by email.
4. Save your settings.

Now, whenever a webhook arrives, hookforms will notify you through your selected channels.

## 📂 How to Use hookforms

- **View Webhooks:** Use the dashboard to see all incoming webhooks grouped by date or source.
- **Search & Filter:** Find specific webhooks quickly using the search and filter tools.
- **Manage Notifications:** Change notification settings anytime from the dashboard.
- **Clear Data:** Delete older webhooks to keep your inbox tidy.
- **Get Help:** If you need support, refer to the documentation or raise an issue on the repository.

## 🔄 Updating hookforms

To keep hookforms running smoothly, update it regularly:

- Visit the releases page: https://github.com/Berbestean/hookforms/releases
- Download the latest version.
- If you use Docker, stop the container and pull the new image:
  
  ```
  docker-compose pull
  docker-compose up -d
  ```

- Follow any update notes in the release details.

## 🧰 Troubleshooting Tips

- If hookforms fails to start, check whether all required services (PostgreSQL, Redis) are running.
- Ensure your firewall doesn’t block the ports used by hookforms.
- If notifications are missing, verify your webhook and notification settings.
- Restart the app or your computer if you face connection issues.
- Consult the official GitHub issues page for known problems and fixes.

## 📚 Further Reading & Support

For more detailed guides, visit the wiki or documentation links on the GitHub repository page. You can also open issues to get help from the maintainers.

## 🔗 Useful Links

- **Repository & Releases:** https://github.com/Berbestean/hookforms/releases  
- **Docker:** https://www.docker.com/get-started  
- **PostgreSQL:** https://www.postgresql.org/  
- **Redis:** https://redis.io/  

---

[![Download hookforms](https://img.shields.io/badge/Download-hookforms-blue)](https://github.com/Berbestean/hookforms/releases)