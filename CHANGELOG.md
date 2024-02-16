# Version 2.0.2:

Hotfix 2 for update 2.0 Phase 1. Very similar changes to hotfix 1.

- Reworked Coalesce:
Same scenario as Magmatic and Brickwork changes in 2.0.1;
Removed the saws;
Made OH logo dynamic component of level;
Made platforms taller and adjusted spacing;
Slowed down movement of platforms;
Attached more ropes between platforms for stability and made ropes invisible;
Added a mechanical themed background;
Changed platform color

- Reworked Weave:
Replaced mechanical saw system with consistent animation system;
Saws now fall in a straight line over 2 seconds and then pause for 2 seconds;
Saws alternate between center and perimeter drops;
Saws are all the same size now;
Tweaked platform positioning;
Moved hazard signs to top and increased opacity;
Moved 2 spawns to have less immediate line of sight on enemies;

- Fixed Cavernous:
Forgot to add an OH logo

- Tweaked Monsoon:
Reduced color intensity of background, which should make it less faded and even slightly transparent, to improve map clarity; 
Further improvements to map clarity will be made across the board when image opacity bug is fixed

- Adjusted README images to reflect the minor visual changes made in hotfixes

---
# Version 2.0.1:

Hotfix to the big 2.0 Phase 1 update - this is not Phase 2. Fixing some issues and adding in one map rework that was delayed due to a bug in a dependency mod (I removed a minor feature to work around it).

- Renamed Tic-Tac-Toe to Criss Cross (I forgot how on-the-nose this name was when doing my other naming scheme changes.)

- Reworked Magmatic:
Swapped out blocks for magmatic rock sprites;
Added a fitting volcanic background;
Added a lava background to make the lava more clear;
Added more platforms;
Added a danger sign;
Made tweaks to platform positioning and eruption mechanism

- Fixed Brickwork: 
Note that this was going to be a delayed rework due to the same issues as Magmatic, but I am partially releasing it now having removed several planned features in order to hotfix an issue;
Fixed the old image not loading in and replaced it with a brand new level image with much less clutter

- Tweaked Herpetology:
Lowered the bottom platforms and removed an oddly positioned "food" platform

- Fixed Rotational:
Background image was a tad too small

- Tweaked Overhaul:
Made level image brighter to outline all map elements better

- Tweaked Kaleidoscopic:
Removed bottom right lasers from level image as it was confusing

- Tweaked Arachnophobia:
Removed UI elements from level image

- Tweaked Geometric:
Removed UI element from level image

- Tweaked Improvisation:
Removed central text from level image

- Restructured README

---
# Version 2.0.0:

This is phase one of Overhaul Maps 2.0, where I plan to revamp all my existing maps and add tons of new ones over the course of a couple updates. I would like to thank everyone that has done playtesting for me during this process as well as anyone who generally gave feedback or support.

- Added 20 new maps: 
Aethereal, Arachnophobia, Cavernous, Entomology, Geometric, Improvisation, Inspired, Kaleidoscopic, Last Resort, Monsoon, Necrosis, Progenitor, Purple Rain, Quackrobatics, Romantik, Styxian, Terrafic, Underwhelm, Vendetta, and Zuology (with many more to come in the future)

- Renamed 3 maps to better fit current naming scheme: 
Holy Mountain -> Brickwork; Hyper Tubes -> Pneumatic; Pinball Machine -> Pinballin'

- Reworked Oscillating: 
Swapped out existing components with more illusionary and mystical sprites; 
Replaced moving platform with two moving platforms that go in opposite directions and no longer move off the map; 
Added much more cover and ways to manueveer; 
Added a fitting background

- Reworked Overhaul:
Map is now square shaped via map boundary changes;
Changed background to something morea akin to the (old) mod icon;
Removed lettering and swapped in new letters from sprites and logos of various games (that are either represented or soon to be represented in the mod);
Instead of one row reading "OVERHAUL", it is now a 4x3 grid reading "OVER HAUL MAPS"

- Tweaked Pneumatic:
Added a futuristic background;
Added more force to downward force zones so they can't be easily bypassed

- Tweaked Recursion:
Added more cover;
Added a recursive background;
Tweaked some platform sizes a tiny bit

- Tweaked Weave:
Added more platforms for better manuevering;
Added a factory-like background;
Added some hazard signs

- Tweaked Falling Down:
Added a fitting background;
Reduced the alpha of all platforms to remove the glow

- Tweaked Pipe Dream:
Added a fitting background;
Added a friend to dodge pipes with you;
Made pipes more opaque and slightly tweaked colors

