# Changelog

Every beta build is listed here, newest first. Downloads are on the
[Releases page](https://github.com/MaxxxFoka/Birnest/releases).

## v0.1.0-beta.3 (2026-11-08)

Fixes from the first online matches between friends, plus respawning in your Roost. Beta 2 can no longer join online
matches once this build is out, so update before you play.

**New**
- **Respawn in your Roost:** heroes now hatch and respawn in their own Roost, which defends
  itself against intruders.
- Coming in the next beta: the Homeward Whistle (fly back to a Perch or your Roost), a
  Stash for buying from anywhere, and the Carrier Swift courier. The groundwork is in this
  build; the buttons for them arrive next.

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
