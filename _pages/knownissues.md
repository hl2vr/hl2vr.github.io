---
permalink: /knownissues/
title: "Known Issues (and some solutions)"
---

<br />

| Table of Contents  |
| ------------- |
| [Step 1](#step-1-for-every-issue)  |
| [Downloading or Installing issues](#downloading--installing-issues  )  |
| [Launching or crash issues](#launching-or-immediate-crash-issues)  |
| [Less common issues](#less-common-issues)   |

<br />

Hi all,

We are aware of several different bugs (or non-bug *reasons*) some users are having trouble installing the game via Steam, or the game not launching once installed. If you are one of those users, please see the following list for the current status and/or any recommendations.

<br />

### **Not all of these issues have solutions or workarounds yet.**  
We will keep this updated as we learn more.

<br />

### This is intentionally an incomplete list.  
It's being updated over time, and only covers the biggest *game-breaking* issues we've come across.
It does not include smaller bugs or feedback on the game. (Please see [the Help page](help/#reporting-bugs) and bug tracker for those!)

<br />

---

# Step 1 for every issue

---

I know nobody likes to hear just turn it off and on again, but you're going to turn it off and on again and you're going to like it!

Please try the basics, listed below, before anything else. We've seen these solve problems for half the users who report issues.

- Update Windows, Steam, and SteamVR to the latest versions.  
Avoid using any branches for SteamVR other than the public stable release or the most recent beta.

- Update your graphics drivers.  
Don't skip this step! I know you're thinking *I'm just gonna skip this step because I know all about my updates already* but that would be a mistake!

- Close Steam and SteamVR, and reboot your device.

<br />

<br />

---

# Downloading / Installing issues

---

### Unable to claim or download the game in the Steam Store

This is often caused by the user not owning the standard Half-Life 2 on Steam. Having access to HL2 via Steam Family Sharing is not enough -- your account needs to own HL2.

We've also seen cases where it takes a bit of time after purchasing Half-Life 2 for Steam to notice that you should now be allowed to grab HL2VR. So if you've *just now* bought it, please give it a bit of time and try again later.

<br />

<br />

---

# Launching or immediate crash issues

---

### A small window pops up for a moment, closes, then nothing happens

Known issue. Details on solution/workaround coming soon.

In the meantime, if you have **OculusKiller** (or any similar app) running, HL2VR will not launch correctly.
A fix for this is being tested now and will be deployed in an upcoming update.

<br />

### Game launches on the desktop, but doesn't display in the VR headset

###### Bad launch parameters
The most common cause we see for this issue is launching the game with *-dev* or *-console* parameters.
We recommend not using these; when enabled, the game will not display in the headset until a level is loaded.

If you need cheat or console access, use the launch parameter *-vrdev* instead.

###### Other causes

We're aware this can happen even with no launch parameters specified. The cause is unknown.

<br />

### Game crashes immediately upon launch

We're investigating what appears to be several different causes for this behavior.

- Some users are able to resolve this issue by simply ensuring their Windows installation and GPU drivers are completely up to date.

<br />

### Game reports "waiting to exit", then hangs or closes

This appears to be limited to users with mobile or integrated graphics.

- Some laptop users report disabling and re-enabling the AMD Radeon integrated graphics in the Windows Device Manager resolves the issue.

- Some laptop users have had success by setting hl2.exe to "High Performance" and forcing the game to use their GPU.  
Details on how to do that here: [Link](https://www.windowsdigitals.com/force-chrome-firefox-game-to-use-nvidia-gpu-integrated-graphics/)

<br />

### ...Some other issue!

We'll be adding more info over time.

<br />

<br />

---

# Less common issues

---

### Getting error: "Setup file 'gameinfo.txt' doesn't exist in subdirectory 'hl2'."

Somehow your Windows install has been modified so the default action for Batch files is Edit instead of Open. For now, simply open the hlvr.bat file *(in the [your Steam directory]/Half-Life 2 VR/ folder)* with Right Click and selecting Open.

A change that can bypass this issue will be included in a future update.
