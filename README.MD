Friday Night Funkin' - Psych Engine
Engine originally used on Mind Games Mod, intended to be a fix for the vanilla version's many issues while keeping the casual play aspect of it. Also aiming to be an easier alternative to newbie coders.

Installation:
You must have the most up-to-date version of Haxe, seriously, stop using 4.1.5, it misses some stuff.

Follow a Friday Night Funkin' source code compilation tutorial, after this you will need to install LuaJIT.

To install LuaJIT do this: haxelib git linc_luajit https://github.com/AndreiRudenko/linc_luajit on a Command prompt/PowerShell

...Or if you don't want your mod to be able to run .lua scripts, delete the "LUA_ALLOWED" line on Project.xml

Credits:
Shadow Mario - Coding
RiverOaken - Arts and Animations
bbpanzu - Assistant Coding
Special Thanks
shubs - New Input System
SqirraRNG - Chart Editor's Sound Waveform base code
iFlicky - Delay/Combo Menu Song Composer + Dialogue Sounds
PolybiusProxy - .MP4 Loader Extension
Keoiki - Note Splash Animations
Smokey - Spritemap Texture Atlas support
Cary - OG Resolution code
Nebula_Zorua - VCR Shader code
Features
Attractive animated dialogue boxes:
127706669-71cd5cdb-5c2a-4ecc-871b-98a276ae8070.gif

Mod Support
Probably one of the main points of this engine, you can code in .lua files outside of the source code, making your own weeks without even messing with the source!
Comes with a Mod Organizing/Disabling Menu.
Atleast one change to every week:
Week 1:
New Dad Left sing sprite
Unused stage lights are now used
Week 2:
Both BF and Skid & Pump does "Hey!" animations
Thunders does a quick light flash and zooms the camera in slightly
Added a quick transition/cutscene to Monster
Week 3:
BF does "Hey!" during Philly Nice
Blammed has a cool new colors flash during that sick part of the song
Week 4:
Better hair physics for Mom/Boyfriend (Maybe even slightly better than Week 7's 👀)
Henchmen die during all songs. Yeah :(
Week 5:
Bottom Boppers and GF does "Hey!" animations during Cocoa and Eggnog
On Winter Horrorland, GF bops her head slower in some parts of the song.
Week 6:
On Thorns, the HUD is hidden during the cutscene
Also there's the Background girls being spooky during the "Hey!" parts of the Instrumental
Cool new Chart Editor changes and countless bug fixes


You can now chart "Event" notes, which are bookmarks that trigger specific actions that usually were hardcoded on the vanilla version of the game.
Your song's BPM can now have decimal values
You can manually adjust a Note's strum time if you're really going for milisecond precision
You can change a note's type on the Editor, it comes with two example types:
Alt Animation: Forces an alt animation to play, useful for songs like Ugh/Stress
Hey: Forces a "Hey" animation instead of the base Sing animation, if Boyfriend hits this note, Girlfriend will do a "Hey!" too.
Multiple editors to assist you in making your own Mod
Screenshot_3

Working both for Source code modding and Downloaded builds!
Story mode menu rework:


Added a different BG to every song (less Tutorial)
All menu characters are now in individual spritesheets, makes modding it easier.
Credits menu
Screenshot_1

You can add a head icon, name, description and a Redirect link for when the player presses Enter while the item is currently selected.
Awards/Achievements
The engine comes with 16 example achievements that you can mess with and learn how it works (Check Achievements.hx and search for "checkForAchievement" on PlayState.hx)
Options menu:
You can change Note colors, Delay and Combo Offset, Controls and Preferences there.
On Preferences you can toggle Downscroll, Middlescroll, Anti-Aliasing, Framerate, Low Quality, Note Splashes, Flashing Lights, etc.
Other gameplay features:
When the enemy hits a note, their strum note also glows.
Lag doesn't impact the camera movement and player icon scaling anymore.
Some stuff based on Week 7's changes has been put in (Background colors on Freeplay, Note splashes)
You can reset your Score on Freeplay/Story Mode by pressing Reset button.
You can listen to a song or adjust Scroll Speed/Damage taken/etc. on Freeplay by pressing Space.
