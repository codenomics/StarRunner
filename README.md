# StarRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v2.0** (Oct 12, 2026)

- [StarRunner_v2.0_no-install.zip](https://github.com/codenomics/StarRunner/releases/download/v2.0/StarRunner_v2.0_no-install.zip) - 586 KB
- [StarRunner_v2.0_Setup.exe](https://github.com/codenomics/StarRunner/releases/download/v2.0/StarRunner_v2.0_Setup.exe) - 645 KB
- [StarRunner_v2.0_source.zip](https://github.com/codenomics/StarRunner/releases/download/v2.0/StarRunner_v2.0_source.zip) - 573 KB

What's new in v2.0:

- New Blueprints tab: the blueprints you have (picked up from the game logs when you receive one, plus any you add by hand) and the ingredients each takes to craft, from the Star Citizen Wiki. Sorted into categories you can fold away, and you can make your own categories
- Home tab: RSI server status at the top, checked every 10 minutes, with a link to the status page
- Home tab: your total play time from the game logs, with this week and today. It keeps counting after patches
- Turn off the tabs you don't use (Home tab > Turn tabs on or off...)
- New HCN Radio tab: listen to HCN Radio's fan-made Star Citizen stations right inside StarRunner, with station covers and what's playing now. It keeps playing while you use the other tabs. Shared with permission from HCN Radio - go check them out at hcnradio.com
- New HCN Radio theme, based on hcnradio.com (Themes, next to Runner)

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
STARRUNNER
==========

All your Star Citizen tools in one window, with a tab for each tool.
The Citizens tab looks up a Star Citizen player by their handle and shows
their public RSI profile: avatar, citizen record number, enlisted date,
location, fluency, badge, organizations (with their rank) and bio.
The Mining tab reads the mining scan number off your screen in Star
Citizen and shows which rock it is in a small see-through overlay.
The Language Packs tab edits the game's language file (global.ini) and keeps your
edits so they can be put back on every new version. The Notes tab is a light
notepad: a list of notes on the left and the text on the right. The Inventory
tab keeps track of what you have stored where, across the universe, and knows
where you last opened your inventory in game. The Hauling tab works out the
best order to fly your cargo contracts. The Blueprints tab lists the
blueprints you have and what each takes to craft. The HCN Radio tab plays
HCN Radio's fan-made Star Citizen stations. The Home tab also shows
the RSI server status and your total play time.


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
  Tabs you don't use can be turned off with "Turn tabs on or off..." under
  the tool list (nothing in them is deleted); Turn on brings one back.
- Themes (button at the top, or Themes... on the Home tab): previews of every
  look - Runner, plus looks from the ship makers' cockpit screens (Aegis,
  Aopoa, Argo, Banu Souli, Crusader, Drake, Esperia, Gatac, Grey's Market,
  Kruger, MISC, Origin, RSI). Pick one and click Restart now to use it.
- Citizens tab: type a player's handle (the name in the address of their
  RSI profile) and press Enter or click Look up.
- Mining tab:
  1. Click Pick area, switch to the game and scan a rock so the number shows.
     After 5 seconds the screen freezes - drag a box around the number.
     (Any game window mode works: Borderless, Windowed or Fullscreen.)
  2. Click Start reading. The overlay shows e.g. "3x Titanium" while the
     number is on screen. It keeps working while you use the other tabs.
  The Signatures button opens the table of scan numbers (you can fix or add
  values after game updates). Press F1 for more help.
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
- Click any name in the Recent list to look that player up again.
- Their organizations are listed with the player's rank in each. Click one
  to see its Overview, History, Manifesto, Charter and a Members list.
- "Open on RSI website" opens their page in your browser.


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
  5. Contracts from the game: when you accept a hauling contract in game,
     StarRunner offers to add it (with the places, and the SCU when the game
     logs it - check it and add the reward). When the game says a contract is
     complete, it asks before checking off its stops. It only reads Game.log
     and only asks while you're looking at the Hauling tab.
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
- HCN Radio theme: in Themes, next to Runner, the look of hcnradio.com.

GOOD TO KNOW
------------
- The Citizens tab only reads public pages on robertsspaceindustries.com.
  Nothing about you is sent anywhere.
- The Mining tab only looks at the box you picked on your screen, using
  the text reader built into Windows, and never touches the game. It needs an
  English text-reader language in Windows (Settings > Time & language >
  Language & region); most PCs already have it. Parts a player keeps private show as "-".
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

