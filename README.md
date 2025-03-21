<p align="center">
	<a href="https://github.com/gitlab-ai/winlator-gold/">
	<img src="wg" width="376" height="128" alt="gitlab" />  
</p>
 
# Winlator Gold

Winlator Gold is an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64 Mesa Turnip driver DXVK.

# Installation Winlator Gold

1. Download and install Winlator Gold APK from [GitHub Releases](https://github.com/gitlabmyxa/winlator/releases)
2. Launch the app and wait for the installation process to finish


----

# Useful Tips Winlator Gold

- If you are experiencing performance issues, try changing the Box64 preset to `Performance` in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing `Wine Mono` found in Start Menu -> System Tools -> Installers.
- If some older games don't open, try adding the environment variable `MESA_EXTENSION_MAX_YEAR=2003` in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- To display low resolution games correctly, try to enabling the `Force Fullscreen` option in the shortcut settings.
- To improve stability in games that uses Unity Engine, try changing the Box64 preset to `Stability` or in the shortcut settings add the exec argument `-force-gfx-direct`.

# Information Winlator Gold

This project has been in constant development since version 1.0, the current app source code is up to version 7.1, I do not update this repository frequently precisely to avoid unofficial releases before the official releases of Winlator.

# Credits and Third-party apps
- GLIBC Patches by [Termux Pacman](https://github.com/termux-pacman/glibc-packages)
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- Mesa (Turnip/Zink/VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- PRoot ([proot-me.github.io](https://proot-me.github.io))

Many thanks to [ptitSeb](https://github.com/ptitSeb), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/), [Max Ivan](https://github.com/Maxython), [Twaik Yont](https://github.com/twaik), [alexvorxx](https://github.com/alexvorxx) and others.<br>
Thank you to all the people who believe in this project.
￼Enter
