# Standard Installation Steps (100% Recognition Success)
## Step 1: Save the Theme File (Critical: Naming + Format)
1. Copy the complete JSON code above and open a local text editor (e.g., Notepad, VS Code);
2. After pasting the code, click "Save As":
   - File name: `merrynuts.ztheme` (must be exact: lowercase letters, no spaces, `.ztheme` extension);
   - Save as type: "All Files" (to avoid automatic addition of `.txt` extension);
   - Save path: Desktop (for easy access later).

## Step 2: Locate ZEditor's Custom Theme Directory (Official Specified Path)
Open the corresponding directory based on your system (manually create the `custom-themes` folder if it doesn't exist):

### Windows:
1. Press `Win + R`, enter `%APPDATA%\ZEditor\custom-themes`;
2. Press Enter to open the folder directly (if prompted "Path not found", first manually create the `ZEditor\custom-themes` folder at: `C:\Users\Your Username\AppData\Roaming\ZEditor\custom-themes`);

### macOS:
1. Open Finder, press `Command + Shift + G`;
2. Enter the path `~/Library/Application Support/ZEditor/custom-themes` and press Enter;
3. If the Library folder is not visible, first press `Command + Shift + .` to show hidden files;

### Linux:
1. Open Terminal, enter `mkdir -p ~/.config/ZEditor/custom-themes` (to create the directory);
2. Enter `cd ~/.config/ZEditor/custom-themes` to navigate to the directory, or access it via the file manager.

## Step 3: Place the Theme File
Copy the `merrynuts.ztheme` file from your Desktop to the `custom-themes` folder mentioned above (ensure no file extension errors, e.g., `merrynuts.ztheme.txt`).

## Step 4: Activate the Theme in ZEditor
1. Restart ZEditor (Critical: A restart is mandatory after manual file placement to load the new theme);
2. Open ZEditor, click "Settings" in the top menu bar → Select "Theme";
3. In the theme list, find "MerryNuts Dark" (consistent with `themes[0].name`);
4. Click to select it, and the theme will take effect immediately.
