**This repository will be deleted soon! The Steamless.NET project is now maintained under the name 'Steamless' here:<br/> https://gitlab.com/atom0s/Steamless**

**Please use the other repo for all future issues/pull requests etc.**

**For more information about this, see:** http://atom0s.com/forums/viewtopic.php?f=2&t=97




<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

















# Steamless
Steamless is a DRM remover of the SteamStub variants. This version of Steamless is written in .NET (C#).

The goal of Steamless is to make a single solution for unpacking all Steam DRM packed files. *Steamless aims to support as many games as possible however, due to my personal limited collection of games I cannot test every scenario personally.*

# Supported Versions

- **SteamStub Variant 1**
  - Currently this version is not supported yet.  
- **SteamStub Variant 2**
  - Support for this version is at: 100% (see below notes)
    - x64 binaries are not supported.
    - Overlays are not currently restored.
    - Some files with specific features (flags) set may not unpack properly.
- **SteamStub Variant 3**
  - Support for this version is at: 100% (see below notes)
    - x64 binaries are not supported.
    - Overlays are not currently restored.
    - Some files with specific features (flags) set may not unpack properly.

# What is SteamDRM / SteamStub?
<blockquote>
DRM
<br><br>
Steamworks Digital Rights Management wraps your game's compiled executable and checks to make sure that it is running under an authenticated instance of Steam. This DRM solution is the same as the one used to protect games like Half-Life 2 and Counter-Strike: Source. Steamworks DRM has been heavily road-tested and is customer-friendly.
<br><br>
In addition to DRM solutions, Steamworks also offers protection for game through day one release by shipping encrypted media to stores worldwide. There's no worry that your game will leak early from the manufacturing path, because your game stays encrypted until the moment you decide to release it. This protection can be added to your game simply by handing us finished bits or a gold master.
<br><br>
ref: hxxps://partner.steamgames.com/documentation/api
</blockquote>

# Legal
I, atom0s, am not responsible for what you do with this source code. I do not condone piracy and wish that if you choose to remove the DRM of a Steam game, do so with a game that you already own. Use this code at your own risk!

Steamless is released for educational purposes in the sense to understand and learn about DRM protection. Steamless does not make it possible to play online games for free that are from Steam. Steamless does not remove the usage of steam_api.dll from any game that makes use of it. Do not contact me asking for help with obtaining games or other content from Steam for free.

# Credits and Thanks
Thanks to Cyanic (aka Golem_x86) for his notes and help with parts of the stub headers and such. You can find his information here:
http://pcgamingwiki.com/wiki/User:Cyanic/Steam_DRM
