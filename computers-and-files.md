# File systems

> [!NOTE]
> The explanations here are all from inference.

Contents
- [What's inside the computer that Kinger was using](#work-computer-windows-computer)
- [What was inside the server where Caine and the other AIs were running on](#circus-server)
- [File Info](#file-info) - Information about files
- [Trivia](#trivia)

## Work computer (Windows computer)

A classic windows computer file system

- C:\\CANDA\\
  - [Command](#Command)
  - [Config](#Config)
  - [Cookies](#Cookies)
  - [Cursors](#Cursors)
  - [Favorites](#Favorites)
  - [Characters](#Characters)
    - [AI](#AI)
      - [???](#???)
      - [CAINE](#CAINE)
    - [CA_NeuralScans [Obsolete]](#CA_NeuralScans-[Obsolete])
  - [Forms](#Forms)
  - [Help](#Help)
  - [History](#History)
  - [Java](#Java)
  - [Media](#Media)
  - [Msapps](#Msapps)
  - [Msremote.sts](#Msremote.sts)
  - [Occache](#Occache)
  - [Options](#Options)
  - [SendTo](#SendTo)
  - [Start Menu](#Start-Menu)
  - [System](#System)
  - [Temp](#Temp)
  - [Temporary Internet Files](#Temporary-Internet-Files)
  - [Wordview](#Wordview)
  - [Accessor.gp](#Accessor.gp)
  - [Accstat.exe](#Accstat.exe)
  - [Addfnpr.reg](#Addfnpr.reg)
  - [Ah](#Ah)
  - [ah](#ah)
  - [Arp.exe](#Arp.exe)
  - [Black](#Black)
  - [Blue](#Blue)
  - [Bubbles.bmp](#Bubbles.bmp)


## circus server

- It's running on linux
- hostname is "circus"

- /
    - [usr/](#usr)
        - [ai/](#ai)
            - [agent/](#agent)
                - [caine/](#caine)
                - [experimental/](#experimental)
            - [module/](#module)
                - consciousnessresearch
                - brainscans
        - [bin/](#bin)
            - [gdb](#gdb)
        - [local/](#local)
            - [bin/](#bin)
                - [clisp](#clisp)
    - [secured/](#secured)
        - [caine-core.lisp](#caine-corelisp)
        - [paraphernalia-engine.dat](#paraphernalia-enginedat)
        - [[Scratch].dat](#scratchdat)
        - [[Ragatha].dat](#ragathadat)
        - [wacky-watch.c](#wacky-watchc)
        - [bubble-chef.lisp]()
    - [home/](#home)
        - [kinger/](#kinger)
            - GreenGROUNDS
            - securitysweep_stealth
            - Switcheroo_realt
            - IABORT

## File info

### `caine-core.lisp`

Contains caine's core source code

### `paraphernalia-engine.dat`

proprietary data file, most likely information about how to run AI programs

### `[Scratch.dat]`

Mind scan of Scratch

### `[Ragatha].dat`

Mind scan of Ragatha

### `wacky-watch.c`

Code for the wacky-watch

### `bubble-chef.lisp`

Source code of bubble?

### `GreenGROUNDS`

Seems to be about declaring authority. Accepts two parameters

- `--daemon`
    - A switch
    - Run program as a daemon service
- `--target`
    - A parameter
    - what to target

### `securitysweep_stealth`

Might be about deleting files. Accepts `-u` parameter

- `-u`
    - User

### `Switcheroo_realt`

might be the same as [GreenGROUNDS](#greengrounds), seems that Caine renamed it?

### `gdb`

"GDB, the GNU Project debugger, allows you to see what is going on `inside' another program while it executes -- or what another program was doing at the moment it crashed."[[1]](https://sourceware.org/gdb/)

### `clisp`

"CLISP is a popular, stable, and highly portable ANSI Common Lisp implementation, primarily used for learning, rapid prototyping, scripting, and **developing complex applications requiring advanced AI or data processing features**. It is widely used on GNU/Linux and Unix systems due to its built-in readline interpreter, debugger, and easy setup compared to faster alternatives like SBCL"

## Trivia

- `CANDA` might be a concatenation of "CA" and "NDA," in which if it were, would mean "Caine &amp; Abel Non-disclosure agreement"