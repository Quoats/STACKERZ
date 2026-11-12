<div align="center">

<img src="media/banner.png" alt="STACKERZ" width="100%">

### A chaotic co-op platformer for up to 24 players. Stack up, throw your friends, survive.

<a href="https://github.com/Quoats/STACKERZ/releases/latest/download/STACKERZ-windows.zip"><img height="42" src="https://img.shields.io/github/v/release/Quoats/STACKERZ?style=for-the-badge&label=download%20for%20windows&color=ff7a1a&logo=windows&logoColor=white" alt="Download STACKERZ for Windows"></a>

<img src="https://img.shields.io/github/downloads/Quoats/STACKERZ/total?style=for-the-badge&color=8b2cff&label=downloads" alt="Downloads">
<img src="https://img.shields.io/badge/players-1%20to%2024-ff2fa8?style=for-the-badge" alt="1 to 24 players">
<img src="https://img.shields.io/badge/made%20with-Godot%204.7-478cbf?style=for-the-badge&logo=godotengine&logoColor=white" alt="Made with Godot 4.7">
<img src="https://img.shields.io/badge/status-beta-5dff6b?style=for-the-badge" alt="Beta">

**[quoats.xyz](https://quoats.xyz/#game)** &nbsp;·&nbsp; **[Every version](https://github.com/Quoats/STACKERZ/releases)** &nbsp;·&nbsp; **[Report a bug](https://github.com/Quoats/STACKERZ/issues/new)**

</div>

---

## The game

Run, jump and stack on top of each other through world maps full of levels, enemies, bosses and puzzles. Pick your friends up and throw them across gaps, ride mounts, and grab power-ups that stack together.

- **Up to 12 players on one PC** (keyboards, Xbox and Switch-style pads, even Wii Remotes) and **up to 24 online** with host / join
- **8 worlds** of levels, each ending in a boss fight
- World maps, mounts and stacking power-ups
- PvP toggle and a full **Battle mode** with item boxes and arenas
- A built-in **World Editor** for making your own levels
- Every sprite, sound and the font are made from scratch for this game: no asset packs

## Screenshots

<table>
  <tr>
    <td width="50%"><a href="media/screens/title-tower.jpg"><img src="media/screens/title-tower-thumb.jpg" alt="Title screen"></a><br><sub><b>Title screen:</b> the tower stacks up on the logo</sub></td>
    <td width="50%"><a href="media/screens/world-1-map-card.jpg"><img src="media/screens/world-1-map-card-thumb.jpg" alt="World 1 map"></a><br><sub><b>World 1 map:</b> walk the overworld and pick a level</sub></td>
  </tr>
  <tr>
    <td><a href="media/screens/w1-1.jpg"><img src="media/screens/w1-1-thumb.jpg" alt="Meadow March"></a><br><sub><b>Meadow March</b> (World 1-1) with six players</sub></td>
    <td><a href="media/screens/lobby24.jpg"><img src="media/screens/lobby24-thumb.jpg" alt="24 player lobby"></a><br><sub><b>Online lobby</b> with all 24 players in</sub></td>
  </tr>
  <tr>
    <td><a href="media/screens/boss-w1-4-fight.jpg"><img src="media/screens/boss-w1-4-fight-thumb.jpg" alt="The Blob King"></a><br><sub><b>Boss fight:</b> The Blob King</sub></td>
    <td><a href="media/screens/boss-w6-4-fight.jpg"><img src="media/screens/boss-w6-4-fight-thumb.jpg" alt="Captain Cannonbeard"></a><br><sub><b>Boss fight:</b> Captain Cannonbeard</sub></td>
  </tr>
  <tr>
    <td><a href="media/screens/boss-roost-4-fight.jpg"><img src="media/screens/boss-roost-4-fight-thumb.jpg" alt="The Sky Dragon"></a><br><sub><b>Boss fight:</b> The Sky Dragon</sub></td>
    <td><a href="media/screens/boss-w5-4-fight.jpg"><img src="media/screens/boss-w5-4-fight-thumb.jpg" alt="El Toro"></a><br><sub><b>Boss fight:</b> El Toro</sub></td>
  </tr>
  <tr>
    <td><a href="media/screens/boss-w8-4-fight.jpg"><img src="media/screens/boss-w8-4-fight-thumb.jpg" alt="The Zorb Mothership"></a><br><sub><b>Boss fight:</b> The Zorb Mothership</sub></td>
    <td><a href="media/screens/world-editor-3d.jpg"><img src="media/screens/world-editor-3d-thumb.jpg" alt="World Editor"></a><br><sub><b>World Editor</b> with the 3D preview</sub></td>
  </tr>
</table>

## How to play

1. **[Download STACKERZ-windows.zip](https://github.com/Quoats/STACKERZ/releases/latest/download/STACKERZ-windows.zip)** (Windows, 64-bit).
2. Unzip it anywhere and double-click **`STACKERZ.exe`**. No install.
3. If Windows says *"Windows protected your PC"*, click **More info → Run anyway** (the game isn't code-signed).

`HOW TO PLAY.txt` inside the zip has everything. The short version:

| | Move | Jump | Run | Grab / throw | Spin | Crouch | Pause |
|---|---|---|---|---|---|---|---|
| **Gamepad** | stick | A | X | RB | Y | LT | Start |
| **Keyboard** | A / D | Space or W | Shift | F | E | C | Esc |
| **Keyboard 2** | arrows | Up | Numpad 1 | Numpad 2 | Numpad 3 | | |

In the lobby, **A / Space** joins and readies up, left / right picks a color, up / down picks a hat, and **Start / Enter** begins once everyone's ready. F11 toggles fullscreen.

<details>
<summary><b>Playing online</b></summary>

- Everyone needs the **exact same build**. It's shown at the bottom right of the title screen.
- **Host:** in the lobby, leave the port at 7777 and click **Host**. The line under the buttons tells you the address friends should use. If your router won't open the port, forward UDP 7777 or use a free LAN VPN (Radmin VPN, ZeroTier or Tailscale).
- **Friends:** join your own players in the lobby first, type the host's IP and port next to "IP", click **Join** and ready up.
- The first time you host, allow STACKERZ through Windows Firewall.

</details>

<details>
<summary><b>Wii Remotes and extra keyboards</b></summary>

- **Wii Remote (+ Nunchuk):** pair it once with `wiimote_pair.exe` (or "Pair Wii Remote" in the lobby) and press the red SYNC button. Keep `wiimote_helper.exe` next to the game.
- **Separate keyboards:** turn on "Separate keyboards" in Settings, then press Space on another keyboard to join as a new player. Keep `keyboard_helper.exe` next to the game.

</details>

## About me

<img align="left" width="130" src="media/quoats.png" alt="Quoats">

**Quoats**, an independent artist out of Texas. Every song, every beat (as **Woats**) and every cover is made by me, released on **XZELSIOR**. STACKERZ is my game: built in Godot, with every sprite, sound and font made for it from scratch.

Music, videos, art and game updates all live on **[quoats.xyz](https://quoats.xyz)**.

<br clear="left">

<p>
<a href="https://quoats.xyz"><img src="https://img.shields.io/badge/quoats.xyz-ff7a1a?style=for-the-badge&logo=googlechrome&logoColor=white" alt="quoats.xyz"></a>
<a href="https://soundcloud.com/quoats"><img src="https://img.shields.io/badge/SoundCloud-ff5500?style=for-the-badge&logo=soundcloud&logoColor=white" alt="SoundCloud"></a>
<a href="https://open.spotify.com/artist/7IHelcDAEHOlZOhP1y70F1"><img src="https://img.shields.io/badge/Spotify-1ed760?style=for-the-badge&logo=spotify&logoColor=black" alt="Spotify"></a>
<a href="https://music.apple.com/us/artist/quoats/6792474588"><img src="https://img.shields.io/badge/Apple%20Music-fa2d48?style=for-the-badge&logo=applemusic&logoColor=white" alt="Apple Music"></a>
<a href="https://www.youtube.com/@quoats"><img src="https://img.shields.io/badge/YouTube-ff0033?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
<a href="https://www.bandlab.com/quoats"><img src="https://img.shields.io/badge/BandLab-f12c18?style=for-the-badge&logo=bandlab&logoColor=white" alt="BandLab"></a>
<a href="https://www.instagram.com/quoatz/"><img src="https://img.shields.io/badge/Instagram-e1306c?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
<a href="https://www.tiktok.com/@quoatz"><img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok"></a>
<a href="https://x.com/Quoatzs"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
<a href="https://genius.com/artists/Quoats"><img src="https://img.shields.io/badge/Genius-ffff64?style=for-the-badge&logo=genius&logoColor=black" alt="Genius"></a>
</p>

---

<div align="center"><sub>STACKERZ © Quoats · XZELSIOR. This repository holds the game's downloadable builds.</sub></div>
