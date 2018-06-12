# Micro-mods for Kerbal Space Program (KSP)

A collection of ModuleManager-only patches I wrote for KSP.
Like those in [the forum thread](https://forum.kerbalspaceprogram.com/index.php?/topic/139980-130-community-database-of-module-manager-patches-for-stock-ksp/),
but I can't stand working without revision control.

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

These tweaked heat shield parts burn ablator a little faster, and more
importantly they will fail and explode if you come in too steep and fast. A
zero ablator shield won't protect you anywhere near as much anymore.

It's recommended that you play with atmospheric heating at 120%.

You will have best results with ballistic re-entry. Re-enter too shallow and
too much shield burns up. Re-enter too steep and your shield overheats and
fails. (Maybe it cracked?)

Ideally the heat shield's maxTemp would get lowered when the ablator ran out,
but this doesn't seem possible in a mod.

Inflatible shields are now somewhat destructible - don't expect to come in to
Eve at 5km/s with periapse 80km with 100 tons of rocket stack behind an
inflatible shield and survive. It's good for skimming, especially lifting
aerocaptures, but it won't let you slam into the atmosphere anymore. (Further
work there may be to add a dynamic pressure limit).

Pods have a small amount of optional ablative coating now, to help protect the
sides/edges if they come in off-bore, and so your low tech pods can still do
low orbit work without being incinerated. Probably.

Heat shields can be made thicker than stock, but by default are now half stock
thickness, which is sensible for most things other then Eve/Jool.
