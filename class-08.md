# Windows Registry 

Resources:
[Windows Registry Demystified: What You Can Do With It](https://www.howtogeek.com/370022/windows-registry-demystified-what-you-can-do-with-it/)

What is Windows Registry?
- Windows collection of several database of program configurations and setting.
- made up of multiple groups "hives" of keys and values.
    like: HKEY_CURRENT_USER
          HKEY_LOCAL_MACHINE
- program developer decides on how much to use Registry for settings, from little ----> to all settings.

How Windows Registry Work?
- user sign in to Windows > Registry loads the settings files to memory
- user launch a program > program checks the Registry stored in memory to find its configuration settings.
- user change program settings > program change settings in the registry.
- user sign out of PC and shut down > Registry saves the state of the registry to the disk.

Registry Editor - included with Windows, let the user edit egistry settings.

"Registry Hacks" - edit registry to enable hidden features and tweats specific options. Search online to find instructions on how to change settings to perform a particular task.

    Warning:
        Always perform a backup before editing registry. Editing registry is not dangerous as long as user follow legitimate instruction properly.

To edit Registry:
- open Registry Editor application
    - to do so:
        1. Windows Key + R = open run dialog
         type "regedit" > ENTER
        2. start menu > type "regedit.exe" into the search box > ENTER
    - to modify:
        - Registry will ask for a User Account Contro promt
        - user can now change the value.

.reg file 
- user can use to make thier own registry hacks.
- can contain multiple different settings that can automatically applies to favorite registry hacks and configuration. 