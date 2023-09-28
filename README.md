
# Kinetic - The Best 1.12.2+ Tool

A **Minecraft Java 1.12.2+** Scanner that automates multiple processes in a screenshare.

*This resource is not open sourced, for more information, join the [discord](https://discord.com).*

⚠️ **Although however this can find most mods, clients, injections, etc, we do not recommend relying fully on this tool as it can't check for everything.** ⚠️

### **Type(s) of Detections and Features:**

- 🔍 **Generic Detection:** Implements Generic Detection and is able to find blatant mod clients.
- 🧵 **String Detection:** Implements String Detection to be able to find clients such as Meteor, Impact, etc.
- 🔏 **Private Detection:** Implements Private Detections to find traces of private clients and is constantly updated.
- 💉 **DLLInject Detection:** Implements DLLInject Detection to find DLL(s) that could be malicious.
- 🖱️ **Macro Detection:** Can find potential macros in known places where macros might be.
- 🔮 **Quick Dump:** Implements a quick and easy way to dump known strings in proccesses to an output file.
- 💵 **Free**: Our software is free to use and is used to catch hackers in screenshares.

## What does it screenshare for?
### Live Processes 🔴
Kinetic screenshares for multiple strings in live processes.

**Kinetic can screenshare for freely with *generic detection:***

| Services/Programs: | Info |
| - | - |
| **PcaSvc -** | ``[PcaClient, appcompact, PcaExtended, PcaWin11]`` |
| **DcomLaunch -** | ``[Doomsday]`` |
| **DPS -** | ``[ModifiedExt, .exeExec]``
| **Explorer -** | ``[Generic, DataStream]`` |
| **DiagTrack -** | ``[ModifiedExt]`` |
| **Java Instance -** | ``[Generic, Macro] `` |
| **Csrss -** | ``[DLL]`` |

### ``[Generic]`` 🌳
Generic detections are easily detected by Kinetic.

### Mod Analysis ⭐️
Kinetic uses Index Mod Analysis logic to look for mods that may be malicious.
- **Compares regular mods to malicious mods.**
- **Looks in strings for logic.**

### Macro Detection 🖱️
Kinetic uses ``[Generic]`` detection to look for macros.
- **Looks for all known macros that have been logged in public guides.**

**Kinetic does *NOT* look for on-board memory macros.**

### Known Strings 🧵
Kinetic is designed to catch most clients by looking for strings that relate to them.

*and more!*

## How to Download?
Join the Discord Server, create a pin, and download the latest release!
