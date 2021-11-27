<h1 align="center">
 Linux For Beginners
</h1>

<h2 align="center">
For people looking to join linux. This is not a spoonfeeding repository.
</h2> 

# Quick Links
  [Reasons not to use Microsoft #](https://stallman.org/microsoft.html)
  
  [Reasons not to use Apple #](https://stallman.org/apple.html)
  
  [Reasons not to use Google #](https://stallman.org/google.html)
  
  [Distros #](https://fernbacher.github.io/linux-for-begginers/#distros)
  
  [Custom Kernel #](https://fernbacher.github.io/linux-for-begginers/#custom-kernel)
 
  [Software #](https://fernbacher.github.io/linux-for-begginers/#software)
  
  [Useful #](https://fernbacher.github.io/linux-for-begginers/#useful)
  
  [Pacman Commands #](https://fernbacher.github.io/linux-for-begginers/#pacman-commands)
  
  [Most Common Questions #](https://fernbacher.github.io/linux-for-begginers/#most-common-questions)
  
  
 
# Distros

1. [Manjaro](https://manjaro.org/)
- I recommend KDE/XFCE from the official editions.

2. [Pop-OS](https://pop.system76.com/)
- Nvidia version if you have NVIDIA GPU, obviously. Otherwise the normal one.

3. [Linux Mint](https://linuxmint.com/)
- Most Windows-Like experience you can have, recommend it the most for new users that just want simplicity and to get rid of Windows.

5. [Archcraft](https://archcraft.io/)
- Archcraft is just another Linux distribution, made on top of Arch Linux, beautifully configured it will automatically give you the r/unixporn dream desktop you kept seeing on reddit.

5. [Arch-Linux-GUI](https://archlinuxgui.in/)
- There are multiple DE versions, aswell as 2 WM versions. If you want to use your keyboard alot more and not focus on GUI anymore, go for WM, also alot slimmer on resourcers.

6. [Debian](https://www.debian.org/)
- Usually used for servers, it uses LTS (long term support) kernel, the base of ubuntu and many many others.

7. [Devuan](https://www.devuan.org/)
- Debian without system-d [read about why system-d could be bloat for you](https://ebin.city/~werwolf/posts/systemd-sucks/).

8. [Artix](https://artixlinux.org/)
- Arch without system-d. [read about why system-d could be bloat for you, again](https://ebin.city/~werwolf/posts/systemd-sucks/).

9. [Arch](https://archlinux.org/)
- A simple, lightweight distribution

# Custom Kernel

1. [Linux-Zen](https://github.com/zen-kernel/zen-kernel)
- Result of a collaborative effort of kernel hackers to provide the best Linux kernel possible for everyday systems. Some more details can be found on [Liquorix](https://liquorix.net).

2. [XanMod](https://xanmod.org)
- XanMod is a general-purpose Linux kernel distribution with custom settings and new features. Built to provide a stable, responsive and smooth desktop experience.

3. [Configure Your Own](https://youtu.be/NVWVHiLx1sU)
- Kinda outdated, but its a decent base to see what you can do and how hard/easy it is.

4. [Clear-Linux](https://aur.archlinux.org/packages/linux-clear/)
- The Clear Linux kernel and modules, from the AUR.

# Software

1. [NoiseTorch](https://github.com/lawl/NoiseTorch)
- This is the first thing you should consider getting on Linux if you use a normal mic or a headset mic, removes every background noise possible, some microphones can suffer a degrading quality if not set up right.

2. [Lutris](https://lutris.net/)
- Open source platform for gaming on linux, easy to download and install games from any platform with the help of the community installers / scripts.

3. [Wine](https://www.winehq.org/)
- Compatibility layer for running Windows applications and even games on Linux.

4. [Proton-GE](https://github.com/GloriousEggroll/proton-ge-custom)
- Custom build of Valve's proton, multiple patches and fixes for steam games using proton.

5. [Spotify-TUI](https://github.com/Rigellute/spotify-tui)
- A spotify client in the terminal written in Rust.** **FOR PREMIUM ACCOUNTS ONLY**

6. [Spicetify-CLI](https://github.com/khanhas/spicetify-cli)
- Command-line tool to customize the official Spotify client.

# Useful

1. [yay](https://github.com/Jguer/yay)
- An AUR Helper written in Go. [What is AUR?](https://wiki.archlinux.org/title/Arch_User_Repository)

2. [Arch-Wiki](https://wiki.archlinux.org/)
- The official Arch Linux documentation webpage.

3. [Linux From Scratch](https://www.linuxfromscratch.org/)
- Linux From Scratch (LFS) is a project that provides you with step-by-step instructions for building your own custom Linux system, entirely from source code.

4. [Brave, the false sensation of privacy](https://ebin.city/~werwolf/posts/brave-is-shit/)
- Why Brave is not what you may think it is.

5. [Firefox Profile Maker](https://ffprofile.com)
- Tool to create your own profile for fireox to import.

6. [Ratpoison: Kill the rat](https://ebin.city/~werwolf/posts/ratpoison/)
- [Ratpoison](http://ratpoison.nongnu.org/) is a simple Window Manager with no fat library dependencies, no fancy graphics, no window decorations, and no rodent dependence, the first link has more helpful information in it.

7. [Polybar-MPV](https://github.com/randomdude8/polybar-mpv)
- Display current playing file and scrolls the text with [zscroll](https://github.com/noctuid/zscroll), cycle pause and volume control, simple to edit and easily expandable. Made by an old friend.

8. [Gamepads/Controllers](https://aur.archlinux.org/packages/xboxdrv/)
- Use any USB Gamepad that you would normally use in windows, to use a PS3/PS4 controller, run this command in the terminal `sudo xboxdrv --detach-kernel-driver`.

9. [Chaotic AUR](https://aur.chaotic.cx/)
- Automated building repository for AUR packages.

10. [Wine-TKG](https://github.com/Frogging-Family/wine-tkg-git)
- Wine-tkg is a build-system aiming at easier custom wine builds creation. You can now easily get the "plain wine + pba + steam fix" build. (Can be installed from Chaotic-AUR)

11. [Dusk](https://github.com/bakkeby/dusk)
- Just another fork of dwm. (Personally use it)

12. [LARBS](https://larbs.xyz/)
- LARBS is an efficient shell script that will install a fully-featured tiling window manager-based system on any Arch or Artix Linux-based system, without any of the routine of manual post-install processes and configuration.

# Pacman Commands

- Remove unused packages and their configuration files: `pacman -Qtdq | pacman -Rns -`

- Upgrade packages: `pacman -Syu`

- Downgrade packages: `pacman -Suu`

- Unlock / add extra, testing and more package repositories: `nano /etc/pacman.conf` / `vim /etc/pacman.conf`

# Most Common Questions

1. Do I Need To Use The Terminal In Linux?
- Short answer, Yes.
- Basic answer; You don't have to use it, but you should learn how to use it to an extent, it is about your full control over your Operating System, GUI applications can cover up terminal usage, but its not unlimited. Slowly but surely you should learn how to use the terminal for basic usage and even advanced.

2. What is [GNU](https://www.gnu.org/gnu/linux-and-gnu.en.html)/[Linux](https://www.linux.com/what-is-linux/), and why should/would i use it?
- Click for information.

3. How can i manually partition with calamares?
- For calamares, here is a [tutorial](https://www.youtube.com/watch?v=lBvps3VwEZs)

4. What is swap, should i use a swap file or a partition?
- For this question i am going to link you towards the same channel with the calamares manual partitioning, here is the [video](https://www.youtube.com/watch?v=0mgefj9ibRE)

5. Where can i find help for Linux?
- Almost every distro has a wiki section, a forum, a server, or something to help you out, like the [Arch](https://fernbacher.github.io/linux-for-begginers/#useful) wiki linked above.

6. Which Linux Distro should i install?
- As a newbie, you should look forward to install something like [Manjaro](https://manjaro.org/), [PopOS](https://pop.system76.com/) or [Linux Mint](https://linuxmint.com/) after spending some time on it, you can see what Linux can be, by doing it yourself, installing [Debian](https://www.debian.org/), [Arch](https://archlinux.org/) or their system-d free versions linked [at the top](https://fernbacher.github.io/linux-for-begginers/#distros)

7. How can i extract a .tar.zst archive?
- Run the command `tar -xvf yourarchivename.tar.zst`

`Updated; 28.11.2021`

 **Made with love for what Linux is about and what it offers us, by [Fernbacher](https://github.com/fernbacher).**

 **Theme used; [Gesko by P0WEX](https://github.com/P0WEX/Gesko)**
