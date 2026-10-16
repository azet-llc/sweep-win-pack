# sweep-win-pack

Packaging runner for the Sweep for Windows installer (AZET LLC). It takes signed `sweepd.exe` and `Sweep.exe` from a
draft release, compiles the Inno Setup installer on a Windows runner, and runs the end-to-end check (install, system-wide
blocking, fault injection, repair, DNS restore, uninstall). The installer itself is signed afterwards with AZET LLC's
Microsoft Artifact Signing certificate and checked again here.

Product page: https://azet.io/products/sweep
