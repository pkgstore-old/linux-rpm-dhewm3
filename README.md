# Doom 3 GPL source port

**dhewm3** is a source port of the original Doom3 (not Doom3 BFG, for that you may want to try RBDoom3BFG). It's known to work on Windows, Linux, macOS, FreeBSD, OpenBSD and AROS, but it should work on (or be easily portable to) any system that supports OpenGL 1.4 with ARB shaders, SDL and OpenAL.

Compared to the original version of Doom3, dhewm3 has many bugfixes, supports EAX-like sound effects on all operating systems and hardware (via OpenAL Softs EFX support), has much better support for widescreen resolutions and has 64bit support.

It only supports old Mods if they either don't require their own game DLL or have been ported to dhewm3 - see the Mods page for more information.

Note that while the Doom3 source code has been released under GPL, you still need to legally own the game and provide dhewm3 the game data to play. See the How to Install section for more information.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/dhewm3
$ dnf install -y dhewm3
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y dhewm3
```

## Remove

```
$ dnf erase -y dhewm3
$ dnf copr remove pkgstore/dhewm3
```
