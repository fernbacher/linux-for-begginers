**Linux For Beginners**
 
**For people looking to join linux. This is not a spoonfeeding repository.** 
 
**Its links to get you started, if you want to use linux, you have to document yourself otherwise you'll get stuck and go back to windows or whatever you used.**
 
# Distros

1. [Manjaro](https://manjaro.org/)
- I recommend XFCE from the official editions.

2. [Pop-OS](https://pop.system76.com/)
- Nvidia version if you have NVIDIA GPU, obviously. Otherwise the normal one.

3. [Archcraft](https://archcraft.io/)
- Archcraft is just another Linux distribution, made on top of Arch Linux, beautifully configured it will automatically give you the r/unixporn dream desktop you kept seeing on reddit.

4. [Arch-Linux-GUI](https://archlinuxgui.in/)
- There are multiple DE versions, aswell as 2 WM versions. If you want to use your keyboard alot more and not focus on GUI anymore, go for WM, also alot slimmer on resourcers.

5. [Debian](https://www.debian.org/)
- Usually used for servers, it uses LTS (long term support) kernel, the base of ubuntu and many many others.

6. [Devuan](https://www.devuan.org/)
- Debian without system-d [read about why system-d is bloat](https://ebin.city/~werwolf/posts/systemd-sucks/).

7. [Artix](https://artixlinux.org/)
- Arch without system-d. [read about why system-d is bloat, again](https://ebin.city/~werwolf/posts/systemd-sucks/).

# Custom Kernel

1. [Linux-Zen](https://github.com/zen-kernel/zen-kernel)
- Result of a collaborative effort of kernel hackers to provide the best Linux kernel possible for everyday systems. Some more details can be found on [Liquorix](https://liquorix.net).

2. [XanMod](https://xanmod.org)
- XanMod is a general-purpose Linux kernel distribution with custom settings and new features. Built to provide a stable, responsive and smooth desktop experience.

3. [Configure Your Own](https://youtu.be/NVWVHiLx1sU)
- Kinda outdated, but its a decent base to see what you can do and how hard/easy it is.

4.[Clear-Linux](https://aur.archlinux.org/packages/linux-clear/)
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
- A spotify client in the terminal written in Rust. **FOR PREMIUM ACCOUNTS ONLY**

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
- As a newbie, you should look forward to install something like [Manjaro](https://manjaro.org/) or [PopOS](https://pop.system76.com/), after spending some time on it, you can see what Linux can be, by doing it yourself, installing [Debian](https://www.debian.org/), [Arch](https://archlinux.org/) or their system-d free versions linked [at the top](https://fernbacher.github.io/linux-for-begginers/#distros)

`Updated; 07.11.2021`
