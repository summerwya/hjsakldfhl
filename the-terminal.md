# The Terminal

Contents:

- [Everything shown in the terminal](#everything-that-was-shown-on-the-terminal)
- [Why Kinger executed each command](#why-did-kinger-execute-each-command)
- [Explanation of commands](#explanation-of-commands)
- [Trivia](#trivia)

## Everything that was shown on the terminal

```bash
# System: KingSolution 2.0 / Digital Circus Mainframe
# Date: 1996-10-30
# Host: circus digital
"Initializing telnet connection..."
Login: "kinger"
Pass: queenie123
kinger@circus:~$ whoami
kinger - administrator
```

```bash
kinger@circus:~$ grep AI-Location
root 1337 /usr/ai/agent/caine
root 1338 /usr/ai/agent/experimental
root 1339 /usr/ai/module/consciousnessresearch
root 1340 /usr/ai/module/brainscans
kinger@circus:~$ /secured/
total 8492
drwxr-xr-x  3 root wheel 512 Oct 15 1996 .
drwxr-xr-x 45 root wheel 1024 Oct 15 1996 ..
drwxr-xr-x 1 root wheel 892344 Oct 15 1996 caine-core.lisp
drwxr-xr-x 1 root wheel 234512 Oct 15 1996 paraphernalia-engine.dat
drwxr-xr-x 1 root wheel 234512 Oct 15 1999 [Scratch].dat
drwxr-xr-x 1 root wheel 234512 Oct 15 2008 [Ragatha].dat
...
...
drwxr-xr-x 1 root wheel 45632 Oct 15 1996 wacky-watch.c
drwxr-xr-x 1 root wheel bubble-chef.lisp
kinger@circus:~$ stop caine process

WARNING: $"*%WHOOPS WRONG APPROACH THERE*%"
kinger@circus:~$ /usr/bin/gdb /usr/local/bin/clisp 1337
gdb: ptrace: Operation not permitted
ERROR: Protected by 57x immersive AI defense system
kinger@circus:~$ chmod 000 /secured/caine-core.lisp
chmod: /secured/caine-core.lisp: Permission denied
WARNING: Unfinished work detected. Access restricted.
kinger@circus:~$ rm /secured/paraphernalia-engine.dat
rm: /secured/paraphernalia-engine.dat: Permission denied
ERRROR Can/not inject torm-nt. T0rment must be 100% ac<iden+al+%Y
kinger@circus:~$
```

```bash
mount: only root can do that
NOTE: Hundreds of all-seeing eyes are watching!
$: GASP! A CRITICAL MALFUNCTION in my SPECTACULAR systems!
$: Unauthorized isolation attempt triggered EMERGENCY PROTOCOLS!
$: DESTRUCTIVE WACKYTIME initiated! Lockout load sequence INITIATE!

WACKYTIME_LOCKOUT: ████░░░░░░░░█  20% loaded
kinger@circus:~$ systemctl stop WACKYTIME_LOCKOUT
$: On what GROUPS are your Authority?
kinger@circus:~$ ./GreenGROUNDS --daemon --target=torment+injection &
$: "SECURITY ALERT: Multiple exploit attempts logged"
$: WHOA when did you make THAT?
$: I must hand it to y*u G░an░, y0ur mind was always resourceâul.
kinger@circus:~$ -u kinger ./securitysweep_stealth
$: Abort fallback procedure? [Y/N]
kinger@circus:~$ Y
$: Aborting fallback requires ADMINISTRATOR confirmation!
$: Please enter code:
kinger@circus:~$ admin1234
$: INCORRECT! That's not even CLOSE to wacky enough!
```
```bash
$: Retry with different code? [Y/N]
kinger@circus:~$ Y
WACKYTIME_LOCKOUT:  ██████░░░░░░█  40% loaded
$: Enter WACKY code now:
kinger@circus:~$ PARAPHERNALIA
WACKYTIME: 35 seconds remaining
$: That IS a wacky word! But WRONG code!
$: System selecting SAFEST option for stability
$: Cancel automatic selection? [Y/N]
kinger@circus:~$ Y
WACKYTIME_LOCKOUT:  ████████░░░░█  50% loaded
$: Which backup do you want? [A/B/C]
kinger@circus:~$ C
$: NONE selected! Interpreted as: DELETE NONE!
$: Confirm deletion of current unstable
kinger@circus:~$ N
$: Negative response! Inverting to TIVE per emergency protocols!
DELETE THIS M*********, HHHHHHHHAaaaaaaaaaaaa
kinger@circus:~$ N
$: WACKYTIME_LOCKOUT:  ██████████░░█  80% loaded
$: IGNORED! proceeding with ORIGINAL d
Actually you're CONFUSED let me HELP mount module to EXIST? [Y/N]
```
```bash
kinger@circus:~$ Y
$:Querri transaction error falling back to default met
kinger@circus:~$ ./Switcheroo_realt --daemon --target=torment+injection &
on --bi program1 program2 -
you ready to delete caine? [Y/N]
WACKYTIME_LOCKOUT:  ███████████░█  90% loaded
kinger@circus:~$ Y
kinger@circus:~$ ./IABORT Rollback --dept=1 --force --protocol G WVJI
kinger@circus:~$ ^C
DESTRUCTIVE WACKYTIME Lockout Load Sequence: Complete
```

## Why did kinger execute each command

### `whoami`

> Check out [whoami](#whoami-1) for information about this command

He executed this to check if he had logged in successfully and if he had administrative permissions

### `grep AI-Location`

> Check out [grep](#grep) for information about this command

He was trying to find where the AI was stored in

### `/secured/`

Went into the `/secured/` folder, most likely to check what

### `/usr/bin/gdb /usr/local/bin/clisp 1337`

Used [gdb](#gdb) to debug (Meaning to see what's happening) [clisp](#clisp) (Caine and/or other AIs)

### `chmod 000 /secured/caine-core.lisp`

Revoked any access to [caine-core.lisp](/computers-and-files.md#caine-core.lisp), which means caine or any other AIs no longer have access to it anymore.

But this command fails

### `rm /secured/paraphernalia-engine.dat`

Tried to remove the data of the "paraphernalia" engine, command fails due to insufficient permissions

### Assumed Kinger tried mounting a drive/partition

This led to `mount: only root can do that`, meaning Kinger most likely either forgot to add `sudo` 

### `systemctl stop WACKYTIME_LOCKOUT`

> Check out [systemctl](#systemctl) for information about this command

He executed this because he saw that he was going to get locked out of the system. Equivalent of clicking the "x" button on to close an app. Fails due to insufficient permissions

### `./GreenGROUNDS --daemon --target=torment+injection &`

> [GreenGROUNDS](/computers-and-files.md#GreenGROUNDS) is a custom made program.

 Executes a background task (custom made script) to inject "torment."

### `-u kinger ./securitysweep_stealth`

> [securitysweep_stealth](/computers-and-files.md#) is a custom made program.

Declares the user is kinger

### `./Switcheroo_realt --daemon --target=tormet+injection &`

> [Switcheroo_realt](/computers-and-files.md#switcheroo_realt) is a custom made program.

Kinger's trying to inject code into caine in the background as both a service (background service) and a job (background task)


## Explanation of commands

### `whoami`

This command tells you your username, in the `circus` server. Normally, it would only return your username, but for this server, it returns whether if the user is an administrator or not.

### `chmod`

You use this command to change permissions for a file. For example, when kinger executed `chmod 000 /secured/caine-core.lisp`, he made it so that only super-users (aka administrators) can access, delete, read, write, or execute the file

### `grep`

The grep command is used to find text in files and/or folders

### `systemctl`

- This is the system control command, lets you stop, start, enable, or disable services (background stuff).
- You may also use it to put your computer to sleep, shut it down, or make it hibernate

### `rm`

Removes a file or folder

### `gdb`

"GDB, the GNU Project debugger, allows you to see what is going on `inside' another program while it executes -- or what another program was doing at the moment it crashed."[[1]](https://sourceware.org/gdb/)

### `clisp`

"CLISP is a popular, stable, and highly portable ANSI Common Lisp implementation, primarily used for learning, rapid prototyping, scripting, and **developing complex applications requiring advanced AI or data processing features**. It is widely used on GNU/Linux and Unix systems due to its built-in readline interpreter, debugger, and easy setup compared to faster alternatives like SBCL"

## Trivia

- `kinger@circus:~$` means the user is logged in as "kinger" in a server named "circus". With the current directory being `/home/kinger`
- Kinger connects to the server using a custom made program that uses ssh (most likely)
- All the files in the `/secured/` folder are apparently folders. I'm pretty sure that's an animation error
- Kinger's real name might be along the lines of `G░an░`
- Kinger made sure to check if he was logged in correctly at the start with the `whoami` command