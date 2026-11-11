# Duel at Dusk

An 8-player lobby autobattler. Each round you buy weapons and items, then your fighter duels one
of your seven bot rivals on its own. Every fight starts in daylight; when the sun sets, both
fighters take more and more damage until one falls. Losing costs Life, and the last player standing
wins. Build toward one of eleven directions (Poison, Burn, Crit, Thorns and more), pick perks along
the way, and play ranked games through six ranks from Ashigaru to Shogun, or casual games against
rivals as strong as you choose.

This repository only hosts the game's downloads.

## Download and play

Open [**Releases**](../../releases/latest). Each release has a Windows zip and a Mac zip.

### Windows (64-bit)

1. Download `DuelAtDusk-X.Y.Z-windows.zip`.
2. Unzip it and run `DuelAtDusk.exe`. It's a single file; there's nothing to
   install.

The exe isn't code-signed, so Windows SmartScreen may warn the first time:
click **More info → Run anyway**.

### Mac (Apple Silicon and Intel)

1. Download `DuelAtDusk-X.Y.Z-macos.zip`.
2. Unzip it on the Mac (double-click it) and drag **Duel at Dusk** to
   Applications.
3. Open it. The game isn't signed by Apple, so the first time macOS says it
   can't verify the app: click **Done**.
4. Open **System Settings → Privacy & Security**, scroll down, click
   **Open Anyway** next to "Duel at Dusk", and confirm with your password.
   From then on it opens normally.

**Downloading the Mac version on a PC?** Don't unzip it on Windows. Windows
drops a setting the app needs, and the Mac then refuses to open it. Copy the zip
over unopened (USB stick, cloud drive, email to yourself) and unzip it on the Mac.

### Saves

Your rank, match history and settings carry over when you update to a new
version. They're stored in:

- Windows: `%APPDATA%\Godot\app_userdata\Duel at Dusk\`
- Mac: `~/Library/Application Support/Godot/app_userdata/Duel at Dusk/`

New to the game? Open **How to play** from the main menu.

## Controls

| Action | Key |
| --- | --- |
| Buy, equip, merge, sell | Click and drag; right-click sells |
| Reroll / level up the shop / fight | R / L / F |
| Pause / speed 1× or 2× / skip | Space / 1, 2 / S |
| Combat log | L (during and after a fight) |
| Mute | M |
| Fullscreen | F11 or Alt+Enter |
