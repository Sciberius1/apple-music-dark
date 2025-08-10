# Dark Mode for Apple Music for Linux

This package enables a persistent dark mode for the Apple Music for Linux application. It updates the necessary configuration files for both GTK3 and GTK4, and switches the app's theme to dark.

## Features
- Dark mode for menu bars, backgrounds, and playlists (where supported)
- Compatible with both GTK3 and GTK4
- Simple installation

## Installation
1. Download and expand the provided zip file.
2. Copy the `apple-music-for-linux` folder inside the expanded zip to your installation location, replacing the existing files if prompted.
3. Enjoy your new dark mode experience!

## Files Included
- `current/.config/gtk-3.0/settings.ini`: Enables dark mode for GTK3 apps
- `current/.config/gtk-4.0/settings.ini`: Enables dark mode for GTK4 apps
- `common/theme`: Sets the app theme to dark

## Notes
- Restart the application after copying the files to see the changes.
- If you want to revert to light mode, change `dark` back to `light` in `common/theme` and set `gtk-application-prefer-dark-theme=0` in the settings files.

---
Created by GitHub Copilot for easy dark mode setup.
