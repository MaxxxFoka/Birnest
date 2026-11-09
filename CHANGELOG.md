# Changelog

Every beta build is listed here, newest first. Downloads are on the
[Releases page](https://github.com/MaxxxFoka/Birnest/releases).

## v0.1.0-beta.7 (2026-11-09)

A balance and language update. If you have beta 6, the game offers this update on the main menu.

**Balance**
- Bellhorn, Dreadcasque and Huddlewarm move a little slower (they'd been given extra speed
  to make up for hopping; that's gone now).
- Nightpinion moves a little faster.
- Velvetclaw's basic attack hits harder: 54 → 58.
- Firstlight and Rouser bots now buy damage items instead of support items.

**Languages**
- Six more languages: Russian, Spanish (Latin America), Portuguese (Brazil), French, Polish
  and Turkish. These are machine-drafted for now; tell us when something reads wrong.
- German is now complete, including the Flock, hero voices and the shop.

**Look and fixes**
- Velvetclaw refined again: new back and wing colours and a feathered head.
- A brighter midday; the warm late light stays for dawn and dusk.
- The pick screen and shop fit longer translated text.
- Fixed an error in pings.

## v0.1.0-beta.6 (2026-11-09)

Windows and Mac. **Install this one by hand once:** from now on the game updates itself.

**Updates in the game**
- When a new beta is out, the main menu offers it: **Update now** downloads it, checks it
  and installs it, then restarts the game. **What's new** shows the notes; **Later** hides it.
- If the server no longer accepts your version, the menu tells you to update.
- On a Mac, keep `Birnest.app` in Applications (not Downloads) so it can update itself.

**Play with friends**
- **The Flock:** a friends page with recent players, plus mute, block and report.
- **Hero colours:** earn colour variants by playing, pick one on the pick screen, and wear
  it in matches.
- **Hero voices:** every bird has a call for each ability, with a Hero voices volume slider.
- **Language:** English and German, with a language picker in Settings.

**Combat and camera**
- Melee hits land with more weight: a short hit-stop and a camera jolt on your own hits and
  kills.
- The camera moves in or rises past cover instead of hiding your bird; buildings fade near
  the lens.
- Dive abilities show as stooping dives on every screen.
- Cleaner world labels: merged markers, fading nameplates, easier-to-read health bars.

**Look**
- Smoother flight: tip-anchored contrails, a swept glide and a tucked dive.
- Night keeps every unit's colour and team colour readable; Shellfall's dark areas are lighter.
- The Stillstorm's coat reads dark slate on every renderer; its den is cleared of clutter.
- Velvetclaw refined again; leaf litter no longer shows hard-edged shapes.

**Fixes**
- The intro flyover only plays at the start of a real match.
- The Watch list no longer shows an empty replay.

## v0.1.0-beta.5 (2026-11-09)

Windows and Mac. Older betas can't join online matches with the updated server, so update
before you play.

**Combat feel**
- Hits read clearly: a tinted flash, stacked damage numbers, flying feathers and a clear
  kill moment. Melee hits now shove the target back.
- A death card shows what killed you, with a short kill cam.
- The camera keeps your bird larger in fights, and your own effects fade near the lens.
- Each ability has one clear look for its cast.

**Flight**
- Diving pushes you faster, with pitched wind, speed blur and wingtip contrails.
- Leaves and bark in front of your bird turn see-through so you never lose sight of it.

**Map and objectives**
- Team-coloured beams and distance markers point to objectives.
- A flyover introduces the map at the start of a match.
- The Stillstorm shows its pounce landing ring and leap path.
- Brighter day and night lighting, a new painted ground with grass and rushes.

**Heroes and menus**
- See your real 3D bird on a lit stage in the pick screen, menu and lobby.
- Thornback and Velvetclaw rebuilt with new models.
- New "First flight" tutorial and a training range with practice tools.

**Bots and balance**
- Bots push the Flyway you're not on, and hold their pushes while they outnumber you.
- Balance recheck after the gentler Fledglings.

**Fixes**
- Joining an online match always goes through the loading screen, and a failed join stays
  there with a plain reason instead of a server address.
- The Compatibility (OpenGL) renderer lights tree canopies correctly again.

## v0.1.0-beta.4 (2026-11-08)

**Mac**
- A native macOS build, `Birnest-v0.1.0-beta.4-macos.zip`: the full renderer on Metal,
  no CrossOver needed. It isn't signed by Apple yet, so approve it once; see
  [Install on a Mac](README.md#install-on-a-mac).

**New**
- **Homeward Whistle:** every hero starts with one in a Trinket slot (extra ones cost
  75 Seeds). Use it to channel for 3.5 s, then fly home to your Roost, or to a friendly
  Perch if you aim right at it. Taking a hit or moving cancels it at no cost.
- **Shop from anywhere:** open the Magpie Market (**B**) anywhere on the map. Away from the
  Market your purchases wait in your 6-slot Stash; right-click a stashed item to sell it.
- **Carrier Swift:** each Clutch has a courier. Press **C** to send it with your Stash; it
  flies the items out to you. Enemies can kill it for a bounty, but your items are never lost.

**Combat**
- Your ultimate (**R**) now shows "Molt 6" until it unlocks, and a refused cast tells you
  why (locked, cooldown or not enough mana).
- Fledglings hit heroes for 30% less and switch to enemy Fledglings when they're near.
- Ranged attacks fly a visible bolt; Perches wind up a glowing orb before they shoot.
- Last hits show "+N" Seeds; denies show "!".

**Fixes**
- Removed log errors from the loading-screen warm-up.

**World**
- The Stillstorm has a new, fiercer model.

## v0.1.0-beta.3 (2026-11-08)

Fixes from the first online matches between friends, plus respawning in your Roost. Beta 2 can no longer join online
matches once this build is out, so update before you play.

**New**
- **Respawn in your Roost:** heroes now hatch and respawn in their own Roost, which defends
  itself against intruders.

**Fixes**
- No more duplicate heroes: each bird can be picked once per match.
- Nobody starts before everyone has loaded. The loading screen shows "Waiting for players"
  until the last player is in.
- Less stutter the first time abilities and effects appear: the game warms them up behind
  the loading screen.
- Fixed black or washed-out graphics on the Compatibility (OpenGL) renderer, used on older
  GPUs and by Mac players running the game through CrossOver.
- Settings: Accept and Revert sit at the bottom and stay greyed out until you change something.

**Balance and world**
- Second and third hero tuning passes; Stillstorm retuned and given a fiercer look.
- Longer opening Day and Gloaming; new day and night colour grading.

## v0.1.0-beta.2 (2026-11-08)

**New**
- The game is now called **Birnest**, with a new icon, boot splash, menu art and loading
  screen. The exe is `Birnest.exe`; settings, key bindings and replays move over from
  beta 1 on first start.
- **Find match:** queue for a match from the main menu, alone or in a party with friends.
  A ready check pops when a match is found, and bots fill empty seats. 5v5 online matches on
  Shellfall, with a draft.
- **Steam invites (optional):** with Steam running, Host a lobby, then click **Invite Steam
  friends**; your friend accepts in Steam and lands in your lobby. It uses Steam's test app
  for now, so you'll show as playing Spacewar, and your friend must already have Birnest
  open when accepting. For the Steam overlay, add `Birnest.exe` to Steam via
  **Games > Add a Non-Steam Game**.
- Music and voices: day and night music, a menu theme, stings and hero reaction calls.

**Look and feel**
- Lighting pass, a rebuilt Canopy environment (trees, rocks, cliffs), rebuilt Perches and a
  redesigned Thornback.
- Clearer ability effects: cast, travel and impact for every ability, and readable
  ultimate-heavy fights.
- HUD: death recap, XP bar and mana numbers.

**Bots and balance**
- Bots close out games, defend, clear the Wilds and now fight the Stillstorm; easy, normal
  and hard practice bots.
- First hero tuning pass; Stillstorm retuned.

**Fixes**
- The Lobby server field opens on the beta server even if beta 1 saved a local address.

## v0.1.0-beta.1 (2026-11-08)

The first closed beta build.

**Play**
- Practice against bots on **Canopy** (3v3, two Flyways) or **Shellfall** (5v5, three Flyways).
- Online lobbies with invite codes on the beta server; bots fill empty slots.
- A first-match guide that teaches moving, flying, the shop and fighting.

**Birds**
- 10 birds: Bellhorn, Dreadcasque, Evensong, Firstlight, Huddlewarm, Nightpinion,
  Plungebright, Rouser, Thornback and Velvetclaw, each with four abilities.

**Systems**
- Flight with a Lift meter, aimed attacks and skillshots.
- Seeds, last hits and Trinkets from the Magpie Market; Plume talent cards.
- Fog of war, Perches, Fledgling waves, the Wilds and a sleeping boss to hunt.
- HUD with death recap, XP bar, minimap, scoreboard and pings.
- Replays of practice matches, and live spectating of online matches.
- Settings: rebindable keys, graphics presets, UI scale, colour-blind modes, audio mixer.

**Known issues**
- Much of the art is placeholder and is being rebuilt.
- The game window and `.exe` still show the old name and the default engine icon (fixed in beta 2).
- Online play has had little testing between players on different networks. Please report
  lag or disconnects.
