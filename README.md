# Quick-Tools

Quick-Tools is a multifunctional system management utility that integrates practical features such as shutdown, restart, network testing, scheduled tasks, and file synchronization. It also provides detailed operation logs and a management interface. The software includes a built-in license verification mechanism to ensure authorized use and supports startup autorun and system tray operation. It is compatible with Windows systems and requires the .NET Framework 4.8 runtime environment.

## Software Interface Preview
![Software Interface Preview](https://zero001.icu/webdav/document/2025-01-05.png?v={{TIMESTAMP}})
<small>The image has been updated.</small>

## Download & Installation
- **Download Link**: [Click to Download](https://github.com/boy86001/Quick-Tools/releases)
- **Installation Requirements**:
  - Supports Windows systems and requires the .NET Framework 4.8 environment.
  - If .NET 4.8 is not installed, the software will redirect you to the [.NET Framework 4.8 download page](https://dotnet.microsoft.com/download/dotnet-framework/net48). Please follow the instructions to complete the installation.
  - Installation password: `3004`

## User Guide
1. **Shutdown/Restart**  
   Click the "Shutdown" or "Restart" button to immediately perform the operation. You may enable the optional 3-second countdown.

2. **Scheduled Tasks**  
   Set your target time in the "Select Shutdown Time" section, choose "One-time" or "Daily Execution" mode, and click "Set Scheduled Shutdown" to create a task.  
   - **Tasks Run Independently**: Scheduled shutdown tasks run independently of the application. Even if the software is closed, the task remains active in the system — a key feature of Quick-Tools.  
   - **Shutdown Reminders & Cancellation**: At the scheduled time, a reminder window will pop up to alert the user before the shutdown executes. The user can confirm or cancel the action to prevent data loss or accidental shutdown.

3. **Ping Test**  
   Click the "Ping Test" button to automatically read the `IP_Z.xml` file in the installation directory and test the listed or custom IP addresses. Results show latency and connection status. To update test IPs, edit the `IP_Z.xml` file and restart the software.

4. **File Synchronization**  
   Click "File Sync" to open the sync interface. After selecting source and destination folders, you can add tasks, view or remove them from the task list, and enable auto-run on startup for each task.

5. **License Verification**  
   The software uses AES encryption to protect license data and binds it to a specific machine, ensuring it runs only on authorized devices.  
   - **MD5 (Quick-Tools 2.4)**: d85c8c2e3ddbc00ad0ef16afda7b6e73

6. **System Tray Icon**  
   When minimized, the main window hides automatically and displays a tray icon. Right-click the icon for options such as "Show Main Interface" or "Exit". You can also double-click the icon to quickly restore the interface.

## Notes
- Please run the software with administrator privileges to ensure normal operation of shutdown, restart, scheduled tasks, and file sync features.
- Shutdown and restart features will forcibly close unsaved work — remember to save your progress in advance.
- Make sure the source and destination folder paths are correct when syncing files to prevent data loss.
- Do not tamper with the license information. Ensure the software is properly authorized to run.

## Author
**YiSanYuan**  
Thank you for using Quick-Tools. If you have any issues or suggestions, please contact us via GitHub Issues or the author's homepage.
