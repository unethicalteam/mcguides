### Downgrading Lunar Client's Launcher to Version 2.16.1

**Not a fan of the Lunar Client 3.0 launcher update? You're not alone.**  
Several methods are available to downgrade the launcher, ranging from easy to hard. Choose the one that suits you best.

#### Easy Difficulty
Simply use the [Lunar Client Batch Utility Downloader](https://github.com/unethicalmc/lcbud) created by us.  
This tool automates the entire downgrading process for you.

#### Normal Difficulty
Here are the steps to manually downgrade to Lunar Client v2.16.1:

First, download the required launcher files and make sure to run `Verify hashes before continuing.bat` after downloading and before proceeding with the steps below.

1. Remove your existing launcher folder from `%localappdata%\programs`.
2. Extract the downloaded `Lunar_Client_v2.16.1.zip` and locate the launcher folder.
3. Copy this folder into `%localappdata%\programs`.
4. Done!

[Download Launcher Files](https://unethical.team/lunarclient/Lunar%20Client%20v2.16.1.zip)

#### Hard Difficulty
If you prefer a more hands-on approach, follow these steps:

1. Download [Lunar Client v2.16.1](https://launcherupdates.lunarclientcdn.com/Lunar%20Client%20v2.16.1.exe). If that link is down, [use this alternative](https://unethical.team/lunarclient/Lunar%20Client%20v2.16.1.exe).
2. Install the client and wait for the update prompt to appear.
3. As soon as the update prompt shows, disconnect from the internet (disable Wi-Fi or unplug Ethernet).
4. Navigate to `%localappdata%\programs\resources` and delete the following files:
  - `app-update.yml`
  - `elevate.exe`
5. Reconnect to the internet.
6. Done!

Choose the method that best suits your needs, and enjoy your downgraded Lunar Client!
