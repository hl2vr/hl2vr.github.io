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

It is being developed by the SourceVR Mod Team, a group of VR enthusiasts.
More information is available on the [About](/about/) page.

<br />

### How can I download and install it?

It will be released on Steam, so that installation will work like any other game you own on Steam.
You will need to own the standard Half-Life 2 game on Steam (though it does not need to be installed; HL2VR will include everything you need).

If you meet that requirement, HL2VR itself is available free of charge!

You can now download and install it via [Steam](https://store.steampowered.com/app/658920/HalfLife_2_VR_Mod/)!

<br />

### Is the mod completely finished?

The current release of HL2VR (released September 16th, 2022) is a *public beta*. Some features are still missing or incomplete, and you may encounter bugs.
However, the game is playable from start to finish, and we do hope you will enjoy the journey!

For more details on the current state of the game and what we have planned for the future, please visit our [Roadmap](/roadmap).

<br />

### What headsets are supported?

HL2VR is targeting SteamVR, so any headset supported by SteamVR should be good to go.
So far, it has been successfully tested on Index, Quest, Vive, WMR, and Pimax headsets.

<br />

### Can it run standalone on the Quest?

No, a PC is required to play. You can of course use Oculus Link, AirLink, or Virtual Desktop to play it with your Quest over a wired or wifi connection.

While the Quest 2 hardware might be powerful enough to run Half-Life 2, there is no legally available Android port of the Source engine that would be required to make it run on the headset directly.

<br />

### Portal? L4D? TF2? CS?

Woah, woah! Let's take this one game at a time. We're focusing on Half-Life 2 and its Episodes right now.

Portal 1 is the only other Valve title that is a viable option right now for multiple reasons, and while we do hope to make it happen, it won't happen for quite some time.

<br />

### Can I support the SourceVR Mod Team?

HL2VR is, and always will be, free of charge. Even so, a lot of time has gone into its development. If you enjoy your virtual time in City 17 and want to say thank you, consider buying us a coffee:

[SourceVR Mod Team on Ko-Fi](https://ko-fi.com/sourcevrmodteam)

But please, only donate if you are happy with what we have already released and are financially able and willing to do so; do not treat it as a down-payment for any future development or the release of the Episodes!

Alternatively, we are always happy to just hear a few kind words of your experience. :)

<br />

---

# Game Features

---

### Will Episode 1 and 2 be supported?

Yes, but not at the initial release.

Right now, we are concentrating on the base game and are working hard to make it fully playable and *mostly* bug-free.
Once that's done, we will slowly move our attention to the Episodes and bring them to VR. These will be released as separate titles, similar to the standard Half-Life 2 and Episode 1/2 titles.

<br />

### World interaction

You can pick up, move, and interact with physics objects, props, weapons, health kits, etc.

An "immersive" ladder climbing mode is enabled by default, in which you can grab the ladder and pull yourself up or down.
A more standard stick-based climbing option is also available.

<br />

### Comfort options

A standard movement vignette is available.  
While moving, the borders of your screen will be blackened, reducing your field of view and reducing the impact of the motion sickness.

Snap-turning  
Artificial turning can be configured to be either smooth or in fixed intervals (snap turns).

Seated mode  
This mode fixes Gordon's in-game height to match the base game regardless of the player's headset position.

World scale  
Players uncomfortable with the standard world scale can adjust it to be larger or smaller.

<br />

### How does anyone stomach the vehicle sections?

The vehicle sections require strong VR legs. However, there are some additional comfort options available to help you survive them!

By default, the game uses a "fixed horizon" mode.  
This prevents your view from tilting left or right, which can help keep your view more stable even as the vehicle thrashes around.

The movement vignette is also available and can be activated for the vehicle rides.

A 3rd person camera perspective is available.  
In this mode, the camera follows the vehicle at a distance and is not directly subjected to the vehicle's rapid movements and turns, which should reduce motion sickness dramatically. (It does, however, make controlling the vehicles a little more awkward.)

In the future, we may implement an additional mode where the vehicle rides are put on a virtual 2D screen in front of the user, so that everyone has a chance to get through the vehicle sections in the game.
This mode would of course be less immersive than the current ones as it would remove any 3D effect from the experience.

<br />

---

# Weapons

---

### Manual reloading?

Yes, all weapons support manual reloading. Partially used magazines and other ejected ammo can be recovered and added back into your inventory.
A "quick reload" option has been added that simplifies the process, for players looking for an easier reloading option.

For more details, see the [Reloading section of the Manual](/manual/#reloading).

Manual reload for the crowbar has been disabled.

<br />

### Two-handed weapons?

Yes! Some weapons can (and should) be held two-handed to reduce recoil and spread. (For example, two-handing the SMG will significantly reduce recoil.)

Some weapons *require* two hands to use. (For example, the shotgun needs to be pumped in between shots.)

<br />

### I want to hit things with the crowbar?

Good news! You can!

However, props cannot be used as melee weapons (except when used with the Gravity Gun, as usual).

<br />

---

# Mod Support

---

### Will the Steam Workshop be supported?

Yes, but not at the initial release.

<br />

### Is HL2VR compatible with Black Mesa?

No. We agree that Black Mesa would be amazing in VR, but that would have to be a whole new project made by, or at least in collaboration with, the Black Mesa team.

<br />

### Is HL2VR compatible with other mods?

Yes, to a limited degree. In general, custom maps and campaigns as well as asset mods (like texture and model mods) are expected to work, although we cannot give any guarantees for any individual mod.
The HL2VR team also cannot provide any support for external mods.

Custom content (such as texture mods) can go in the */Half-Life 2 VR/hlvr/custom* directory.

Any mod that includes custom code or custom weapons, however, is incompatible and would require specific changes to be ported to HL2VR.
As a rule of thumb, if the mod includes its own custom DLLs, expect it to not work.

<br />

### Will you make the source code for HL2VR available?

That is our intention. HL2VR is based on the publically available Source SDK 2013 edition and can, in principle, be open sourced under the same license terms.

However, given the long development history of the project and the changes in the core team who worked on it over the years, we first need to do our due diligence to ensure that the source code is in a releasable state and that there are no technical and legal issues preventing it from being published.
While we do not expect any major issues, this process will require some time. The source code release will therefore happen after the initial public release of the mod, and there is currently no definitive timeline.

<br />

---

# Controls

---

### How do controls work in the game?

HL2VR will offer some in-game hints on the required actions and buttons you need to perform certain actions in the game.

For a comprehensive overview of the controls, check the [Manual](/manual/).

<br />

### What movement options are available?

HL2VR features smooth locomotion. The direction of motion can be configured to either follow your head or any of the two controllers. Turning can be configured to be
either smooth or in fixed intervals (snap turns).

There is currently no teleport movement available, and it is unclear if it will become a viable option in the future.  
We would like to include it, but it is very tricky to add to a game that was not designed for it. Implementing teleporting itself is difficult, but only part of the solution; the whole point is to get rid of artificial locomotion for the player, and that requires dealing with the vehicles, swimming, all the places where the player can experience pushback or slide down a slope, etc.

<br />

### Why did you put (this action) on (this button)?

Unfortunately, the amount of inputs provided by most VR controllers is limited, and we have a selection of actions that need to be mapped to the primary-hand controller. These include the weapon selection menu, primary and alt fire, eject magazine, as well as jump and crouch.
While some of these actions could, in theory, be bound to the left controller, doing so feels unintuitive or in some cases would be impossible to use properly.

As a consequence, we have no choice but to bind some of these actions to the up/down movement on the joystick. After some experimentation, it was found that neither the weapon selection menu nor alt-fire were a good candidate to place on the stick as the sticks have a higher accidental misfire probability. Putting jump on the stick is less harmful in most situations.
Additionally, it allows us to make the overall controls very similar to Half-Life: Alyx, which most of our players are probably familiar with.
It also means that both sticks are now fully devoted to controlling movement, with the right stick controlling turning, jumping, and crouching.

While it may take some getting used to initially, the vast majority of our playtesters have not had any issues with the controls.
If you still do not like the assignments, the controls are fully customizable via SteamVR controller bindings!

<br />

### Is left-handed mode supported?

Yes! You can configure the dominant hand, which determines the hand that is holding weapons.
It will also swap the control scheme accordingly, so (by default) movement is on the off-hand and turning is on the primary hand.

If you would like to hold your weapons in the left hand while still moving with the left stick, you will need to configure a custom SteamVR controller binding
(or use a preset that another community member has created and shared via SteamVR).
