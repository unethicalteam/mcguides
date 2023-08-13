### downgrade lunar client's launcher to 2.16.1

**hate lunar client 3.0 launcher update? don't worry, so do we.**

1. download [Lunar Client v2.16.1](https://launcherupdates.lunarclientcdn.com/Lunar%20Client%20v2.16.1.exe) - if that link doesn't work [try this](https://cdn.discordapp.com/attachments/1081741605360377998/1140157728724094986/Lunar_Client_v2.16.1.exe) </br>
2. install the client and wait for the update prompt to come up </br>
3. **as soon as the prompt is up, disable wifi / unplug ethernet** </br>
4. delete the following from `%localappdata%\programs\resources`
  - app-update.yml
  - elevate.exe
5. enable wifi / plug in ethernet
6. profit.
