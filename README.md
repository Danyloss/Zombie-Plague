# Zombie-Plague
Zombie Plague /Polish by Danyloss
===============================================================================

                         Zombie Plague Release Notes
                                Version 5.0

                          Written by Nikita Ushakov

===============================================================================

Release Notes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

2016.04.11

================
MAJOR NEWS IN THIS RELEASE
================
Zombie Plague now more near half built on old Zombie:Reloaded modification.

Big thanks to:

Richard Helgeby & Greyscale


==============
CUSTOM MODELS
==============

This is quite obviously against the stated rules and will very likely get your server banned if reported even if it doesn't currently trigger the automatic detections.

Valve Model, Valve Texture = No.
Valve Model, Custom Texture = No.
Custom Model, Valve Texture = No.
Custom Model, Custom Texture = Appears to be OK currently.


================
 SOURCE CODE
================

The source code is bundled in every release and patch. It's located in
addons/sourcemod/scripting/ and prepared to compile once the SDK Hooks include
file is installed.

Source code repositories with build scripts are available on our side at GitHub:

  * https://github.com/qubka/Zombie-Plague

================
 INSTALLATION
================

Install the following requirements:

* Metamod:Source 1.10.6+
  http://sourcemm.net/
  
* SourceMod 1.7.3+
  http://sourcemod.net/

The version numbers listed above are minimum requirements. You should always get
the latest stable version.

Note: Verify that both Metamod:Source and SourceMod is running before
      continuing. Type these commands in the server console: "meta version" and
      "sm version". If both give version information it's working. If not, go
      through their installation instructions again and verify that everything
      is in the correct place.

When the requirements are installed the Zombie Plague release package can be
extracted into the "csgo" folder and all files should go in the correct
place.

Start the dedicated server and verify that Zombie Plague is running by typing
this command in the server console: "zp_version".

Check the SourceMod error logs if it's not working. Zombie Plague will
validate and log errors if something is wrong. Look for messages from
zbm3_core.smx.

================
 LIST OF CHANGES
================

  * Core of Zombie Plague build on Zombie:Reloaded and optimized only for Counter Strike: Global Offensive.
  * Many bug fixes and improvements. (More than 100) 
  * Huge amount of new cvars added. (More than 125 convars now)
  * Added improved random number generator from SMLIB. (Better random zombie, selection, etc.)
  * A lot of functions and stock was rewrited.
  * Add sky and sun chaning.
  * Added dymanic glow for nemesis and survivor.
  * Added custom sound and world models to survivor weapons.
  * Restoring health for zombie.
  * Gamemodes customizing.
  * Added config and log module from ZOMBIE:RELOADED.
  * Added human model module from ZOMBIE:RELOADED.
  * Added hitbox module from ZOMBIE:RELOADED.
  * Added weapons module from ZOMBIE:RELOADED. 
  * Added downloads module from ZOMBIE:RELOADED.
  * Added view model API for future purpose.
  * Added block items in menu.
  * Block pickuping weapon, if client level is less, than weapon level access.
  * Extra items devided to seperate plugins.
  * Removing teleporing grenade.
  * Dynamic sound module was added.
  * New custom sounds, like Flashlight, NightVision.
  * New knockback and damage system.
  * Added burning for zombie with damage and custom sounds.
  * New main menu on F button.
  * Antistuck and support of custom MotD.
  * Added improved gamemode system.
  * Added jump boost system.
  * Config module from ZOMBIE:RELOADED, can be used for reaploading all mod configs.
  * New paramparser system.
  * Level system for zombies.
  * Added admin commands loggin in zombieplague.log
  * Also, mod now can remove doors from maps.
  * Zombie footstep  sound can be disabled.
  * Zombies make a bleeding footsteps.
  * Remove support of zombie escape maps.
  * New deathmatch settings.
  * Infinity ammo for survivor, maked by sv_infinity_ammo cvar.
  * Added fov to zombie.
  * Added knockback boost settings.
  * Added ragdoll settings.
  * New setting, which can delete dropped weapons.
  * Added @ flag to zombie classes and extra items name, which will get name from translation files.
  * New fixed admin menu + new section 'Give ammopacks'
  * Added a lot of new translation messages
  * Added a lot of new sounds, like gamemode sounds, nemesis pain, etc
  * Bug fix when claws models still left on next round
  * Added different flags access for zombie admin menu
  * Added infinity reserve ammo for bots
  * Fix with Zombie VIP classes if they on the first position in the menu
  * Added random zombie choosing for bots
  * Fix with removing dropped model on timer
  * Leap jump work just on CTRL+SPACE
  * Bug fix with m_iState offset
  * Weapon ammo fix for custom weapons
  * Remake weapon ammo system. Grenades now not unlimited
  * Fixes with removed level system
  * Fixes in lasermine addon
  * Update some extraitems
  * Update lasermines addon (Damage must applied only for zombies)
  * Fix bug with cheat convars
  * Added cvar to disable custom weapon models
  * Fix bug with dropping database (Thanks to hola22 for reporting)
  * When you disable footsteps sounds for zombie, standart footsteps for them disable too
  * Update extraitems to ver 2.0
  * Update of zombieplague.inc (Added new natives)
  * Added smlib to mod folder for future addons
  * Added feature to precache whole folder in the downloads.ini
  * Optimisation
  * Update of some addons
  * Added removing light_dynamic if client is change class.
  * If player use antidot, he teleports to spawn
  * Include update, added new native ZP_GetClientViewModel()
  * Fix with custom weapon addons
  * Remaked custom weapon module
