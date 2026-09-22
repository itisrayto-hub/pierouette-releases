# Rayto — Alpha

A gesture-based radial launcher for macOS. **Private alpha — please don't redistribute.**

## Requirements
- Apple Silicon Mac (M1 or newer)
- macOS 26 (Tahoe) or newer

## Install (once)
1. Download **Rayto.dmg** from this page and open it.
2. Drag **Rayto** onto **Applications**, then open it from there (it is signed and notarized — no warnings).
3. Grant **Accessibility** when asked (macOS 27 calls it "Device Control and Data Access") — Rayto needs it to see your gestures and press keys for you. Nothing else is read.

## Use
- Tap **⌘** (Command) alone to open your menu — a starter set is included; **Setup** walks you through the first two gestures.
- Right-click the centre hub to arrange the menu; everything else lives in the side panel.

## Updates
The app updates itself — when a new version is published you'll get an "Update available" dialog. Your menus and settings always survive updates.

## If something goes wrong
- **Input feels stuck/weird:** quit Rayto (⌘⌥Esc → Force Quit → Rayto). Everything returns to normal immediately.
- **It crashed:** on the next launch it offers "Send Report…" — that opens an email draft to hello@rayto.app with a diagnostic file attached. You see everything before it's sent. There is no hidden telemetry.
- **Feedback:** hello@rayto.app
- **Uninstall:** drag Rayto from Applications to the Trash and delete the folder `~/.config/pierouette-alpha`. Nothing else is touched.
