---
permalink: /faq/
title: "FAQ"
---

<br />

| Table of Contents  |
| ------------- |
| [About](#about-half-life-2-vr-mod)  |
| [Game Features](#game-features)  | 
| [Weapons](#weapons)  |
| [Mod Support](#mod-support)  |
| [Controls](#controls)  | 

<br />

---

# About Half-Life 2: VR Mod

---

### Who is developing HL2VR?

It is being developed by the Source VR Mod Team, a group of VR enthusiasts.
More information is available on the [About](/about/) page.

<br />

### How can I download and install HL2VR?

It will be released on Steam, so that installation will work like any other
game you own on Steam. You will need to own the base Half-Life 2 game on Steam
(though it does not need to be installed).

You can now wishlist it on [Steam](https://store.steampowered.com/app/658920/HalfLife_2_VR_Mod/)!

<br />

### How much will HL2VR cost, and when will it be available?

It will be available free of charge to all owners of Half-Life 2 on Steam.

HL2VR is currently undergoing a closed playtest.
The public beta release is scheduled for September 16th, 2022.

<br />

### What headsets are supported?

HL2VR is targeting SteamVR, so any headset supported by SteamVR should be good to go.
So far, it has been successfully tested on Index, Quest, Vive, WMR, and Pimax headsets.

<br />

### Can it run standalone on the Quest?

No, a PC is required to play. You can of course use Oculus Link, AirLink, or
Virtual Desktop to play it with your Quest over a wired or wifi connection.

While the Quest 2 hardware might be powerful enough to run Half-Life 2, there
is no legally available Android port of the Source engine available that would be required
to make it run on the headset directly.

<br />

### Portal? L4D? TF2? CS?

Woah, woah! Let's take this one game at a time. (Portal 1 is the only other Valve
title that is a viable option, for multiple reasons, and it won't happen for quite some time.)

<br />

---

# Game Features

---

### Will Episode 1 and 2 be supported?

Yes, but not at the initial release.

Right now, we are concentrating on the base game and are working hard to
make it fully playable and get its public release out of the door. Once that's
done (and the first inevitable influx of bug reports have been processed), we will
slowly move our attention to the Episodes and bring them to VR.

<br />

### How will you handle the vehicle sections? I don't think I can stomach them in VR.

The vehicle rides do indeed require strong VR legs. However, there are some
comfort options available to help you survive them. By default, the game enables a
"fixed horizon" mode that helps keep your view more stable even as the vehicle thrashes around.

A classic movement vignette is also available and can be activated for the vehicle rides.
While riding the vehicles, the borders of your screen will be blackened,
reducing your field of view and reducing the impact of the motion sickness.

Additionally, you can choose to experience the vehicle rides from a 3rd person camera perspective.
In this mode, the camera follows the vehicle at a distance and is not directly subjected to
the vehicle's rapid movements and turns, which should reduce motion sickness dramatically.
It does, however, make controlling the vehicles a little more awkward.

In the future, we may implement an additional mode where the vehicle rides are put
on a virtual 2D screen in front of the user, so that everyone has a chance to get through
the vehicle sections in the game. This mode would of course be less immersive than the
current ones as it'd remove any 3D effect from the experience.

<br />

---

# Weapons

---

### Manual reloading??

Yes. All weapons support manual reloading. Partially used magazines and other ejected ammo
can be recovered and added back into your inventory.

Manual reload for the crowbar has been disabled.

<br />

### Two-handed weapons?

Yes! Some weapons can be held two-handed to reduce recoil and spread.

Some weapons require two hands to use. (For example, the shotgun needs to be pumped
in between shots.)

<br />

### I want to hit things with the crowbar?

Good news! You can!

<br />

---

# Mod Support

---

### Will the Steam Workshop be supported?

Yes, but not at the initial release.

<br />

### Is HL2VR compatible with Black Mesa?

No. We agree that Black Mesa would be epic in VR, but that would have to be a whole new
project made by, or at least in collaboration with, the Black Mesa team.

<br />

### Is HL2VR compatible with other mods?

Yes, to a limited degree. In general, custom maps and campaigns as well as asset mods (like
texture and model mods) are expected to work, although we cannot give any guarantees for
any individual mod.
Any mod that includes custom code or custom weapons, however, is incompatible and would
require specific changes to be ported to HL2VR.

As a rule of thumb, if the mod includes its own custom DLLs, expect it to not work.

<br />

### Will you make the source code for HL2VR available?

That is our intention. HL2VR is based on the publically available Source SDK 2013
edition and can, in principle, be open sourced under the same license terms.

However, given the long development history of the project and the changes in the core team
who worked on it over the years, we first need to do our due diligence to ensure that
the source code is in a releasable state and that there are no technical and legal issues
preventing it from being published. While we do not expect any major issues, this process
will require some time. The source code release will therefore happen after the initial
public release of the mod, and there is currently no definitive timeline.

<br />

---

# Controls

---

### How do controls work in the game?

The game will offer some hints on the required actions and buttons you need to perform certain
actions in the game.
For a comprehensive overview of the controls, check the [Manual](/manual/).

<br />

### What movement options are available?

HL2VR features smooth locomotion. The direction of motion can be configured to
either follow your head or any of the two controllers. Turning can be configured to be
either smooth or in fixed intervals (snap turns).

There is currently no teleport movement available, and it is unclear if it will
become a viable option in the future.

<br />

### Why did you put (this action) on (this button)?

Unfortunately, the amount of inputs provided by most VR controllers is limited, and we have a
selection of actions that need to be mapped to the primary-hand controller. These include
the weapon selection menu, primary and alt fire, eject magazine, as well as jump and crouch.
While some of these actions could, in theory, be bound to the left controller, doing so feels
unintuitive or in some cases would be impossible to use properly.

As a consequence, we have no choice but to bind some of these actions to the up/down movement
on the joystick. After some experimentation, it was found that neither the weapon selection menu
nor alt fire were a good candidate to place on the stick as the sticks have a higher accidental
misfire probability. Putting jump on the stick is less harmful in most situations. Additionally,
it allows us to make the overall controls very similar to Half-Life: Alyx, which most of our
players are probably familiar with. It also means that both sticks are now fully devoted
to controlling movement, with the right stick controlling turning, jumping, and crouching.

While it may take some getting used to initially, the vast majority of our playtesters have not
had any issues with the controls. If you still do not like the assignments, the controls are
fully customizable via SteamVR controller bindings!

<br />

### Is left-handed mode supported?

Yes! You can configure the dominant hand, which determines the hand that is holding
weapons. It will also swap the control scheme accordingly, so (by default) movement
is on the off-hand and turning is on the primary hand.

If you would like to hold your weapons in the left hand while still moving with the left stick,
you will need to configure a custom SteamVR controller binding.
