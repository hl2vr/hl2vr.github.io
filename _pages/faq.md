---
permalink: /faq/
title: "FAQ"
---

*Who is developing Half-Life 2: VR?*

The mod is being developed by the Source VR Mod Team, a group of VR enthusiasts.
See also [About](/about/).

---

*How much will it cost?*

The mod will be available free of charge. You do need to own the base game Half-Life 2
on Steam.

---

*When will it be available?*

"Soon". The mod is currently undergoing a closed playtest. We are targeting a 2022
public release, fingers crossed!

---

*What headsets are supported?*

The mod is targeting SteamVR, so any headset supported by SteamVR should be good to go.
So far, the mod has been successfully tested on Index, Quest, Vive and Pimax headsets.

---

*What movement options are available?*

The mod features smooth locomotion, where the direction of motion can be configured to
either follow your head or any of the two controllers. Turning can be configured to be
either smooth or in fixed intervals (snap turns).

There is currently no teleport movement available, and it is unclear if it will
become a viable option in the future.

---

*Is left-handed mode supported?*

Yes! You can configure the dominant hand, which determines the hand that is holding
weapons. It will also swap the control scheme accordingly, so that by default movement
is on the off hand whereas turning is on the primary hand. If you would like to hold
your weapons in the left hand while still moving with the left stick, you will have the
option to configure a custom SteamVR controller binding to make that happen.

---

*How will you handle the vehicle sections? I don't think I can stomach them in VR.*

Right now, the vehicle rides do indeed require strong VR legs. However, there are some
comfort options available to help you survive them. A classic movement vignette is
available and can be activated for the vehicle rides. While riding the vehicles, the
borders of your screen will be blackened, reducing your field of view and reducing the
impact of the motion sickness. Additionally, you can choose to experience the vehicle
rides from a 3rd person camera perspective. In this mode, the camera is following the
vehicle at a distance and is not directly subjected to the vehicle's rapid movements
and turns, which should reduce motion sickness dramatically. It does, however, make
controlling the vehicles a little more awkward.

In the future, we may implement an additional mode where the vehicle rides are put
on a virtual 2D screen in front of the user, so that everyone has a chance to get through
the vehicle sections in the game. This mode would of course be less immersive than the
current ones as it'd remove any 3D effect from the experience.

---

*Will Episode 1 and 2 be playable in VR?*

Eventually yes. Right now, we are concentrating on the base game and are working hard to
make it fully playable and get an initial public release out of the door. Once that's
happened and the first inevitable influx of bug reports have been processed, we will
slowly move our attention to the episodes and bring them to VR.

---

*Will you make the source code for the mod available?*

That is our intention. The VR mod is based on the publically available Source SDK 2013
edition and can, in principle, be open sourced under the same license terms.

However, given the long development history of the mod and the changes in the core team
who worked on it over the years, we first need to do our due diligence to ensure that
the source code is in a releasable state and that there are no technical and legal issues
preventing it from being published. While we do not expect any major issues, this process
will require some time. The source code release will therefore happen after the initial
public release of the mod, and there is currently no definitive timeline.

---

*Is Half-Life 2: VR compatible with other mods?*

To a limited degree. In general, custom maps and campaigns as well as asset mods like
texture and model mods are expected to work, although we cannot give any guarantees for
any individual mod. Any mod that includes custom code or custom weapons, however, is
incompatible and would require to be ported to the VR mod, specifically. In general, if
the mod includes its own custom DLLs, expect it to not work.

---

*How can we download and install Half-Life 2: VR?*

Our goal is to bring the VR mod to Steam, so that installation would work like any other
game you own on Steam. You will need to possess the base Half-Life 2 game on Steam and can
then simply add the VR mod to your library and download it.

However, the initial public beta release may not make it into Steam. If that should be the
case, we will offer an installer that you can download and that will take care of installing
Half-Life 2: VR. You will need to have the base Half-Life 2 game installed on your PC for the
installer to work.

---

*How do controls work in the game?*

The game will offer some hints on the required actions and buttons you need to perform certain
actions in the game. For a comprehensive overview of the controls, check the [Manual](/manual/).

---

*Why did you put 'Jump' on 'Right stick up'? That seems unintuitive.*

Unfortunately, the amount of inputs provided by most VR controllers is limited, and we have a
selection of actions that need to be mapped to the right (primary) controller. These include
the weapon selection menu, alt fire, eject magazine as well as jump and crouch. While these
actions could, in theory, be bound to the left controller, as well, doing so would feel
unintuitive or even be impossible to use properly.

As a consequence, we have no choice but to bind some of these actions to the up/down movement
on the joystick. After some experimentation, it was found that neither the weapon selection menu
nor alt fire were a good candidate to place on the stick as the sticks have a higher accidental
misfire probability. Putting jump on the stick is less harmful in most situations. Additionally,
it allows us to make the overall controls very similar to Half-Life: Alyx, which most of our
players are probably familiar with. And it also means that both sticks are now fully devoted
to controlling movement, with the right stick controlling turning, jumping and crouching.

While it may take some getting used to initially, the vast majority of our playtesters have not
had any issues with the controls. If you still do not like the assignment, the controls are
fully customizable via SteamVR controller bindings :)
