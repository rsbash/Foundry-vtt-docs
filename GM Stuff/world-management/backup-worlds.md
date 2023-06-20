Whether updating Foundry or simply as a precaution, periodically backup worlds to prevent the loss of important data.

> The instruction below is sourced heavily from [Foundry VTT documentation](https://foundryvtt.com/article/user-data-backup/).

## Backup Foundry Game Worlds

Backup is a two-step process:

1. Locate your user data.
2. Copy the `Data`, `Config`, and `Logs` folders.

Depending on your operating system, your User Data folder may be located in different locations. The defaults are:

Windows 10 - `%localappdata%\FoundryVTT\`
macOS - `~/Library/Application Support/FoundryVTT`
Linux - `~/.local/share/FoundryVTT`


## Restore Foundry Game Worlds

Replace the `Data`, `Config`, and `Logs` folders to fully restore a Foundry VTT game world. 

It is possible to move data during the process of restoration 

Moving your User Data to a new location requires just a few simple steps. Before you do so, you should first perform a complete backup of your existing data using the steps above.


### Moving User Data For Windows

1. Launch Foundry VTT and right-click its icon in the taskbar. Click on 'Browse User Data.'
2. Close Foundry VTT. Open a new file browser window and navigate to where you wish to move your data to. Create a new folder.
3. Copy the 'Data', 'Config', and 'Logs' folders to this new location. Keep this window open. We will refer to this location as the "old location."
4. Launch Foundry VTT and navigate to the Configuration screen.
5. Under 'User Data Path', enter the path to your new User Data location. Click on 'Save Configuration.' Foundry VTT will shut down.
6. Re-Launch Foundry VTT and check if your worlds are present. If they're not, double check the path you set in the Configuration screen.
7. If your worlds are present, shut down Foundry VTT. Temporarily move the 'Data', 'Config', and 'Logs' folders from the old location to another folder.
8. Launch Foundry VTT again. If your worlds are present, you have successfully moved your User Data to a new location.
9. If your worlds do not show up after completing these steps, double check that the assigned User Data Path is correct and that the folders in this location are not empty.


### Moving User Data For macOS

1. Open Foundry VTT. Navigate to the 'Configuration' screen. Copy the filepath from the field next to 'User Data Path.'
2. Close Foundry VTT. Open Finder, click the 'Go' menu, choose 'Go to folder...', and paste in the path you copied.
3. Copy the 'Data', 'Config', and 'Logs' folders to this new location. Keep this window open. We will refer to this location as the "old location."
4. Launch Foundry VTT and navigate to the Configuration screen.
5. Under 'User Data Path', enter the path to your new User Data location. Click on 'Save Configuration.' Foundry VTT will shut down.
6. Re-Launch Foundry VTT and check if your worlds are present. If they're not, double check the path you set in the 'Configuration' screen.
7. If your worlds are present, shut down Foundry VTT. Temporarily move the 'Data', 'Config', and 'Logs' folders from the old location to another folder.
8. Launch Foundry VTT again. If your worlds are present, you have successfully moved your User Data to a new location.
9. If your worlds do not show up after completing these steps, double check that the assigned User Data Path is correct and that the folders in this location are not empty.


### Moving User Data For Linux

1. Open Foundry VTT. Navigate to the 'Configuration' screen. Copy the filepath from the field next to 'User Data Path.'
2. Close Foundry VTT and open a file browser window enter in the path you copied.
3. Copy the 'Data', 'Config', and 'Logs' folders to this new location. Keep this window open. We will refer to this location as the "old location."
4. Launch Foundry VTT and navigate to the Configuration screen.
5. Under 'User Data Path', enter the path to your new User Data location. Click on 'Save Configuration.' Foundry VTT will shut down.
6. Re-Launch Foundry VTT and check if your worlds are present. If they're not, double check the path you set in the Configuration screen.
7. If your worlds are present, shut down Foundry VTT. Temporarily move the 'Data', 'Config', and 'Logs' folders from the old location to another folder.
8. Launch Foundry VTT again. If your worlds are present, you have successfully moved your User Data to a new location.
9. If your worlds do not show up after completing these steps, double check that the assigned User Data Path is correct and that the folders in this location are not empty.