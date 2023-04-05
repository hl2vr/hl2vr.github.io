---
permalink: /howto/
title: "How-To"
---

This page contains a few brief guides on how to accomplish things that aren't specific to HL2VR itself (such as changes to Steam or SteamVR settings).
Generally speaking, this means **the SourceVR Mod Team doesn't have control over how these things work.**
This is only meant to be helpful!

<br />

| Table of Contents  |
| ------------- |
| [Beta Branches](#beta-branches)  |
| [Re-Binding Controls in SteamVR](#re-binding-controls-in-steamvr)  |


<br />

---

# Beta Branches

---

Branches, also known as Betas, are specific builds of a Steam app that has been made available publicly or privately by the dev team.
To switch to a custom branch in the Steam client, right-click on the game from your Steam Library and select "Properties". Among the available tabs will be the "BETAS" tab.
On this tab, you'll find a dropdown menu with these available options under "Select the beta you would like to opt into":

(image here)

<br />

**None** - The default branch, intended for stable releases. Recommended for most users.

**testing** - Typically updated with new patches a day or two before public release to the default branch. Mostly intended for playtesters, and may not be stable.

**previous** - Rolls back to the previous public release. This shouldn't be useful for most users unless a new update introduces a game-breaking issue.

**3.0 (AKA "TNG")** - A beta branch with improved visuals, including updated lighting and upscaled textures.  
This branch is a *work in progress*, it is *not* considered a stable release, and there is currently no ETA for its completion. For this reason, it is passworded to prevent accidental usage. The password is: *bleedingedge2*

<br />

---

# Re-Binding Controls in SteamVR

---

Editing controls for HL2VR is done via SteamVR's built-in Controller Bindings menu. With the game running, open the SteamVR overlay and select "controller bindings", then select Half-Life 2: VR Mod.

(image: bindings-edit)

<br />

### Official presets

HL2VR offers two default control presets. The only difference between them is how vehicles control.

(image: bindings-official)

The default preset uses your movement hand (off-hand) stick to control vehicle acceleration, braking, and steering.
Vehicle weapon fire is bound to primary-hand Trigger.

The other preset changes vehicle acceleration and braking to primary-hand Trigger and off-hand Trigger (respectively).
Vehicle weapon fire is bound to primary-hand "B".  
See also: (accel/brake section link)

<br />

### Personalized changes

If none of the Official or Community bindings presets work for you, you can edit the SteamVR controller bindings to adjust controls to your liking.

(image: bindings-personalize)

Details on how to use SteamVR Controller Bindings is outside the scope of this page, but if you're unfamiliar with it you can find plenty of help through Google or the Steam community.

<br />

### Vehicle Acceleration/Brake

Keep in mind that binding *either* Accelerate or Brake vehicle options will un-bind *both* from your movement stick up/down.
So you'll need to assign Accelerate *and* Brake options.

(image: bindings-accelerate)

Left-handed players: SteamVR is not aware of the in-game changes that swap your primary hand from right to left hand. 
Thus, if you want to put Accelerate on your right hand trigger, you'll need to assign it to the *left* hand trigger in SteamVR.