- Tweaked Rotational:
Added destructible boxes to bottom as cover;
Made map rotate slower;
Made boxes black instead of brown;
Added a fitting background;

- Tweaked Origins:
Added CRT scan lines

- Tweaked Title:
Added a background resembling the main menu

- Tweaked Poltergeist:
Moved one of the spawns to a less crowded area;
Added a spooky background

- Reworked Emulation:
Increased size of all level elements;
Broke the TV and increased map dimensions so that players can manuever to more areas;
Added a error background to the TV and a living room background to the overall level

- Tweaked Herpetology:
Added a fitting background

- Tweaked Homestead:
Added a forests background;
Reduced the opacity of existing background elements

- Tweaked Ruins:
Added a ruined city background;
Shifted the position of the rightmost box

- Tweaked Laboratory:
Added a lab background

- Fixed Wipout:
Fixed minor visual error;
Not revamped... yet!

- Tweaked Elementary:
Removed the saws;
Not revamped... yet!

- Changed mod icon and tweaked README

- More to come!

---
# Version 1.6.2:

- Moved OH logo (mostly) to places that won't affect gameplay so that saws can be removed (they are loud); affected maps are: As Above, Balance, Broadside, Cyclic, Down Under (did not have one before), Flip Flop, Lurch, Origins, Rotational, Serpentine, Sinkhole, So Below, and Wipeout

- Tweaked Serpentine: added ground under snake and to sides

- Tweaked Cyclic: made central platforms colored

- Tweaked Lurch: made central platforms colored

- Tweaked Broadside: OH logo is now underwater cover

- Tweaked Sinkhole: OH logo is now a physics object in center

- Tweaked Flip Flop: OH logo is now 2 stable platforms at bottom to fight over

- Tweaked Wipeout: OH logo is now a physics object in center

- Tweaked Galleons: removed saws

- Tweaked As Above: OH logo is now platform at bottom to fight over/shoot blocks from

- Tweaked So Below: OH logo is now physics object that floats at bottom

- Tweaked Pipe Dream: kept OH logo since it provides to tactical advantage, but still removed saw

- Tweaked Emulation: fixed README image

- Various tweaks and updates to README and manifest files

- Preparing something big...

---
# Version 1.6.1:

- Tweaked HolyMountain: used new MapImageObjects features to manually add collision to an upscaled, non-edited version of the level image

- Migrated all README images from Discord to Github

---
# Version 1.6.0:

- Added BetterChat as a dependency for chat legibility on enlarged maps

- Added MapImageObjects as a dependency for Holy Mountain and more future maps

- Added Antechamber, Herpetology, Holy Mountain, Homestead, Laboratory, Locomotive, and Ruins

- Reworked Pinball Machine: added some platforms and a force zone for improved manueverability and added a pinball moving light effect

- Tweaked Down Under: made the camera size bigger and no longer upside-down and increased map size

- Tweaked Emulate: made it slightly bigger

- Tweaked Probability: removed the destructible box at the top now that spawns are consistent

- Fixed Cyclic: removed a number of unused map components off screen

---
# Version 1.5.1:

- MapsExtended 1.3.1 means border and screen alignment issues on non-1920x1080-resolutions should be fixed (accidentally slipped through while doing QA whoops)

- Added Down Under (sort of made this map on accident yesterday)

- Fixed Nostalgia: viewport height was too large - settings were leftover from testing

---
# Version 1.5.0:

- MapsExtended 1.3.0 means animated maps are compatible with MapEmbiggener now

- Added Emulation (uses new map/camera size functions)

- Tweaked Enginery: improved spacing on platform and swapped from physics-based reciprocating motion boxes at top to animation based movement

- Tweaked Hyper Tubes: made blocks much less bright, tweaked some block positioning/sizes to improve manueverability, and tweaked force zone placement

- Fixed Elementary: minor static animation visual errors

- Fixed Serpentine: moved top ropes higher to prevent rare instances of clipping

- Tweaked Origins: made central dividing line more transparent to not confuse players into thinking they're in the foreground

- Reworked Ghastly: added some platforms to outer sides and tweaked positioning of sprites there to improve manuever and give better spawn points

- Tweaked Poltergeist changed map logo area to platform to fix minor visual bug

- Tweaked Lurch: moved indicator arrows to center for better visibility

- Tweaked Nostalgia: moved unsightly force zones and fixed rare instance of barrel getting stuck at top girder

- Various Changes to Map Bottoms: fixed instances of rarely clipping under the map on Ghastly, Origins, Miniature, Nostalgia, Pipe Dream, and Recursion

---
# Version 1.4.2:

