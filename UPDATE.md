# Updating Therapize

Therapize includes built-in update checking. The app will automatically check for updates on startup and periodically while running.

---

## Update Notification

When a new version is available, you'll see a notification in the app. You can also manually check for updates:

1. Open **Settings** (gear icon)
2. Scroll to the **About** section
3. Click **"Check for Updates"**

---

## Windows Update Process

Windows supports fully automatic updates:

1. When an update is available, click **"Download Update"**
2. Wait for the download to complete
3. Click **"Install & Restart"**
4. The app will close, install the update, and reopen automatically

That's it! The update process is seamless on Windows.

---

## Linux Update Process

Linux (AppImage) supports automatic updates similar to Windows:

1. When an update is available, click **"Download Update"**
2. Wait for the download to complete
3. Click **"Install & Restart"**
4. The app will close, install the update, and reopen automatically

---

## macOS Update Process

Due to macOS security restrictions and the app being unsigned, updates on macOS require a manual step:

### Step 1: Download the Update

1. When an update is available, click **"Download Update"**
2. Wait for the download to complete (the .zip file will be saved to your Downloads folder)
3. Click **"Open Downloads Folder"** to locate the file

### Step 2: Install the Update

1. **Quit Therapize completely** (Cmd+Q or right-click dock icon → Quit)
2. In Finder, navigate to your **Downloads** folder
3. **Double-click** the downloaded .zip file to extract it
4. **Drag** the new Therapize.app to your **Applications** folder
5. When prompted, click **"Replace"** to overwrite the old version
6. **Open** Therapize from Applications

### Step 3: First Launch After Update

macOS may show a security warning because the new version hasn't been opened before:

1. Right-click Therapize and select **"Open"**
2. Click **"Open"** in the security dialog

See [MAC_TRUST.md](./MAC_TRUST.md) for more details on macOS security dialogs.

---

## Manual Download

If the in-app update doesn't work, you can always download the latest version manually:

1. Visit the [Releases page](https://github.com/andrewtcrooks/therapize-releases/releases)
2. Download the appropriate file for your platform:
   - **Windows:** `.exe` installer
   - **macOS:** `.zip` file (extract and move to Applications)
   - **Linux:** `.AppImage` file
3. Install as described in the platform-specific instructions above

---

## Troubleshooting

### Update download fails

- Check your internet connection
- Try again in a few minutes
- Download manually from the releases page

### Windows: Update stuck

- Close Therapize completely (check Task Manager)
- Delete the `%LOCALAPPDATA%\therapize-updater` folder
- Restart the app and try again

### macOS: "App is damaged" after update

Run this command in Terminal:
```bash
xattr -dr com.apple.quarantine /Applications/Therapize.app
```

### Linux: AppImage won't run after update

Make sure the file is executable:
```bash
chmod +x Therapize-*.AppImage
```

---

## Version Information

You can always check your current version in **Settings → About**.

The version number follows semantic versioning (MAJOR.MINOR.PATCH):
- **MAJOR:** Breaking changes or major new features
- **MINOR:** New features, backward compatible
- **PATCH:** Bug fixes and minor improvements
