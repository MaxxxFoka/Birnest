<h1 align="center">🪶 Birnest</h1>

<p align="center">
  <b>A third-person team battle game where every hero is a bird.</b><br>
  Take off, fight down the Flyways, and break the enemy's Great Egg.
</p>

<p align="center">
  <a href="https://github.com/MaxxxFoka/Birnest/releases/download/v0.1.0-beta.10/Birnest-v0.1.0-beta.10-windows.zip"><b>⬇ Windows</b></a> ·
  <a href="https://github.com/MaxxxFoka/Birnest/releases/download/v0.1.0-beta.8/Birnest-v0.1.0-beta.8-macos.zip"><b>⬇ Mac</b></a> ·
  <a href="https://github.com/MaxxxFoka/Birnest/releases">All releases</a> ·
  <a href="#install">Install</a> ·
  <a href="#how-to-play">How to play</a> ·
  <a href="#report-a-bug">Report a bug</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="https://birnest.com">birnest.com</a> ·
  <a href="https://birnest.com/discord"><b>Discord</b></a>
</p>

<p align="center"><img src="docs/images/match.jpg" alt="A 3v3 match on the Canopy map, seen from behind a hero at the Nest" width="900"></p>

> **Open beta, free to play.** Anyone can download Birnest and play online. The game is early
> and changes every week: expect bugs, placeholder art and balance swings. Your reports shape
> what we fix next.
>
> **Latest: v0.1.0-beta.10** (Mac: still v0.1.0-beta.8) · [Windows](https://github.com/MaxxxFoka/Birnest/releases/download/v0.1.0-beta.10/Birnest-v0.1.0-beta.10-windows.zip) · [Mac](https://github.com/MaxxxFoka/Birnest/releases/download/v0.1.0-beta.8/Birnest-v0.1.0-beta.8-macos.zip) · [What's new](CHANGELOG.md)

## What is Birnest?

More about the game, its birds and its world at **[birnest.com](https://birnest.com)**.

Two Clutches, **Sunfeather** and **Duskwing**, defend their Nests on the world of Welkin.
Each team picks birds, pushes waves of woven Fledglings down the Flyways, brings down the
enemy Perches and breaks the Great Egg at the heart of their Nest.

- **Third-person, aimed combat.** You look and aim with the mouse, like a shooter, not by
  clicking on the ground.
- **Flight.** Flyers and Gliders take to the air; the heavy Hoppers (Bellhorn, Dreadcasque
  and Huddlewarm) stay on the ground and hop. Lift drains in the air and refills on the
  ground, so choosing when to fly is half the game. On the Canopy you can also perch in the
  treetops, hide in the leaves and ride the wind.
- **10 birds** in this beta, five for each Clutch, from the Larder-Keeper Thornback to the
  River-Spear Plungebright. Each has a trait and four abilities taken from how that bird
  really lives: a shrike's larder, a kingfisher's dive, a nightingale's songs.
- **Grow through the match.** Earn XP to Molt up to Molt 25, rank up an ability each time
  and pick Plumes on the Plume card to shape your build.
- **Seeds and Trinkets.** Last hits pay Seeds; spend them at the Magpie Market on 34
  Trinkets, the same shop in every mode. You can buy from anywhere: the Carrier Swift brings
  what you bought away from the Nest. The Homeward Whistle that flies you home has its own
  slot.
- **Play your way.** Learn in First flight, a guided match, or practice against bots at three
  difficulties. Online, queue for 3v3 on the Canopy (unranked or ranked) or host a lobby and
  play with friends using an invite code, on the Canopy (3v3) or the Shellfall (5v5), where
  the Stillstorm sleeps.

## System requirements

| | Minimum | Recommended |
|---|---|---|
| **OS** | Windows 10 64-bit | Windows 11 64-bit |
| **CPU** | 4 cores, 2.5 GHz | 6 cores, 3.5 GHz |
| **Memory** | 8 GB RAM | 16 GB RAM |
| **Graphics** | Vulkan 1.2 GPU, 2 GB (GTX 960 / RX 470 class) | 4 GB+ (GTX 1660 / RX 5600 class) |
| **Storage** | 500 MB free | 1 GB free (replays add up) |
| **Network** | Broadband for online play | |

These are early estimates; tell us if the game runs badly on a PC that meets them.

**Mac:** there is a native build for macOS 11 Big Sur or later. It runs the full renderer
on Metal and is made for Apple Silicon (M1 or newer); the same app also runs on Intel Macs,
but we haven't tested those yet. Linux may come later.

## Install

1. Download [the Windows zip](https://github.com/MaxxxFoka/Birnest/releases/download/v0.1.0-beta.10/Birnest-v0.1.0-beta.10-windows.zip) (or pick a version from **Assets** on the
   [Releases page](https://github.com/MaxxxFoka/Birnest/releases)).
2. Right-click the zip, choose **Extract All…**, and pick a folder you own, for example
   `C:\Games\Birnest`. Don't run the game from inside the zip.
3. Open the folder and double-click `Birnest.exe`.
4. Windows may show **"Windows protected your PC"** because the beta isn't code-signed yet.
   Click **More info**, then **Run anyway**.

Keep every file from the zip together: the game needs the `.pck`, the `.dll` and the
`content` folder next to the `.exe`.

### Install on a Mac

The Mac beta isn't signed with an Apple Developer ID yet, so macOS asks you to approve it
once.

1. Download [the Mac zip](https://github.com/MaxxxFoka/Birnest/releases/download/v0.1.0-beta.8/Birnest-v0.1.0-beta.8-macos.zip) (or pick a version from **Assets** on the
   [Releases page](https://github.com/MaxxxFoka/Birnest/releases)). Safari unzips it for
   you; otherwise double-click the zip. You get `Birnest.app`.
2. Drag `Birnest.app` into your **Applications** folder (or any folder you own).
3. Double-click `Birnest.app`. macOS says it **"cannot verify"** the app or that Apple
   could not check it for malware. Click **Done** (or **OK**). Don't move it to the Bin.
4. Open **System Settings → Privacy & Security**, scroll down to **Security**, and next to
   *"Birnest" was blocked* click **Open Anyway**. Enter your password, then click
   **Open Anyway** once more. From then on the game opens normally.

If step 4 has no **Open Anyway** button, or macOS says the app **"is damaged and can't be
opened"**, remove the download quarantine flag in **Terminal** and open it again:

```sh
xattr -dr com.apple.quarantine /Applications/Birnest.app
```

(Change the path if you put the app somewhere else. You can type `xattr -dr
com.apple.quarantine ` and drag the app onto the Terminal window.)

Settings and replays live in `~/Library/Application Support/Godot/app_userdata/Birnest/`.
To update, replace `Birnest.app` with the new one; you may need to approve it again.

If you played the Windows build through CrossOver or Parallels before, use the Mac build
instead: it looks better and runs faster.

**Updating:** from beta 6 on, the game checks for a new version when you open it. The main
menu offers the update, downloads it, checks it and installs it for you. Beta 5 and older
can't do that yet, so install beta 6 by hand once: download the new zip and extract it over
the old folder (on a Mac, replace `Birnest.app`). Your settings, key bindings and replays
are kept, because they live in your user profile, not in the game folder.

**Uninstalling:** delete the game folder. Settings and replays live under
`%APPDATA%\Godot\app_userdata\Birnest\`; delete that folder to remove them too.

<details>
<summary><b>Check the download (optional)</b></summary>

Each release also has a `.sha256` file. In PowerShell:

```powershell
Get-FileHash .\Birnest-<version>-windows.zip -Algorithm SHA256
```

On a Mac, in Terminal:

```sh
shasum -a 256 ~/Downloads/Birnest-<version>-macos.zip
```

The hash should match the one in the `.sha256` file.
</details>

## How to play

This guide follows the current Windows build. The Mac is still on beta 8, which plays
against bots only; online play on the Mac returns with the December Mac build.

### Your first match

1. Launch the game. On your first run the **Practice** menu opens with **First flight**, a
   guided 10-minute match on the Canopy: moving, fighting, shopping and taking a Perch.
   Press **F1** to end the tutorial.
2. After that, **Practice → Practice match** lets you pick any bird, a map and the bots'
   difficulty (Easy, Normal or Hard). The **Canopy** (3v3, two Flyways) is the best place to
   start; the **Shellfall** is the full 5v5 map with three Flyways and the Stillstorm.
   **Practice → Training range** has practice tools on **F9**: training dummies, cooldown
   refresh and more.
3. Push with your Fledglings, bring down the enemy Perches and Hatcheries, then break their
   Great Egg.

### Play online

The game connects to the beta server by itself (the **Lobby server** field under
**Lobby → Advanced** already says `https://2-31-168-73.sslip.io`).

**Find match:** press **Play** on the main menu to queue for 3v3 on the Canopy, **Unranked**
or **Ranked**. To queue together, one of you clicks **Make a party** and shares the party
code; the other enters it under **Join party**. When a match is found, accept the ready
check and draft your birds. Unranked fills empty seats with bots after a short wait; ranked
waits for players. Ranked has seasons and rank tiers, and is solo or duo.

**Play with a friend:** open **Lobby** on the main menu; both of you type your names.

1. One of you clicks **Host a lobby** and sends the invite code (any chat app works).
2. The other pastes the code into **Invite code** and clicks **Join**.
3. Pick your Clutches. The host picks the map (the Canopy for 3v3, the Shellfall for 5v5)
   and can switch to a draft with bans, then starts the match. Empty slots are filled with
   bots, so 1v1, 2v2 or a full match all work.

If your game closes mid-match, the main menu offers to rejoin it.

**Steam invites (optional):** with Steam running, host a lobby and click **Invite Steam
friends**. Your friend must already have Birnest open when they accept. For now you'll show
as playing "Spacewar" in Steam; that's expected during the beta.

If you joined a lobby but the match never loads, allow the game through Windows Firewall
(it uses UDP ports 7777 to 7876) and try again.

### Controls

All keys can be changed in **Settings → Controls**.

| Action | Key |
|---|---|
| Move | **W A S D** |
| Look and aim | **Mouse** |
| Attack | Hold **Left mouse** |
| Cancel an aimed cast | **Right mouse** |
| Take off / land (Hoppers hop) | **Space** |
| Crown hop (while perched in a treetop) | **X** |
| Abilities 1, 2, 3, ultimate | **Q**, **E**, **F**, **R** |
| Rank up an ability | **Ctrl** + **Q**, **E**, **F** or **R** |
| Trinkets | **1** to **6** |
| Homeward Whistle (fly home) | **T** |
| Magpie Market (shop, works anywhere) | **B** |
| Send the Carrier Swift with your Stash | **C** |
| Plume card | **P** |
| Scoreboard | Hold **Tab** |
| Ping (tap or hold) | **G** or **Mouse 4** |
| Team chat | **Enter** |
| Free the cursor, show ranges | **Alt** |
| Swap camera shoulder | **V** |
| Menu | **Esc** |
| End the tutorial | **F1** |

### Watch and replay

Every match you play is saved as a replay when it ends or when you leave. Open **Watch** on
the main menu to play them back, or enter a lobby's invite code to spectate its live match.

## Report a bug

Found something broken? Please tell us; every report gets read.

1. Go to [**Issues → New issue**](https://github.com/MaxxxFoka/Birnest/issues/new/choose).
2. Pick **Bug report** (or **Feedback** for ideas and balance opinions).
3. Fill in what happened, what you expected, and how to make it happen again. A screenshot
   or a short video helps a lot.

Rather chat? Post it in **#bug-reports** on our [Discord](https://birnest.com/discord), where you
can also find teammates and hear about playtests first.

Useful extras:

- **Replay:** attach the replay of the match where it happened. Replays are in
  `%APPDATA%\Godot\app_userdata\Birnest\replays\` (paste that path into the Explorer
  address bar). Zip the `.bndreplay` file and drag it into the issue.
- **Crash or black screen:** run the game from a Command Prompt in the game folder and copy
  the text it prints into the issue.
- Tell us your **beta version** (the release name, e.g. `v0.1.0-beta.1`), your **GPU** and
  whether you were in **Practice** or **online**.

Please don't post personal information in issues.

## Troubleshooting

| Problem | Try this |
|---|---|
| "Windows protected your PC" | Click **More info → Run anyway**. The beta isn't code-signed yet. |
| The game closes at once or says a `.dll` is missing | Make sure you extracted the whole zip. Install the [Microsoft Visual C++ Redistributable (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe). |
| Error about Vulkan or a black window | Update your graphics driver from NVIDIA, AMD or Intel. |
| Low frame rate | **Settings → Graphics**: set quality to **Low** and lower the render scale. |
| Can't connect to a lobby | Check that the Lobby server field (**Lobby → Advanced**) says `https://2-31-168-73.sslip.io`, and allow the game through your firewall. |
| Mouse is stuck in the window | Hold **Alt**, or press **Esc** for the menu. |

## Beta terms

Birnest is in open beta and is provided as is, for testing. See
[BETA-TERMS.md](BETA-TERMS.md) for what that means for you. This repository holds the
player downloads, changelog and bug reports; the game's source code is not public.

<p align="center"><sub>Birnest is an original game. All names, heroes, art and lore are our own.</sub></p>
