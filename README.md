# CubeTV

CubeTV is a desktop application built with Python & PyQt6 that allows users to manage and randomly play their favorite TV shows as if they were actually watching TV. Users can add shows, specify details like total seasons and episodes, and play random episodes while optionally avoiding reruns. <br>
**IMPORTANT:** A pre-made shows.json file is already included in the assets folder, i only included very popular shows and you can remove and edit them as you wish, or just delete the file entirely if you want.

## Features
- **Add TV Shows**: Input show title, total seasons, and select the website.
- **Play Episodes**: Randomly play episodes from the added shows.
- **Avoid Reruns**: Option to avoid playing episodes that have already been watched.
- **Open Shows File**: Easily access the JSON file containing show data.
- **Automatic Update Checking**: Every time you launch the program it checks the github for any updates, be assured that this is the only web request it makes.

## Installation
1. Download the latest release from the [releases page](https://github.com/LeRubix/CubeTV/releases/latest).
2. Extract the downloaded ZIP file.
3. Navigate to the extracted folder.

## Usage
1. Run the application `CubeTV.exe`.
2. Use the interface to add shows you want to be in the list
3. **IMPORTANT:** Open the JSON file and enter how many episodes are in each season, if you don't do this it will assume 10
4. Click the "Play" button to watch random episodes.

## File Structure
- `CubeTV.exe`: The main application file.
- `assets/`: Directory containing files necessary or made by the program.
  - `cubetv.png`: Icon for the application.
  - `shows.json`: JSON file that stores all of your shows.
  - `watched.json`: JSON file to store watched episodes to (optionally) avoid reruns. To reset you can just delete it or manually edit it.