## v0.3.17-alpha
 - **Fix** Crash caused by connecting to websocket through android/macos due to Arc Runtime not being set

## v0.3.16-alpha
 - **Fix** Move trigger duration setting to 114 when copied with 0.5
 - **Fix** Check for null objects when trying to do object duplication
 - **Fix** Collision block edits not saving
 - **Fix** Undoing duplicated objects not deleting said objects

## v0.3.15-alpha
 - **Fix** Rotation when using keyboard to rotate multiple objects at once
 - **Fix** BetterEdit scale and rotate input boxes

## v0.3.14-alpha
 - **Fix** Scale and rotation issues, including scale hacks (praying), please report if you still come across issues

## v0.3.13-alpha
 - **Fix** Song trigger prep values not saving
 - **Fix** Wsx randomly failing while receiving, causing actions to not load

## v0.3.12-alpha
 - **Add** Use dankmeme's wsx for websockets! yay!
 - **Fix** Abnormal level kicking failing
 - **Fix** Crash on exiting the game on MacOS

## v0.3.11-alpha
 - **Fix** Crash caused in scaling objects related to Mega Hack slider bypass

## v0.3.10-alpha
 - **Fix** Limit Scale command to -1000 to 1000 in client in order to not cause game crashes
 - **Fix** Actions not appearing when connection fails on first open
 - **Fix** Crash with Better Easings Menu when loading some trigger actions

## v0.3.9-alpha
 - **Fix** UI appearing early when connecting to level

## v0.3.8-alpha
 - **Add** 2.2081 support!
 - **Fix** Disable keyboard rotation when warp is active, will debug later

## v0.3.7-alpha
 - **Fix** Default values not sharing after editing a trigger or similar (duration to 0.5, alpha trigger opacity to 1.0 etc.)

## v0.3.6-alpha
 - **Add** A testing option that allows for the host to disable viewing other's usernames for editors and viewers
 - **Fix** Move Editor Overlay that shows object selection rectangles into the UI mod

## v0.3.5-alpha
 - **Fix** Duplicating offsetable rotated objects losing their offsets after duplication

## v0.3.4-alpha
 - **Fix** Incompatibilities with Free Snap, Better Move Menu, Clone and Move
 - **Fix** Rotating a single object with a rotate wheel breaking offsetting

## v0.3.3-alpha
 - **Fix** Create loop not setting spawn triggered and multi trigger
 - **Fix** Lots of non-zero default values in triggers getting reset back to 0 when edited different values
 - **Fix** Keyframe object auto layer property

## v0.3.2-alpha
 - **Fix** Keyframe objects, hopefully
 - **Fix** Objects getting placed at layer -1
 - **Fix** Build helper gradient id and gradient trigger
 - **Fix** New Group X/Y buttons
 - **Fix** Orange teleport portals teleporting to the floor

## v0.3.1-alpha
 - **Fix** Binary not loading on MacOS due to missing ZLib
 - **Fix** Binary not loading on Android due to old NDK
 - **Fix** Pixel objects being scaled down
 - **Fix** Build Helper and Regroup buttons

## v0.3.0-alpha
 - **Add** Android, iOS and MacOS support!
 - **Fix** Another try at fixing the link & unlink buttons
 - **Fix** Another try at fixing the object layers
 - **Fix** Layer issue when trying to place an object when the object is in a different layer

## v0.2.20-alpha
 - **Fix** Create Loop button again
 - **Fix** HSV and color overlay with triggers not registering
 - **Fix** Rotate animations of saws
 - **Fix** Crash with custom objects mods might add
 - **Fix** Duplicating objects that have been move trigger moved by someone else

## v0.2.18-alpha
 - **Fix** Some reconnect issues
 - **Fix** Crash related to placing objects with filter enabled
 - **Fix** Breaking the log indent

## v0.2.17-alpha
 - **Fix** Editor layers not updating on placed objects
   - You need to be updated to both send and receive this fix
 - **Fix** Some complex rotation desync when moving and rotating and scaling at the same time
 - **Fix** Crash when placing objects, but not registered as selected

## v0.2.16-alpha
 - **Fix** Keyframe Anim Trigger moving to 0,0
 - **Fix** Rotate Gameplay Trigger trigger channel resetting
 - **Fix** Area Triggers special target resetting
 - **Fix** Spawn ordered, preview disable, target control id resetting

## v0.2.15-alpha
 - **Fix** Crash related to 1 object custom objects
 - **Fix** No Touch option not working

## v0.2.14-alpha
 - **Fix** Add some null checks where Robtop also has them

## v0.2.13-alpha
 - **Fix** Crash caused by the HSV overlay

## v0.2.12-alpha
 - **Fix** Regroup and Create Loop buttons
 - **Fix** Audio Line Trigger, Count Trigger, Item Trigger, Rotate Gameplay, Spawn Particle, SFX Trigger, and Timer Trigger zero resets

## v0.2.11-alpha
 - **Fix** More desync issues
   - Move, rotate, and scale issues after opening the rotate, scale or warp overlays
   - Nothing updating after opening the HSV overlay
 - **Fix** Crash after moving a deleted object
 - **Fix** Crash after moving an extended collision object
 - **Add** Tracking for start pos objects

## v0.2.10-alpha
 - **Fix** Desync issues with the HSV overlay
 - **Fix** Paste state and paste color buttons
 - **Fix** Copy+ color and paste+ color buttons

## v0.2.9-alpha
 - **Add** Crash recovery setting

## v0.2.8-alpha
 - **Fix** Counter objects
 - **Fix** Stop triggers (and resume and pause)
 - **Fix** Advanced random triggers
 - **Fix** Exiting putting you back into the main menu
 - **Fix** Particle object use object color

## v0.2.7-alpha
 - **Fix** Camera triggers
 - **Fix** Area triggers
 - **Fix** Gradient trigger
 - **Fix** Keyframe trigger and object
 - **Fix** Group parent
 - **Fix** Anim button
 - **Fix** 40000 error opening on unrelated levels

## v0.2.6-alpha
 - **Fix** Dash orbs
 - **Fix** Shader triggers
 - **Fix** Breaking apart text object

## v0.2.5-alpha
 - **Fix** Custom objects breaking
 - **Fix** Teleport objects breaking
 - **Fix** BetterEdit move and rotate shortcuts
 - **Fix** Speed objects not playing correctly

## v0.2.4-alpha
 - **Fix** Start pos objects duplicating
 - **Fix** Rotating being broken when used with BetterEdit

## v0.2.3-alpha
 - **Fix** Game opening before it was fully connected
 - **Fix** Failed connection error outside the join screen

## v0.2.2-alpha
 - **Fix** Scale X not tracking

## v0.2.1-alpha
 - **Release** Initial Early Access release
