### downgrade lunar client's launcher to 2.16.1

**hate lunar client 3.0 launcher update? don't worry, so do we.**
there's multiple ways to do this, so follow along.

**easy difficulty** </br>
just use [lunar client batch utility downloader](https://github.com/unethicalmc/lcbud) made by us. </br>
handles the process completely automatically. <3

**"normal difficulty"** </br>
the following are the lunar client v2.16.1 launcher files. </br>
be sure to run the `Verify hashes before continuing.bat` file after downloading and before doing the following:

1. delete your launcher folder from **%localappdata%\programs**
2. copy the launcher folder from **Lunar_Client_v2.16.1.7z**
3. paste it into **%localappdata%\programs**
4. profit.

[download](https://cdn.discordapp.com/attachments/1140173680018735144/1140178656438784031/Lunar_Client_v2.16.1.7z)

**"hard difficulty"** </br>
1. download [Lunar Client v2.16.1](https://launcherupdates.lunarclientcdn.com/Lunar%20Client%20v2.16.1.exe) - if that link doesn't work [try this](https://cdn.discordapp.com/attachments/1081741605360377998/1140157728724094986/Lunar_Client_v2.16.1.exe) </br>
2. install the client and wait for the update prompt to come up </br>
3. **as soon as the prompt is up, disable wifi / unplug ethernet** </br>
4. delete the following from `%localappdata%\programs\resources`
  - app-update.yml
  - elevate.exe
5. enable wifi / plug in ethernet
6. profit.
