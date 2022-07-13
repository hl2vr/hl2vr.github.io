---
permalink: /manual/
title: "Manual"
---

## Controls

The controls are fully customizable via SteamVR's controller bindings. Below we will
explain the default bindings, but you can always make your own modifications to suit
your needs.

HL2VR aims to support both right- and left-handed players. In the options menu on the
controls tab you can select which hand is your primary hand. The guide below will assume
that the right hand is the primary hand and the left hand the off hand. If you change the
primary hand, all controls will be swapped accordingly. For example, if you enable left-handed
mode, then you will hold weapons in your left hand and move with the right stick. If you still
want movement to be on the left stick, you will have to customize the SteamVR controller bindings.

![Index controllers](/assets/images/controls/Controls-Index.png)

![Touch controllers](/assets/images/controls/Controls-Oculus.png)

![Vive wands](/assets/images/controls/Controls-Vive.png)

![WMR controllers](/assets/images/controls/Controls-WMR.png)

#### Movement

The left (off-hand) stick controls your movement through the world. Press the stick in
to activate sprint; sprint will remain active until you fully let go of the stick again.
You can also freely move around in the real world. Your roomscale position will be reflected
in the game.

You can turn with the right (primary) stick. By default, snap turn is active with a 30°
turn amount. You can change the turn amount in the controls options - if you set it to 0,
you will get continuous turn.

Jump by pressing the right stick up. You can toggle crouch by pressing the right stick down.
You can also physically crouch in real life.

There is currently no teleport movement option available, although it might come in a future
update. For now, you can active a motion vignette in the comfort options if you need it.

#### World interactions

You can grab items in each hand by pressing the grip button (or squeezing the Index controllers).
Release grip to let go. Grabbable items will be highlighted in the world when you are close enough
to pick them up. By default, you need to pick up consumables like health or battery packs and weapons
to consume them. If you prefer the automatic pickup from the flat game, you can change this in
the controls options.

The trigger on each controller is your "Use" key. Use it to interact with buttons, levers, NPCs
and more. Your hand needs to be close to your interaction target.

You can press trigger on doors to open them automatically. Most doors can alternatively be grabbed
to open them manually. This feature is currently experimental and still a work in progress.

#### Ladders

By default, immersive ladder climbing is active. Grab the ladder by squeezing your grip buttons
to climb the ladder. When you are at the top, look towards where you want to dismount the ladder,
then let go of it.

If you prefer stick-based climbing of ladders (similar to the flat game), you can enable this in
the controls options.

#### Weapons

Press and hold the right stick (or right touchpad on Index controllers) to open the weapon selection menu.
The available weapons are shown in a hexagonal grid. Move your right hand towards the icon of the
weapon you want to equip, then let go of the right stick to close the menu. It may take some practice,
but the menu is designed so that you can quickly switch to your desired weapons blind! So allow yourself
some time to build the necessary muscle memory :)

Once equipped, aim the weapon with your primary hand. Pull the trigger to fire the weapon. To reload
weapons, first press the right A key to eject the magazine (if applicable), then press your off hand's
grip button near your shoulder to grab a fresh magazine. Bring the new magazine close to the weapon's
insert point, and the magazine will be loaded.

For the crowbar, you need to physically swing it to damage enemies or crates.

Some weapons have an alt-fire mode which is activated by pressing the right B key.

Some weapons can be held with both hands (SMG, pulse rifle, shotgun and crossbow). When the weapon
is equipped, move your off hand near the handle or grab point and press and hold the grip button to
hold onto the weapon with your secondary hand. Holding the weapon in both hands reduces recoil
significantly.

For the shotgun, you will have to pump it after every shot. To do so, you need to grip it with both hands,
then pull in your secondary hand towards your primary hand and release it again.

To throw grenades or bugbait, press and hold the trigger of your primary hand to arm the grenade.
Then make a physical throwing motion with your controller and let go of the trigger at the end
to throw the grenade.
It can be challenging to accurately aim the grenade throw. Since there are instances in the game where
you need absolute precision on your grenade throws to progress, there is an alternative throw mode
available when pressing the right B button. In this mode, you will be presented with a visual arc that
you can use to aim your throw. Release the B button to throw the grenade along the arc.

#### Flashlight

You can activate and deactivate your flashlight by pressing either hand's trigger near or in front of
your head.

#### Vehicles

To enter a vehicle, press either hand's trigger key (while not holding anything) near the vehicle.

You can accelerate and steer your vehicles with the left stick. Press the left stick in to activate
the jeep's boost.

If the vehicle is equipped with a weapon, use your primary hand to aim the weapon and press the trigger
to fire it. If available, you can activate alt fire via the right B button.

The right A button activates the jeep's handbrake. Pressing the right stick in activates the airboat's
headlights.

To exit the vehicle, press the left stick A or X button.


## Developer options

To enable the console, add `-console` to the launch options in Steam. This will bring up the console in
the game.

To enable the developer menu, add `-dev` to the launch options in Steam. This will enable a special
developer panel in the menu where you can jump to any map, give yourself any weapon and a number of
other options.

*Note*: enabling either of these options will prevent the main menu from showing in the headset! You
have to actually load into a level first before you will get anything to show in your HMD.