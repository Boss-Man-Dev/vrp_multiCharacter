# vrp_multiCharacter

A robust multi-character selection system inspired by the QB-Core framework. This system enables players to create, select, and manage multiple characters seamlessly within the game. The user interface is modeled after QB-Core’s intuitive design, providing a familiar and efficient experience for players.
Features

Multi-Character Creation: Allows players to create multiple characters with ease.
Intuitive UI: QB-Core-inspired design ensures smooth navigation and character management.
Character Switching: Quick and efficient character switching with minimized delay.
Customizable Configurations: Easy-to-configure options to tailor the system to specific server needs.

# Installation & Setup

### Download the Repository
  * Download or clone this repository to your local machine.

### Add the script to your server
  * Locate the file named `vrp_multiCharacter` in the repository, and move it to your server main directory or specific addons folder.

### Update server.cfg
  * add `ensure vrp_multiCharacter` to your server.cfg

# Special Instructions

### Compatibility with vRP 2
  * If you are not using the latest version of vRP 2, a small modification to the User.lua file may be necessary. Replacement code is included in this repository.

### Updating Core Files
  * To update core files, drag the file from the core_update folder and place it directly in the main directory of your vRP 2 framework.

# Requirements

vRP2 framework.

Note: This system is designed for performance and optimized for smooth gameplay transitions, making it an ideal choice for roleplay servers with multiple characters per player.

# Other

  ### Default command is `/character`
  * change the command name on line 18 in the server.lua
  
# Configuration
### Change spawn locations, default groups, default ped customizations
* cfg > multicharacter.lua

### Change max character enties, post addresses, character info loading oreder, character creation form fields
* cfg > html > config.js

# Screenshots

![1](https://github.com/user-attachments/assets/8960e86d-f959-47b1-b30a-f3b3d450d842)
![2](https://github.com/user-attachments/assets/3b928cd6-14a9-427e-8a38-267a5f5ac8c4)
![3](https://github.com/user-attachments/assets/5a567baf-d31f-41f4-a05f-ef1f92407a6f)
![4](https://github.com/user-attachments/assets/2a428308-24d5-4638-8371-8cf4d370a374)




