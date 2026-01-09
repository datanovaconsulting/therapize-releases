# Running Unsigned Apps on macOS

Therapize is distributed as an unsigned application. macOS will display security warnings when you first try to open it. This is expected behavior and does not indicate any problem with the app.

## Why is Therapize unsigned?

Apple charges $99/year for their Developer Program, which is required to sign and notarize macOS apps. To keep Therapize affordable and accessible, we've chosen not to participate in this program.

**Important:** Therapize is safe to use. All processing happens locally on your machine, and no data ever leaves your computer.

---

## Method 1: Right-Click to Open (Recommended)

This is the simplest method and works for most users.

1. **Locate Therapize** in your Applications folder (or wherever you placed it)
2. **Right-click** (or Control-click) on the Therapize icon
3. Click **"Open"** from the context menu
4. In the dialog that appears, click **"Open"** again

You only need to do this once. After the first time, Therapize will open normally.

---

## Method 2: System Settings

If Method 1 doesn't work, use System Settings:

1. Try to open Therapize normally (double-click)
2. When the warning appears, click **"Cancel"** (not "Move to Trash")
3. Open **System Settings** (Apple menu → System Settings)
4. Go to **Privacy & Security**
5. Scroll down to the **Security** section
6. You'll see a message like "Therapize was blocked from use because it is not from an identified developer"
7. Click **"Open Anyway"**
8. Enter your password if prompted
9. Click **"Open"** in the final confirmation dialog

---

## Method 3: Terminal (Advanced)

If the above methods don't work, you can remove the quarantine attribute using Terminal:

1. Open **Terminal** (Applications → Utilities → Terminal)
2. Run the following command:

```bash
xattr -dr com.apple.quarantine /Applications/Therapize.app
```

If you installed Therapize in a different location, adjust the path accordingly:

```bash
xattr -dr com.apple.quarantine /path/to/Therapize.app
```

3. Try opening Therapize again

---

## Troubleshooting

### "Therapize is damaged and can't be opened"

This message usually appears due to quarantine attributes. Try Method 3 (Terminal command) to resolve it.

### "Therapize can't be opened because Apple cannot check it for malicious software"

This is the expected message for unsigned apps. Use Method 1 or Method 2 to open the app anyway.

### Still having issues?

1. Make sure you downloaded Therapize from the official releases page
2. Try deleting the app and re-downloading it
3. Check that the download completed fully (no partial downloads)
4. Open an issue on GitHub if problems persist

---

## Security Notes

- Therapize processes all data locally on your device
- No audio, transcripts, or clinical notes are ever sent to external servers
- The app does not require an internet connection to function
- All ML models run locally using your CPU/GPU

The unsigned nature of the app is a distribution choice, not a security concern.