- Added Celestial (Happy Overhaulloween)

- Tweaked Nostalgia: cleaned up all ladders and made them animation based; removed a ladder up top to give that area more space

- Tweaked Rotational: made outer wall rotation ~67% slower to reduce cases of clipping and to make getting to the center (same speed as before) more manageable

---
# Version 1.4.1:

- Added Poltergeist

- Changed Ghastly: made the side areas of the map accessible to make the map less restrictive and lowered the text to accomodate this playstyle; tweaked spawn locations

- Tweaked Elementary: made water and space zones more visible via background walls, increased platform lengths, and reoriented the right yellow triangle

- Tweaked Cyclic: moved the holes around to make manuevering the map easier

- Tweaked Magmatic: moved off-screen ball that was rarely affecting player spawns

- Tweaked Trenches: fixed minor animation issue

---
# Version 1.4.0:

- Added Title, No Internet, Ghastly and Tic Tac Toe

- Tweaked Hyper Tubes: filled in empty spaces to fix clipping and weird spawn issues

- Tweaked Falling Down: made walls ~40% taller to improve manueverability

- Tweaked Division: reduced saw sizes to fix rare instances of players being damaged through floors and doubled divider speeds to promote faster gameplay

- Tweaked Origins: added platforms below the paddles to make up for their unpredictable nature causing early deaths

- Thanks for 100k downloads!

---
# Version 1.3.2:

- Tweaked As Above: fixed spawn issue, lowered the platform, and widened spawn boxes

- Tweaked Falling Down: cut platform speed in half to fix cases of clipping through and tweaked platform placement

- Tweaked Lurch: added more holes and platforms for improved manueverability

- Tweaked Miniature: fixed cases of balls being stuck, added platform to right of map, added tunnel in windmill center, added lips to windmill fans to improve ball launching, and improved ball distribution to land on more platforms

- Tweaked Origins: made small changes to ball animation to be more fluid

- Tweaked Pipe Dream: made pipes ~25% wider

- Tweaked Recursion: added platforms to improve map manueverability

---
# Version 1.3.1:

- Tweaked Orbitals: added various background walls to outline walls and space zones for better readibility

- Tweaked Revolution: made platforms 50% slower, made static platforms shorter, and removed the walls

- Tweaked So Below: made background walls static and removed many ropes to reduce shaking on some clients; increased the amount of debris that can fall off the bridge

- Tweaked Mini Golf: removed the white golf ball and made the magenta ball purple for better readibility

- Tweaked Pinball Machine: removed two pinballs

- Tweaked Elementary: added clear dividing lines using background walls for readibility

- Tweaked Weave: made the green boxes invisible instead so they are not distracting or misleading

- Tweaked Galleons: reduced the amount of physics objects on the map in an attempt to remove shaking on some clients

- Tweaked Overhaul: slighty changed map colors and positions and made them static to remove shaking on some clients

- Tweaked As Above: made background walls static and removed ropes

- Tweaked Balance: made central stand more transparent to reduce any confusion

- Added Map Logo to Rotational, Pipe Dream, and Origins

---
# Version 1.3.0:

- Added Rising Up, Origins, Pipe Dream, and Rotational

- Tweaked Broadside: made lower boxes thinner to fix spawns, and made destructible boxes yellow to stick out more

- Tweaked Cyclic: slowed hazard to be more managable and added indicator arrows to choreograph its movement

- Tweaked Lurch: slowed hazard to be more managable and added indicator arrows to choreograph its movement


---
# Version 1.2.8:

- Changed Trenches: added more boxes that are smaller as to not disrupt spawns

- Changed Oscillating: replaced the lower moving platform with an animated one

- Changed Falling Down: now uses wider, slower, more evenly spaced boxes for better gameplay and spawn fixes

- Changed Division: now uses animated moving boxes that are wider and alternate for consistency and reduced lag

- Tweaked Coalesce: made platforms closer together and centered and split the OH logo

- Tweaked Flipside: changed the platform colors for one map state and added an indicator to the top of the map that shows when the map changes

- Tweaked Lurch, Serpentine, Cyclic, Revolution, Miniature, and Nostalgia: slightly tweaked platform length, position, size, or quantity

- Changed the Overhaul (OH) logo on most maps to use a saw instead of lava/acid to prevent people from playing on it

---
# Version 1.2.7:

- Misc. tweaks to Cyclic, Lurch, Oscillating, Revolution, Pinball Machine, Miniature, Flipside, Magmatic, Hyper Tubes, So Below, and Broadside in an attempt to make spawns more consistent

- Tweaked Nostalgia: minor fix to an animation

