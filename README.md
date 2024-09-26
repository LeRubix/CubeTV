# CubeTV

CubeTV is a desktop application built with Python & PyQt6 that allows users to manage and randomly play their favorite TV shows as if they were actually watching TV. Users can add shows, specify details like total seasons and episodes, and play random episodes while optionally avoiding reruns. <br>
> [!IMPORTANT]
> A pre-made shows.json file is already included in the assets folder, i only included very popular shows and you can remove and edit them as you wish, or just delete the file entirely if you want.

## Features
- **Add TV Shows**: Input show title, total seasons, and select the website.
- **Play Episodes**: Randomly play episodes from the added shows.
- **Avoid Reruns**: Option to avoid playing episodes that have already been watched.
- **Enable/Disable shows in the list**: Customize your viewing experience by only enabling what you want to watch at any point.
- **Open Shows File**: Easily access the JSON file containing show data.
- **Automatic Update Checking**: Every time you launch the program it checks GitHub for any updates.
- **Discord Rich Presence**: Allows your friends to see what you're currently watching on CubeTV, you can disable it.
- **Watch History**: View a list of your watch history and when you watched it.
- **Watch Shows in Order**: If you don't like randomising episodes, you can decide to watch a random show in order, starting from episode 1.
- **Colourful Themes**: Instead of the default purple, you can choose one of many colourful themes to spice up your UI!

## Installation
1. Download the latest release from the [releases page](https://github.com/LeRubix/CubeTV/releases/latest).
2. Extract the downloaded ZIP file.
3. Navigate to the extracted folder.

## Usage
1. Run the application `CubeTV.exe`.
2. Use the interface to add shows you want to be in the list; I recommend using the show's actual title for the title so the API can retrieve the episode numbers.
3. Click the "Play" button to watch random episodes.
4. Enable/Disable specific shows at any point in the "Enabled Shows" tab.

## File Structure
- `CubeTV.exe`: The main application file.
- `assets/`: Directory containing files necessary or made by the program.
  - `cubetv.png`: Icon for the application.
  - `shows.json`: JSON file that stores all of your shows. A pre-made one is included in the assets folder. Edit/Delete it if you want.
  - `watched.json`: JSON file to store watched episodes to (optionally) avoid reruns. To reset you can just delete it or manually edit it.
  - `history.json`: JSON file that stores all of your watch history.
  - `settings.conf`: Config file that stores your settings.

![image](https://github.com/user-attachments/assets/aa21aeac-9bae-46d3-998f-228c46d59bf6)
![image](https://github.com/user-attachments/assets/ed725010-9276-4583-bf80-d4e67a3a5f99)
![image](https://github.com/user-attachments/assets/891a595f-1849-441e-9761-5b036a014b22)
