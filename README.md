# KDE-3-Sounds Theme

This is a classic KDE3 sound theme converted to modern KDE sound naming conventions.

## Description

The KDE-3-Sounds theme brings back the nostalgic sounds from KDE3 but makes them compatible with modern KDE installations. The sounds have been organized according to the freedesktop.org sound naming specification.

## Download
V1.0 - https://github.com/os-guy/kde-3.3-sound-pack/releases/download/V1.0/KDE-3-Sounds.tar.gz

## Installation

### System-wide installation

To install the sound theme for all users on the system:

```bash
sudo cp -r KDE-3-Sounds /usr/share/sounds/
```

### User-specific installation

To install the sound theme for your user only:

```bash
cp -r KDE-3-Sounds ~/.local/share/sounds/
```

## Activating the Theme

1. Open System Settings
2. Navigate to "Colors And Themes"
3. Click on "System Sounds"
4. Select "KDE-3-Sounds" from the list
5. Click "Apply"

## Structure

The sound theme is organized into the following directories:

- `actions/`: Sounds for user actions like clicks, completions, and screen captures
- `notifications/`: Sounds for system notifications, alerts, and events
- `ui/`: Sounds for user interface elements like windows, menus, and desktop actions
- `stereo/`: General sounds and symlinks for backward compatibility

## Credits

Original sounds from KDE3, converted to follow modern sound naming specifications.

## License

These sounds are licensed under the same license as the original KDE3 sounds (GPL).
