> [!NOTE]
> # hack toolz

> [!IMPORTANT]
> > Create God Mode folder in your Desktop
> > Create a folder in your desktop called it
````
"GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}"
````

> [!IMPORTANT]
>> You call also run it by hold Windows Key + R to open Run command and then paste this
````
shell:::{ED7BA470-8E54-465E-825C-99712043E01C}
````

### Good to remember command with shell commands

shell:Startup - Current User Startup

shell:Common Startup - All Startup

shell:connectionsfolder - It will bring you to the network connection

shell:Downloads

shell:Favorites

shell:Profile

shell:UserProfiles

shell:Windows

> [!IMPORTANT]
> > Here are several ways to open legacy Windows panels in Windows 10 or 11 using Run commands or PowerShell:

1. Control Panel:
   - Run command: `control`
   - PowerShell command: `control panel`

2. Devices and Printers:
   - Run command: `shell:::{A8A91A66-3A7D-4424-8D24-04E180695C7A}`
   - PowerShell command: `explorer.exe shell:::{A8A91A66-3A7D-4424-8D24-04E180695C7A}`

3. System Properties:
   - Run command: `sysdm.cpl` or `systempropertiesadvanced`
   - PowerShell command: Same as Run commands

To use these commands:

1. For Run commands:
   - Press Win + R to open the Run dialog
   - Type the command and press Enter

2. For PowerShell commands:
   - Open PowerShell (right-click Start button and select "Windows PowerShell")
   - Type the command and press Enter




Here are the comprehensive list of CLSID (GUID) commands that can be used to open various special folders and features in Windows 10 and 11. These can be executed via the Run dialog (`Win + R`), PowerShell, or File Explorer.

### **General CLSID Commands**
- **God Mode (All Tasks)**: `shell:::{ED7BA470-8E54-465E-825C-99712043E01C}`
- **Control Panel**: `shell:::{21EC2020-3AEA-1069-A2DD-08002B30309D}`
- **Administrative Tools**: `shell:::{D20EA4E1-3957-11d2-A40B-0C5020524153}`
- **Computer (This PC)**: `shell:::{20D04FE0-3AEA-1069-A2D8-08002B30309D}`
- **Network Connections**: `shell:::{7007ACC7-3202-11D1-AAD2-00805FC1270E}`
- **Printers and Faxes**: `shell:::{2227A280-3AEA-1069-A2DE-08002B30309D}`
- **Recycle Bin**: `shell:::{645FF040-5081-101B-9F08-00AA002F954E}`
- **Fonts**: `shell:::{D20EA4E1-3957-11d2-A40B-0C5020524152}`
  
### **Control Panel Views**
- **Category View**: `shell:::{26EE0668-A00A-44D7-9371-BEB064C98683}`
- **Icon View**: `shell:::{5399E694-6CE5-4D6C-8FCE-1D8870FDCBA0}`

### **Special Folders**
These folders provide access to specific system directories:
  
| Folder Name                | CLSID Command                                   |
|----------------------------|------------------------------------------------|
| Documents                  | `shell:::{450D8FBA-AD25-11D0-98A8-0800361B1103}` |
| History                    | `shell:::{FF393560-C2A7-11CF-BFF4-444553540000}` |
| Network Places             | `shell:::{208D2C60-3AEA-1069-A2D7-08002B30309D}` |
| Programs Folder            | `shell:::{7BE9D83C-A729-4D97-B5A7-1B7313C39E0A}` |
| Start Menu                 | `shell:::{48E7CAAB-B918-4E58-A94D-505519C795DC}` |
| Scheduled Tasks            | `shell:::{D6277990-4C6A-11CF-8D87-00AA0060F5BF}` |
| Windows Experience Index   | `shell:::{78F3955E-3B90-4184-BD14-5397C15F1EFC}` |

### **Additional Useful Commands**
These commands target specific Windows features:
  
| Feature Name               | CLSID Command                                   |
|----------------------------|------------------------------------------------|
| Network Setup Wizard       | `shell:::{992CFFA0-F557-101A-BDC7-E6FA85DA40F4}` |
| Bluetooth Devices          | `shell:::{28803F59-D86B-4044-B681-AEDDB77B1473}` |
| Taskbar Settings           | `shell:::{0DF44EAA-CF23-D8DF-D5FE-EA8ED9B84A6C}` |

### **Usage Tips**
To use these commands:
1. Open the Run dialog (`Win + R`) or PowerShell.
2. Type the command prefixed with `shell:::`, e.g., `shell:::{20D04FE0...}`, and press Enter.
3. Alternatively, create shortcuts by naming folders with `{CLSID}`.
