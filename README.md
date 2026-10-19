# StarRunner

All your Star Citizen tools in one window. StarRunner puts player lookups, mining scans, hauling routes, your inventory, blueprints, language packs, notes and a ship radio side by side in tabs, so you can keep one app open next to the game instead of a pile of websites and spreadsheets.

### Features

- Hauling: type in your cargo contracts and get the best order to pick up and drop off, with gateway jumps and big contracts split into trips that fit your ship. Save routes and contracts, check off stops with a key while you play (F8), and keep a small on-top window with your next stop.
- Cargo map (optional): see where every box sits in your ship's hold at each stop, and move or stack them yourself.
- Mining: reads the scan number off your screen and shows which rock it is in a small see-through overlay.
- Refinery timers (on the right of the Mining tab): press a key at the refinery terminal and it reads the station and the time left off the screen and starts a timer, with a sound when the order is done. You can also add timers by hand.
- Inventory: keeps track of what you have stored where, across the universe, and knows where you last opened your inventory in game.
- Blueprints: adds the blueprints you receive in game by itself and shows what each one takes to craft.
- Citizens: look up any player by their handle and see their public RSI profile, organizations and rank.
- Language Packs: edit the game's language file and put your edits back after every patch.
- Notes: a light notepad that saves by itself.
- HCN Radio: plays HCN Radio's fan-made Star Citizen stations, with ship radio sound effects and a small on-top player.
- Home: RSI server status, your play time, and looks from the ship makers' cockpit screens (Aegis, Drake, Origin, RSI and more).
- Turn off the tabs you don't use, and it keeps itself up to date.

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v2.9** (Oct 19, 2026)

