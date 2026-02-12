\\# Option/Settings System - Roblox Portfolio Project







\\##  Overview



A comprehensive, polished settings menu system for Roblox games featuring smooth animations, persistent preferences, and performance optimization tools.







\\## Features



\\- Low Graphics Mode - Disables bloom, depth of field, sun rays, blur effects, and global shadows for potato computers.



\\- Texture Management - Dynamically removes textures to boost FPS on low-end devices.



\\- Chat Toggle - Hide chat functionality for parental control and streamers.



\\- Music Mute - Independently mutes background music while keeping UI sound effects active.



\\- Smooth Animations - Tween-based hover effects (1.01x scale) with click feedback. (2px press)



\\- ZIndex Management - Proper layer hierarchy ensuring menus always display correctly.



\\- Sound Feedback - Satisfying hover and click sounds for all interactive elements.





\\## Architecture



\\- \\\*\\\*Client-Side\\\*\\\*: LocalScripts handling UI animations, user input, and local preference toggles.



\\- \\\*\\\*Server-Side\\\*\\\*: (Optional) DataStore integration for saving player settings across sessions.



\\- \\\*\\\*Performance\\\*\\\*: Optimized descendant scanning with instance caching for texture management.



\\- \\\*\\\*Data\\\*\\\*: DataStore integration for player preferences.







\\## Installation



1\\. Clone this repository.



2\\. Open the `.rbxl` file in Roblox Studio (demo file available in Releases).



3\\. Import the MenuGui "ScreenGui" into StarterGui.



4\\. Explore the script structure in `/src`.



5\\. Run the game and access settings via the SettingsButton.





\\## Project Structure

Workspace\\StarterGui/



MenuGui/

├── MenuGuiScript (LocalScript)    # Main settings logic

├── ButtonContainer/

│   └── SettingsButton (ImageButton)  # Opens settings menu

├── SettingsFrame/                 # Main settings panel

│   ├── BackButton               # Closes settings

│   └── SettingsScroller/        # Scrollable settings container

│       ├── LowGraphicsSetting/  # Graphics toggle

│       ├── TexturesSetting/     # Texture toggle  

│       ├── ChatSetting/         # Chat toggle

│       └── MusicSetting/        # Music mute toggle

├── Sounds/

│   ├── ClickSound (Sound)       # Button click feedback

│   └── HoverSound (Sound)       # Button hover feedback

└── AmbianceMusic (Sound)        # Background music (auto-muted by MusicSetting)





\\## Demo



\\\[Add YouTube video link here demonstrating the system]







\\##Tech Stack







\\\*\\\*Platform \\\& Language\\\*\\\*



\\- Roblox Studio



\\- Lua 5.1 (Roblox-flavored)







\\\*\\\*Core Services\\\*\\\*



\\- TweenService (Smooth UI animations)



\\- LightingService (Graphics management)



\\- StarterGui (Core GUI controls)



\\- RunService (Heartbeat for animations)







\\\*\\\*UI/UX Features\\\*\\\*



\\- Responsive hover scaling (1.01x)



\\- Tactile click feedback (2px depression)



\\- Smooth slide toggles with color transitions



\\- Proper ZIndex layering



\\- Screen-relative positioning





\\\*\\\*Additional Expertise\\\*\\\*



\\- Client-Server security models



\\- Optimized DataStore usage patterns



\\- Efficient networking strategies







\\## 📜 License



This portfolio project is licensed under the MIT License.







\\\*\\\*Note:\\\*\\\* This is a demonstration project for portfolio purposes. The code is provided to showcase development skills.







\\# Author



\\\[I03I] - Portfolio Projects



\\- Demo Video: \[Coming Soon]

\\- Portfolio Contact: trafonbusiness.com

