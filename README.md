# Pierouette — Alpha

A gesture-based radial launcher for macOS. **Private alpha — please don't redistribute.**

## Requirements
- Apple Silicon Mac (M1 or newer)
- macOS 26 (Tahoe) or newer

## Install (once)
1. Download **Pierouette.dmg** from this page and open it.
2. Drag **Pierouette** into **Applications**.
3. Open Pierouette. macOS will block it ("Apple could not verify…") — that's expected for an alpha:
   open **System Settings → Privacy & Security**, scroll down, click **"Open Anyway"**, confirm with your password.
4. Grant the permissions it asks for (**Accessibility**, and **Input Monitoring** if asked) — it needs these to show the menu over other apps.

## Use
- Hold **⌃⌥Space** (Control + Option + Space) to open the menu — a starter set is included.
- Click the center hub with the **right** mouse button to edit the menu; the Settings window does the rest.

## Updates
The app updates itself — when Ray publishes a new version you'll get an "Update available" dialog. Your menus and settings always survive updates.

## If something goes wrong
- **Input feels stuck/weird:** quit Pierouette (⌘⌥Esc → Force Quit → Pierouette). Everything returns to normal immediately.
- **It crashed:** on the next launch it offers "Send Report…" — that opens an email draft to Ray with a diagnostic file attached. You see everything before it's sent. There is no hidden telemetry.
- **Uninstall:** drag Pierouette from Applications to the Trash and delete the folder `~/.config/pierouette`. Nothing else is touched.