- Tweaked Serpentine: made changes to prevent the ball from clipping through

- Tweaked Coalesce: moved the map up due to seeing the platforms drop below the boundary in some games

- Tweaked Division: made the engine a bit stronger due to it not properly starting in rare cases

- Changed Trenches: made all boxes animation based so they float; made all passages connected to fix spawns; misc. adjustments

- Changed Orbitals: various position and sizes changes to platforms to make the map more balanced and manueverable

---
# Version 1.2.6:

- Tweaked Falling Down: moved a spawn to help with consistency

- Tweaked Miniature: moved outer walls to make side map boundaries proper hazards

- Tweaked Pinball: reverted last change; it fixed nothing and made more issues

- Fixed Serpentine: made various tweaks that allowed the lowered mass ball to move the snake again

- Changed Lurch: made the map hazard take up less of the map when stationary and reworked upper half to fix spawns and balance both halves

---
# Version 1.2.5:

- Misc. tweaks to Lurch, Nostalgia, Falling Down, Oscillating, Revolution, Pinball Machine, and Orbitals in an attempt to have more consistent spawns

- Changed Probability: everyone spawns on a nice flat platform that breaks right away to hopefully fix spawns

- Changed Trenches and As Above: added small boxes to spawn on to hopefully fix spawns

- Tweaked Cyclic: changed saw positioning to be more consistent

- Tweaked Division: made changes to reduce the chances of stopping the mechanism of the map

- Tweaked Broadside: made cannons easier to activate and made sea mines stop bouncing around

---
# Version 1.2.4:

- Tweaked Coalesce: now partially animation based now that ball engine mechanisms don't function as well (the reciprocating motion platforms were too fast when fixed); moves a bit slower overall

- Fixed Division: still uses a ball engine, but just added a lot more force zones

- Changed Enginery: lower ball engine broke, so the mechanism was changed to 2 platforms that move with animations; the upper ball engine that uses reciprocating motion platforms was fixed; the breakable boxes were made bigger and break to the saws now; added lots of cover

- Tweaked Magmatic: ball distribution should be more even between left and right

- Tweaked Miniature: changed the golf club and a few other minor areas to compensate for new ball mass in Maps Extended

- Tweaked Nostalgia: barrels should roll more smoothly and set on fire more evenly

- Tweaked Pinball: made bumpers thinner to compensate for new ball mass; fixed issue with pinballs rarely clogging up

- Changed Revolution: platforms now animation based (platforms were formerly attached to a ball engine which again now act odd with reduced ball mass)

---
# Version 1.2.3:

- Attempt to fix more spawn points

---
# Version 1.2.2:

- Tweaked Serpentine: tongue thickness increased to prevent clipping through

- Tweaked Miniature: minor misc. changes for consistency

- Tweaked Oscillating: all spinning blocks now use animations to avoid inconsistency and ropes failing to load; lower platform moves faster; made map more symmetrical

- Tweaked Cyclic: saw size and positon changed so that players are no longer safe on the main platform

- Tweaked spawn points for several maps to avoid faulty spawns

---
# Version 1.2.1:

- Fixed Balance: now properly sways again

- Fixed Coalesce: platforms no longer go too far off screen

- Tweaked Elementary: very minor tweaks to positioning

- Fixed Pinball Machine: saws static again

- Fixed So Below: duplicate box removed

- Changed Weave: saw sizes reduced, saw colors made more distinct, and 4 saws replaced with harmless green background blocks

- Updated some map images in README

---
# Version 1.2.0:

- Got maps fixed so that they (should) no longer have missing components

- Removed BossSloth's ExtraMapObjects since their color blocks are now redundant; all old color blocks have been swapped to the new ones

- Added Falling Down

- Visual updates to As Above, Balance, Broadside, Coalesce, Cyclic, Division, Elementary, Enginery, Hyper Tubes, Lurch, Magmatic, Miniature, Nostalgia, Orbitals, Oscillating, Overhaul, Pinball Machine, Revolution, Sinkhole, and So Below

- Changed Broadside: sea mines and cannon balls are now deadlier

- Changed Cyclic: hazard now uses animation instead of physics for consistency and map balance between upper and lower levels

- Tweaked Elementary: had some very minor layout changes

- Changed Lurch: hazard now uses animation instead of physics for consistency and map balance between upper and lower levels and even distribution

- Tweaked Magmatic: minor changes to how hazards are delivered

- Tweaked Miniature: very minor layout changes

- Tweaked Nostalgia: various tweaks and some fun additions

- Updated every map image in README
---

# Version 1.1.0:

- Now using MapEditor 1.0ish