- [StarRunner_v2.9_no-install.zip](https://github.com/codenomics/StarRunner/releases/download/v2.9/StarRunner_v2.9_no-install.zip) - 629 KB
- [StarRunner_v2.9_Setup.exe](https://github.com/codenomics/StarRunner/releases/download/v2.9/StarRunner_v2.9_Setup.exe) - 686 KB
- [StarRunner_v2.9_source.zip](https://github.com/codenomics/StarRunner/releases/download/v2.9/StarRunner_v2.9_source.zip) - 618 KB

What's new in v2.9:

- The refinery timers now sit on the right side of the Mining tab (there is no separate Refinery tab any more).
- Mining tab: the reading box and rock name are in an Overlay section on the left. Start reading and the start-at-launch check box are right under it.
- New Overlay settings window for the overlay's colors, size, how long it stays and where it sits. The overlay can still be moved while it is open.
- Inventory: Green Imperial Housing Exchange now shows as GrimHex.

Older versions are on the [Releases page](https://github.com/codenomics/StarRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find StarRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## Source code

Want to see how it works, or build it yourself? Download the file ending in `_source.zip` above, extract it and double-click `Build.bat`. It only uses the C# compiler that already comes with Windows, so there is nothing to install.

## More details

```
GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > StarRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the StarRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click StarRunner.exe. Nothing is installed; to remove it, delete
  the folder.

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
- Click a tab at the top to switch tools. StarRunner remembers the tab you
  had open. Drag a tab sideways to put the tabs in your own order. The window
  can be resized and maximized.
- Home tab: a quick look at each tool and the look in use, the RSI server
  status (checked every 10 minutes; "Status page" opens the full page) and
  your play time: the total since your earliest game log entry, this week and today.
  It keeps counting after patches, even once the game deletes old logs.
  Tabs you don't use can be hidden with the Hide button next to each tool
  (nothing in them is deleted); Show brings one back.
- Themes (button at the top, or Themes... on the Home tab): previews of every
  look - Runner, plus looks from the ship makers' cockpit screens (Aegis,
  Aopoa, Argo, Banu Souli, Crusader, Drake, Esperia, Gatac, Grey's Market,
  Kruger, MISC, Origin, RSI). Pick one and click Restart now to use it.
- Citizens tab: type a player's handle (the name in the address of their
  RSI profile) and press Enter or click Look up.
  Click any name in the Recent list to look that player up again. Their
  organizations are listed with the player's rank in each; click one to see
  its Overview, History, Manifesto, Charter and a Members list. "Open on
  RSI website" opens their page in your browser.
- Mining tab:
  1. Click Pick area, switch to the game and scan a rock so the number shows.
     After 5 seconds the screen freezes - drag a box around the number.
     (Any game window mode works: Borderless, Windowed or Fullscreen.)
  2. Click Start reading. The overlay shows e.g. "3x Titanium" while the
     number is on screen. It keeps working while you use the other tabs.
  The Signatures button opens the table of scan numbers (you can fix or add
  values after game updates). Overlay settings opens a window for the
  overlay's colors, size, how long it stays and where it sits. Press F1 for
  more help.
- Language Packs tab:
  1. Click Choose language file (or drag a global.ini onto the window). "Get
     newest" downloads a community language pack from GitHub.
  2. Search the list, click an entry and type in the Current value box.
  3. Save my changes keeps just your edits in a small file (Documents\LangRunner).
     When a new version of the file comes out, open it and click Load my
     changes to put your edits back on it.
  4. Save to game puts the file into Star Citizen and backs up the old one.
     Windows may ask for permission to write there - click Yes. Backups...
     lists the backups so you can put one back. Press F1 for the guide.
- Notes tab: click New note and type. The first line is the title. Notes save
  by themselves and are plain text files in Documents\StarRunner Notes.
- Inventory tab:
  1. Open your inventory in game at a station or city, then click Add item.
     StarRunner picks that place for you (it reads the game's log file). Pick
     the type, type the name and the amount (units, SCU or cSCU) and click
     Add, or Add + next to keep going. With SCU you can also type how many
     cargo boxes and their size (for example 8 x 8 SCU) and it works out the total.
  2. Your places are listed on the left by system and planet. Click one to
     see what's there. All items adds up the same things across every place.
  3. The search box looks through every place at once. Double-click a result
     to go there.
  4. Each item has small buttons: -1 and +1 to change the amount quickly,
     then edit, move (all of it or part of a stack) and remove.
     Right-click a place to rename it, make it your home, or remove it.
  5. Tools: Set home location, Move everything home (after a patch moves your
     stuff), Back up / Load a backup, Item colors and Clear all.


- Hauling tab:
  1. At the top left, pick your ship (or type its cargo SCU), where you
     start, and Shortest distance or Fewest stops.
  2. Click Add contract for each hauling job: where it's picked up, where it
     goes, how many SCU (and the reward if you like). If a contract has
     more than one pick-up or drop-off, click "+ Add a pick-up or drop-off"
     and add a line for each, with its own SCU. Each contract has
     buttons to edit or remove it. Clear contracts empties the whole list
     (it asks first).
  3. The best order shows in the middle: each stop with what to load and
     unload, the distance flown and any gateway jumps. Check stops off as you
     fly them. Big contracts are split into trips that fit your ship.
     Checked stops stay as they are: add or remove a contract on the way
     and only the rest of the route is worked out again, from your last
     checked stop. A contract in a checked stop can't be edited.
     Under the contracts you see the total pay (from the rewards you typed)
     and how much you have earned so far.
  4. Ship list: type part of a name to find it. My ships... adds your own.
  5. Saved routes... keeps a whole route (ship, start and contracts) to load
     again later. The disk button on a contract saves just that one, and
     Saved contracts... adds it back to the list.
     Check-off key: press F8 while you play to check off the stop you're at
     (click "Check-off key: F8" to pick another key or turn it off).
  6. Cargo map (optional): check "Show the cargo map", pick your ship and click
     Edit grid to draw its cargo hold once (squares across, long and high, and
     the ramp edge). In each contract you can type the boxes the freight
     elevator lists, or click the boxes button on a contract to set them
     later. The map shows in its own column on the right. Click a stop to see
     where every box sits: Arrive shows
     what to take off, Leave shows what was put on. Drag a box to move it
     (drop it on another box to stack it, or on an empty spot to put it on
     the floor), right-click to turn it. You usually only see the box sizes at the
     freight elevator: click the boxes button on that stop in the route and
     type them there.
  7. Mini window (top right): a small window with just the stop you're
     flying to. The check button next to the place checks it off (in the
     route too) and shows the next stop; the curved arrow at the top
     undoes the last one. The size button switches between wide, tall
     (also shows the next stops) and a one-line strip; drag the bottom-right
     corner to make it bigger or smaller. It stays on top of other windows; for
     it to show over Star Citizen, run the game in Borderless mode.
- Refinery timers (right side of the Mining tab):
  1. Start a refinery work order in the game. On the terminal's PROCESSING
     screen (the one that says TIME REMAINING), press the refinery key
     (F9 to start with; the Key button changes it). StarRunner reads the
     station, the work order, the materials and the time left, and starts a
     timer. The key works while the game is in front, so run the game in
     Borderless or Windowed mode.
  2. No key handy? Click Read the screen, switch to the game, and it reads
     the screen five seconds later.
  3. Press the key again on the same order to correct the time. Timers
     for different stations or work orders run side by side.
  4. Add by hand starts a timer from text like: Seraphim Station, 1h 30m.
     The x on a timer removes it; Clear finished removes all done ones.
  5. A sound plays when a timer finishes. Timers are kept when you close
     StarRunner, but you only get the sound while it is open.
- Blueprints tab:
  1. Blueprints you receive in game are added by themselves (StarRunner
     reads them from the game's log files, including older ones). Opening
     the crafter doesn't show up in the logs, so add any it missed with
     Add blueprint (pick it from the list or type its name).
  2. Blueprints are sorted into categories (Armor, FPS Weapons, Ship
     Components and so on). Click a category heading to fold it away or open
     it. To move a blueprint to another category, or make your own, click it
     and then Category... on the right.
  3. Click a blueprint to see its ingredients, craft time and what you get
     back from dismantling it.
  4. "All blueprints" shows every blueprint in the game. Click "I have this"
     to put one on your list, or "Remove from my list" to take it off.

- HCN Radio tab: click a station on the left to tune in (click it again, the
  big cover or Stop to stop; the space bar works too). It keeps playing while
  you use the other tabs. The volume is next to the Play button. If a station
  won't play, Open in browser plays it on hcnradio.com instead. HCN Radio is
  a free community project shared here with their permission: visit
  hcnradio.com and join their Discord to support them.
  Sound: Direct plays it as it comes; FM, AM and SW (shortwave) make it
  sound like a real ship radio, with hiss, hum, crackle and fading.
  Mini player: a small ship radio that stays on top of your other windows
  (drag it anywhere; the pin turns staying on top on or off). The size
  button next to the pin switches between wide, tall and small, and
  dragging its bottom-right corner makes it bigger or smaller. How
  see-through the pop-out windows are is set on the Home tab.
- HCN Radio theme: in Themes, next to Runner, the look of hcnradio.com.

GOOD TO KNOW
------------
- The Citizens tab only reads public pages on robertsspaceindustries.com.
  Nothing about you is sent anywhere.
- The Mining tab only looks at the box you picked on your screen, using
  the text reader built into Windows, and never touches the game. It needs an
  English text-reader language in Windows (Settings > Time & language >
  Language & region); most PCs already have it. Parts a player keeps private show as "-".
- The refinery timers only look at your screen when you press their key (or the
  button) and reads it with the text reader built into Windows. The picture
  is not saved or sent anywhere. Timers are kept in
  %APPDATA%\StarRunner\refinery.txt.
- The Hauling tab gets places and distances from UEX Corp (uexcorp.space), a
  public Star Citizen trade site, once a week. Nothing about you is sent.
- The Inventory tab only reads the game's log file (Game.log in the game's
  LIVE folder) to see where you last opened your inventory. It never changes
  anything in the game. If it can't find the log, use Tools > Find the game's
  log file. Your inventory is kept in %APPDATA%\StarRunner\inventory.txt.
- The Blueprints tab gets the recipes from the Star Citizen Wiki
  (api.star-citizen.wiki) once a week. Your blueprints and play time come
  from the game's log files and are kept in %APPDATA%\StarRunner. The RSI
  status comes from status.robertsspaceindustries.com. Nothing about you
  is sent.
- The HCN Radio tab plays HCN Radio's streams and gets what's playing and
  the station pictures from hcnradio.com. HCN Radio is run by HLN
  Corporation and is not part of StarRunner; the streams, pictures and logo
  are theirs. Nothing about you is sent.
- The Language Packs tab only writes to the game's language folder when you click
  Save to game (and it backs up the old file first). Language packs come
  from public GitHub pages; nothing about you is sent.
- RSI has no official lookup service, so if RSI changes its web page some
  details may come up blank.
- Your recent lookups, settings and the Mining signature table are kept in
  %APPDATA%\StarRunner. Language Packs changes files and downloaded packs are kept
  in Documents\LangRunner, and your notes in Documents\StarRunner Notes.
- Updates: a few seconds after it starts, StarRunner checks GitHub for a newer
  version (it only reads the public release page; nothing is sent). If there
  is one, "Update available" shows at the top right; click it to update. With
  the installer, it downloads and runs the new installer for you; with the
  no-install zip, it opens the download page. Right-click "Check for updates"
  to turn the startup check on or off.
- If something goes wrong, StarRunner-log.txt next to StarRunner.exe says what.
- To remove StarRunner: delete its folder and %APPDATA%\StarRunner.
```

