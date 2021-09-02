[![Netlify Status](https://api.netlify.com/api/v1/badges/a4c6e2f6-5ff3-4349-8a24-f2988af83487/deploy-status)](https://app.netlify.com/sites/kexquake/deploys)

---

# Quake 2021 Remaster (Kex Quake) Mod Server

**Table of Contents**

- [Quick Setup](#quick-setup)
  - [Testing Branch](#testing-branch)
- [Troubleshooting](#troubleshooting)
  - [Opening the addon menu crashes the game](#troubleshooting)
  - [Activating mod crashes the game](#troubleshooting)
  - [I'm experiencing a technical problem with a mod](#troubleshooting)
- [Credit](#credit)

## Quick Setup

Append `+ui_addonsBaseURL http://kexquake.netlify.app/` to your Quake [launch options].

### Testing Branch
If you wish to test additional mods in various stages of compatibility:

Append `+ui_addonsBaseURL http://kexquake.netlify.app/beta/` to your Quake [launch options].

Submit an issue if you discover a mod is now fully functional after a game update.

## Troubleshooting

### Opening the addon menu crashes the game
The `content.json` file on the server is probably incorrectly formatted, let someone know.
### Activating a mod crashes the game
Your download was either corrupted or the download server is currently down. Delete it and try downloading it again.
### I'm experiencing a technical problem with a mod
Post an issue on how to replicate the problem and we'll take a look at it.

## Credit

[Tyler McVicker](https://twitter.com/tyler_mcv): For originally bringing this to my attention.

[u/jpiolho](https://libredd.it/r/quake/comments/p8dfe8/adding_mods_to_the_new_addons_tab/): For their reddit thread on the topic.

[RamblingMadMan](https://github.com/RamblingMadMan/q1mods): For their github and example implementation.

[launch options]: https://help.steampowered.com/en/faqs/view/7D01-D2DD-D75E-2955
