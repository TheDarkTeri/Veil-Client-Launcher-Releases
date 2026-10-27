# Veil Client Launcher

The easiest way to play [Veil Client](https://github.com/TheDarkTeri/Veil-Client-Releases): install the launcher,
sign in with Microsoft and press **Play**. It sets up Java 8, Minecraft 1.8.9, Forge and the newest Veil Client by
itself, and keeps Veil updated.

**NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**

**[Download the latest launcher](https://github.com/TheDarkTeri/Veil-Client-Launcher-Releases/releases/latest)**

## Requirements

- Windows 10 or 11, 64-bit
- A Microsoft account that owns Minecraft: Java Edition
- About 700 MB of free space (the launcher, Java 8 and the game files)

## Installing

1. Download `VeilClient-Setup-<version>.exe` from
   [Releases](https://github.com/TheDarkTeri/Veil-Client-Launcher-Releases/releases/latest).
2. Run it. The launcher isn't code-signed yet, so Windows may show **"Windows protected your PC"**. Click
   **More info**, then **Run anyway**.
3. Choose **Only for me** (recommended) and click **Install**.
4. Open **Veil Client** from your desktop, click **Sign in with Microsoft** and press **Play**. The first launch
   downloads about 220 MB.

If Windows says **Smart App Control** blocked the installer, your PC only runs signed apps and won't let you start
it. Until the launcher is signed, you can still play with the mod jar from
[Veil-Client-Releases](https://github.com/TheDarkTeri/Veil-Client-Releases).

## What it does

- **Signs you in with Microsoft.** Your login is saved encrypted on your PC (Windows DPAPI) and is only ever sent
  to Microsoft and Mojang.
- **Installs everything for you:** Minecraft 1.8.9 from Mojang, Forge 1.8.9, Java 8 (Eclipse Temurin) and the
  newest Veil Client.
- **Keeps Veil updated.** Every time you press Play it checks for a new Veil release and swaps it in.
- **Stays separate** from your normal `.minecraft`: everything lives in `%APPDATA%\.veilclient`. Use the **Mods**
  button to add other 1.8.9 Forge mods, such as OptiFine.
- **Gets out of the way.** The launcher hides while you play and comes back when you close the game.

## Updating

- **Veil** updates by itself when you press Play.
- **The launcher:** download the newer installer from Releases and run it. It updates in place and keeps your login
  and settings.

## Uninstalling

**Settings → Apps → Installed apps → Veil Client → Uninstall.** Your game files stay in `%APPDATA%\.veilclient`;
delete that folder to remove them too.

## Only download the launcher from here

The only official launcher downloads are on this page's
[Releases](https://github.com/TheDarkTeri/Veil-Client-Launcher-Releases/releases). A launcher from anywhere else may
be modified to steal your account. Nobody from Veil will ever ask for your password.

## Bugs and help

Open an [issue](https://github.com/TheDarkTeri/Veil-Client-Launcher-Releases/issues), or email
[thedarkteriyt@gmail.com](mailto:thedarkteriyt@gmail.com). If the game crashed, use the **Logs** and
**Crash reports** buttons in the launcher's Settings and attach the newest file.

## License

Copyright (c) 2026 TheDarkTeri. All rights reserved. You may download official releases and use them for personal
play. Copying, modifying, re-uploading or redistributing the launcher needs written permission. See
[LICENSE](LICENSE).

The Veil Client launcher is made and maintained by TheDarkTeri, who is responsible for it
([thedarkteriyt@gmail.com](mailto:thedarkteriyt@gmail.com)). It is not affiliated with or endorsed by Mojang Studios,
Microsoft, Hypixel or Discord.