- Added Miniature and Flipside
---

# Version 1.0.4:

- Changed Division: added a lower route to increase map manuevering options and have alternate routes for slow players or 

- Tweaked Recursion: added access to map boundary in bottom corners to enable block jumping as an alternative manuevering option
---

# Version 1.0.3:

- Changed As Above: reduced the number of boxes by making dividing boxes tall and take up an entire row in order to make the map's gimmick more relevant

- Changed Cyclic: lowered upper boxes and spawns to make it easier for lower spawns to break and allow for the saw to disrupt upper levels; misc. tweaks

- Changed Hyper Tubes: made the force zones less powerful

- Changed Nostalgia: made lava hazards larger and added visual indicators; several misc. tweaks

- Changed Orbitals: replaced bottom arrow with 2 diagonal arrows to fix initial spin and make fights at bottom more interesting

- Changed So Below: made destructible boxes larger and gray blocks smaller to make the map's gimmick more relevant

- Changed Weave: adjusted off-screen force zones to hopefully fix the initial spin
---

# Version 1.0.2:

- Replace ReducePostFX with ToggleEffects
---

# Version 1.0.1:

- Changed Oribitals force zones to be more balanced

- Tweaked Galleons spawns

- Slowed down Division and Weave dynamic elements to be less frustrating

- Various minor tweaks to positioning in Pinball Machine to be more symmetrical

- Made So Below visual elements of bridge less ugly

- Updated some README images
---

# Version 1.0.0:

- Added Coalesce, Weave, Division, As Above, and So Below

- Added all missing map images to README

---

# Version 0.11.1:

- Removed unecessary dependencies

---

# Version 0.11.0:

- Added Recursion, Revolution, and Enginery

- Made decorative barrels on Nostalgia static

---

# Version 0.10.1:

- Fixed Trenches; scaled up the map ~4x to reduce the amount of map objects needed to load and to make it easier to manuever the map

- Reworked Pinball Machine; made both bumpers more stable, added a second route on right side for balls to come from, added lava to both tubes to make balls more hazardous, doubled ball amount, tweaked minor placements

- Reinforced Serpentine; should hopefully not just fall apart easily now; also added more platforms

- Changed the box "barrels" at top right of Nostalgia to more 8-bit inspired barrel objects

---

# Version 0.10.0:

- Added Galleons, Trenches, Hyper Tubes, and Pinball Machine

- Added ReducePostFX

- Added some map images to README

---

# Version 0.9.0: 

- Added Flip Flop and Wipeout

---

# Version 0.8.1: 

- Made Sinkhole sink much slower

- Added watermark to Elementary

- Added some map images to README

---

# Version 0.8.0: 

- Added Elementary and Sinkhole V2 - will be keeping an eye on Sinkhole.

---

# Version 0.7.1: 

- Fixed some issues with barrels on Nostalgia

---

# Version 0.7.0: 

- Added Nostalgia

---

# Version 0.6.4: 

- Removed Sinkhole for being unstable

---

# Version 0.6.3:

- Tweaked Lurch lower platform height and Broadside left seamine

- Added README GIFs and misc. adjustments

---

# Version 0.6.2: 

- Tweaked Magmatic spawns

---

# Version 0.6.1: 

- Updated map images

---

# Version 0.6.0:

- Added Overhaul, Broadside, Sinkhole, Probability, and Magmatic

- Made all maps 8-player compatible

---

# Version 0.5.1:

- Updated map images

---

# Version 0.5.0:

- Added Balance and Lurch

- Reworked Orbitals

- Tweaked Serpentine and Oscillating

---

# Version 0.4.4:

- Fixed README

- Added map descriptions

- Started actually using Markdown Preview

---

# Version 0.4.3:

- Tweaked all 4 maps and added README changelog

---

# Version 0.4.2:

- Tweaked Oscillating and Serpentine

- Fixed Discord Links

---

# Version 0.4.1:

- Fixed README

---

# Version 0.4.0:

- Added Oscillating

- Added README map images

---

# Version 0.3.1:

- Tweaked README

---

# Version 0.3.0:

- Tweaked Serpentine

- Added Performance Improvements mod for screen shake issues

---

# Version 0.2.0:

- Reworked Orbitals and Serpentine

---

# Version 0.1.1:

- Tweaked Orbitals and Cyclic

---

# Version 0.1.0:

- Added Cyclic

---

# Version 0.0.3:

- Added Serpentine

- Tweaked Orbitals

- Added map watermarks

---

# Version 0.0.2:

- Tweaked Orbitals and README

---

# Version 0.0.1:

- Added Orbitals