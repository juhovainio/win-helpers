# win-helpers
Collection of scripts and guidelines for setting up remote operated Windows machines

## Checking restart logs
1. Press `Win+R`
2. Type `eventvwr`
3. Windows Logs -> Filter -> Code: `1074`

## Preventing automatic restarts on scheduled automatic updates
1. `Win+R`
2. Type `gpedit.msc`
3. Administrative Templates -> Windows Components -> Windows Update
4. Enable "No auto-restart with logged on users for scheduled automatic updates installations"

## Define Windows startup app/scripts
1. Press `Win+R`
2. Type `shell:startup`
3. Create shortcut to app/script in the folder
