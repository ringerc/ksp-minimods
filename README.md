# Micro-mods for Kerbal Space Program (KSP)

You can just copy these directories or the raw .cfg files into your `GameData`
directory to use them.

To use these mods you must have [`ModuleManager`] installed. There must be a
ModuleManager dll in your game data directory. It's bundled with most if not all
mods, so you should have it. If not, get it from
[here](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-141-module-manager-307-may-5th-2018-its-dangerous-to-go-alone-take-those-cats-with-you/).

If you edit the config files or add/remove some, you can reload them without
restarting KSP. Go to the space center and press Alt-F11 (RShift-F11 on Linux),
then choose "Reload database" from he resulting menu. Wait until the reload
completes before doing anything.

## HeatShields

KSP's heat shields are magic - even a heat shield with 0 ablator is almost
always sufficient to protect a pod because it acts as a near perfect insulator and
has an insanely high max temperature.

These tweaked heat shield parts burn ablator faster, and more importantly they
will fail and explode if you come in too steep and fast. A zero ablator shield
won't protect you from much anymore.

You will have best results with ballistic re-entry. Re-enter too shallow and
too much shield burns up. Re-enter too steep and your shield overheats and
fails. Maybe it cracked?

The patch does not yet tweak the heat shields on the new Making History bubble
pods. Nor does it remove the magic from the inflatible heat shield yet - 

I still suspect the root cause of the magic power of heat shields is a bug with
heat shield conductivity.
