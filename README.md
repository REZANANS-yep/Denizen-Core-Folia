> ## ⚠️ Folia fork - EXPERIMENTAL, NOT FOR PRODUCTION
>
> This is an **unofficial fork** of [DenizenScript/Denizen-Core](https://github.com/DenizenScript/Denizen-Core) that
> adapts the engine for a **[Folia](https://github.com/PaperMC/Folia)** build of Denizen (Minecraft 1.21.11). Branch: `folia`.
> The only engine change is making the "main thread" check delegate to the implementation (so Folia's global region tick
> can act as the single logical engine thread). Pair with the matching Denizen Folia fork.
>
> **Do NOT use on a production server.** Experimental, work-in-progress, not endorsed by the DenizenScript team.

<p align="center">
  <a href="https://pterohost.com">
    <img src="https://pterohost.com/images/branding/logo-sm.webp" alt="Pterohost" height="64">
  </a>
</p>
<p align="center">
  <b>Этот форк развивается на <a href="https://pterohost.com">Pterohost</a></b><br>
  Игровой хостинг с поддержкой Folia, Paper и панелью YourControl.<br>
  <i>Developed on <a href="https://pterohost.com">Pterohost</a> - game server hosting with Folia/Paper support.</i>
</p>
<p align="center">
  <a href="https://discord.gg/BayzJzArBa"><img src="https://avatars.githubusercontent.com/u/93002293?s=280&v=4" alt="Discord" width="48" height="48"></a><br>
  <a href="https://discord.gg/BayzJzArBa">Discord-сервер Pterohost</a>
</p>

DenizenCore
===========

The core Denizen engine

To be implemented and extended by separate DenizenScript projects.

Please posts issues to the [Denizen Repo](https://github.com/DenizenScript/Denizen/issues).

For API usage, refer to the [Denizen README](https://github.com/DenizenScript/Denizen).

If you are implementing your own version of Denizen using this core, this topic is not yet fully documented, but talk to us on [Discord](https://discord.gg/Q6pZGSR).

### Licensing pre-note:

This is an open source project, provided entirely freely, for everyone to use and contribute to.

If you make any changes that could benefit the community as a whole, please contribute upstream.

### The short of the license is:

You can do basically whatever you want, except you may not hold any developer liable for what you do with the software.

### Previous License

Copyright (C) 2014-2019 The Denizen Script Team, All Rights Reserved.

### The long version of the license follows:

The MIT License (MIT)

Copyright (c) 2019-2026 The Denizen Script Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
