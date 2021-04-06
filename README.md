#
<h1 align="center">Wolveric's YAGPDB Custom Commands</h1>

## Implementing Custom Commands
All scripts found within this repository, are published with the understanding, that users of these scripts will have some experience of how to create, configure and use a Custom Command, within YAGPDB.
This repository will be structured as such, that it will be separated into folders of related or similar commands, with an accompanying `README.md` document, detailing the general contents of the folder, and their use cases. Most folders will group standalone commands with similar use areas, but can all be implemented and used separately, without issue.
Any folders of commands that work as a system, will be clearly marked as such in their dedicated `README.md` document, and will require users to implement and configure *all* scripts, unless specified otherwise on a per-script basis.

Each individual command file will have a feature a heading comment, describing the scripts function, and the intent of use behind its design, as well as a recommended trigger type and trigger. This is included to inform how it should be set up in YAGPDBs control panel.

## Current Contents
+ [Utilities](https://github.com/Wolveric/YAGPDB-Scripts/tree/master/Utilities)
  + Looking For Game
  + Add Reactions
+ [Moderation](https://github.com/Wolveric/YAGPDB-Scripts/tree/master/Moderation)
  + Relocate
  + Custom Role Command Controls
+ [Script Snippets](https://www.example.com)
  + Flag Handling Manual Arg Parser
  + Index Suffix Extractor
  + Safe Prefix-RegEx Extractor

## Disclaimers
+ All scripts in this repository are provided as found, in a manner by which they are not to cause offense of any kind.
The YAGPDB's creator, staff, support and/or myself, are not responsible for any difficulties caused by the implementation and/or use of these scripts.
+ All scripts in this repository, are provided, and are typically intended to be used, as found, published in a state I (Wolveric Catkin) have considered appropriate to designate as "functional".
These commands are not guaranteed to be entirely free of faults, and may be detailed as in cases where this applies.
+ In the case where faults cannot be attributed to misunderstanding in use or configuration, contribution to correct these faults is appreciated.
+ In alternating a script beyond intended parameters of configuration, in a manner where it can no longer be reasonably correlated with the base design, it is to be understood responsibility for troubleshooting any resulting conflicts with the base configuration, now predominantly fall upon the party having made such alterations, as it will have become divergent enough to be understood as the user's own design.

## Need help?
If you are having difficulties with one of the custom commands here, I am regularly available for enquiries on the [YAGPDB Support Server](https://discord.gg/5uVyq2E). You can find me as `Wolveric#0897`, though I generally prefer not to be DMed directly.
