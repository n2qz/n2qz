# n2qz

<details>

<summary>Free and Open Source Software (FOSS) contributions</summary>

# Free and Open Source Software (FOSS) contributions

## Batocera.linux https://batocera.org/
June 2023 - present
- Project description: Batocera.linux is an open-source Buildroot Linux operating system designed for retro gaming, providing a user-friendly interface and support for a wide range of gaming consoles and emulators.
- Role: Developer/Maintainer
- Source archives: https://github.com/batocera-linux
- Credited as: n2qz
- Contributions:
  - https://github.com/batocera-linux/batocera.linux/pulls?q=is%3Apr+author%3An2qz+is%3Aclosed
  - https://github.com/batocera-linux/batocera-emulationstation/pulls?q=is%3Apr+is%3Aclosed+author%3An2qz
  - https://github.com/batocera-linux/buildroot/pulls?q=is%3Apr+is%3Aclosed+author%3An2qz
- Languages: Python, C++, bash, Buildroot

## checkov 
August 2020
- Project description: Checkov is an open-source static code analysis tool for identifying security and compliance issues in infrastructure-as-code (IaC) configurations, such as Terraform, CloudFormation, and Kubernetes.
- Source archive: https://github.com/bridgecrewio/checkov
- Credited as: n2qz
- Credits: https://github.com/bridgecrewio/checkov/pull/499
- Contributions: Web proxy support
- Languages: Python

## pgmaze
May 2018
- Project description: pgmaze is a maze game written in Python, using the pygame library.
- Role: Author (derived from several credited sources)
- Source archives: https://github.com/n2qz/pgmaze
- Credited as: n2qz
- Languages: Python

## WiiMC
March 2012
- Project description: WiiMC is an open-source media center application for the Nintendo Wii, enabling playback of videos, music, and streaming content from various sources.
- Source archive: https://github.com/dborth/wiimc
- Credited as: entropy
- Credits: https://github.com/dborth/wiimc/blob/master/README.md
- Contributions:
  - Improved music playlist sorting - now it is per-folder (patch by entropy)
  - Added playlist reset with minus key (patch by entropy)
  - Added a new "Through" setting for music playlists (patch by entropy)
- Languages: C

## WiiFlow
January 2012 - March 2012
- Project Description: WiiFlow is an open-source USB loader for the Nintendo Wii, allowing users to load and organize games, homebrew, and multimedia from external storage with a sleek, customizable interface.
- Source archive: https://github.com/Fledge68/WiiFlow_Lite
- Credited as: entropy
- Credits: https://github.com/Fledge68/WiiFlow_Lite/blob/master/source/defines.h
- Languages: C, C++
- Contributions:
  - Fix Issue 27:  "When in 'channel view' and wiiflow is locked the wrong icon is displayed"
  - Comment out reload of IOS 58 before booting homebrew.  Stops random code dumps when booting HB.
  - Ensure that long game titles are NUL-terminated
  - Bug fix:  index for EXIT_TO_DISABLE changed, correct hard-coded value
  - Allow installation of games with titles containing illegal filename characters
  - Use LF carriage control in shell scripts to fix build under Linux
  - Add a game config button (cfgg28) to toggle "custom" setting of channels
  - Support custom titles for homebrew
  - More cache overrides at startup, plus related debugging gprintfs
  - Make debug message explicit about enabling or disabling IOS reload block
  - Add option "update_cache" in GENERAL section, to force cache update at startup
  - Allow display of homebrew while parental controls are enabled, if option "parental" is set in homebrew section of wiiflow.ini
  - Restore code to hide game adult toggle and game settings button while parental controls enabled
  - Show an error message when parental unlock password is entered incorrectly.
  - Use homebrew icon.png to make rough but serviceable homebrew covers

## nts_nys_traffic_routing
2008 - present
- Project description: nts_nys_traffic_routing is a Docker container to serve a web page providing routing data for the ham radio National Traffic System in New York State.
- Role: Author
- Source archives: https://github.com/n2qz/nts_nys_traffic_routing
- Credited as: n2qz
- Languages: Perl, Docker

## paclink-unix
November 2005 - October 2016
- Project description: paclink-unix is a UNIX client interface to the Winlink 2000 email system for ham radio.
- Role: Original author
- Credited as: n2qz
- Credits: https://github.com/nwdigitalradio/paclink-unix/blob/master/AUTHORS
- Source archives: 
  - https://paclink-unix.sourceforge.net/
  - https://github.com/nwdigitalradio/paclink-unix
- Languages: C

## FreeTDS https://www.freetds.org/
August 2002 - January 2004
- Project description: FreeTDS is a set of libraries for Unix and Linux that allows your programs to natively communicate with Microsoft SQL Server and Sybase databases.
- Role: Developer/Maintainer
- Credited as: Nicholas S. Castellano entropy@freetds.org, entropy@tappedin.com, Nicholas_Castellano@acml.com
- Credits: https://github.com/FreeTDS/freetds/blob/master/AUTHORS.md
- Source archives: https://github.com/FreeTDS/freetds
- Languages: C

## NetBSD https://netbsd.org/
1997-1998
- Project description: NetBSD is an open-source, Unix-like operating system known for its portability, security, and wide support for various hardware platforms.
- Source archive: http://cvsweb.netbsd.org/
- Credited as: maximum entropy
- Credits:
  - http://cvsweb.netbsd.org/bsdweb.cgi/src/sys/arch/atari/vme/if_le_vme.c?rev=1.20;content-type=text%2Fplain;only_with_tag=MAIN
  - http://cvsweb.netbsd.org/bsdweb.cgi/src/sys/arch/atari/vme/leo.c?rev=1.22&content-type=text/x-cvsweb-markup&only_with_tag=MAIN
- Contributions:
  - Device driver support for BVME410 VMEbus lance NIC card
  - Device driver support for Circad Leonardo VMEbus graphics card
  - Various bug fixes and minor features
- Languages: C

## xmame
April 1997 - June 1997
- Credited as: entropy
- Credits
  - https://web.archive.org/web/20090308011558/http://x.mame.net/changes-unix.html
  - https://www.cs.utexas.edu/users/klivans/xmame-doc-5.html#ss5.2 ( was http://www.dit.upm.es/~jantonio/mame/ )
- Contributions:
  - added SGI IRIX sound support
  - Miscellaneous IRIX bug fixes
  - Various generic bug fixes
  - Initial port to NetBSD
- Languages: C

## atari800
September 1996 - October 1996
- Source archive: https://atari800.github.io/ <!-- ( was: http://www.signus.demon.co.uk/david/atari/atari.html ) -->
- Credited as: Maximum Entropy
- Credits:
  - https://github.com/atari800/atari800/blob/231a72df3709be5d88bf1639bcfb4f3259c9fa41/DOC/CREDITS
  - https://github.com/dmlloyd/atari800/blob/master/DOC/CHANGES.OLD
- Contributions:
  - various corrections to Motif code
  - Motif callbacks for Insert Disk, Eject Disk and Insert ROM
  - bug fixes in sio.c
  - bug fix to devices.c allowing DOS 2.5 to get a directory of H:
  - bug fix to monitor.c (EOF on input + blank lines)
  - undocumented commands added to monitor's "HELP" command
  - implementation of Disable Drive menu item for Motif
  - fixed scrolling problem for SGI and SPARC machines
  - added FPS Monitor to X11 and Motif versions
  - changes to pattern matching for H: device
  - Motif fileselector retains state from one invocation to the next
  - fixed an uninitialized pointer
  - tidied up declaration of various functions
  - removed warning messages when compiled with -Wall
  - configuration program detects if longwords need to be aligned
  - modification to X11 paddle emulation
  - removed annoying flicker present under some X11 platforms
  - removed hardcoded paths in Motif code
  - various fixes for curses mode
- Languages: C

## ew-too/summink
April 1995 - 2003
- Project description: Summink is an open-source talker server based on the ew-too engine, designed to facilitate the creation and management of interactive, text-based worlds and environments.
- Source archive: https://github.com/talkersource/summink
- Ran a highly-customized version: https://github.com/n2qz/ds (private repo)
- Languages: C

## GNU tar
March 1995
- Source archive: https://ftp.gnu.org/gnu/tar/tar-1.12.tar.gz
- Credited as: maximum entropy
- Credits: https://github.com/Distrotech/tar/commit/1da46c233dc3b44e472a41c8e8e781c3c72bbc88
- Languages: C

## MiNT/MiNTlibs
1994 - 1997
- Project description: MiNT (MiNT Is Not TOS) is a multitasking operating system for Atari ST/TT computers, providing advanced features like preemptive multitasking, memory protection, and compatibility with UNIX-like environments.
- Role: Contributor, primary maintainer of MiNTlibs (GNU libc port)
- Credited as: entropy@gnu.ai.mit.edu
- Credits:
  - https://github.com/freemint/freemint/blob/d36c5b6ad363ef8e18d6ee71c53f21b14092f3a9/doc/ChangeLog.old/ChangeLog.%230.50-1.12
- Source archives:
  - http://www.umich.edu/~archive/atari/Mint/
  - https://github.com/freemint/freemint
- Languages: C

## Morse Code decoder
1991 (Published September 1994)
- Project description: Takes input from a Morse Code key and converts it to readable text.
- Role: Original author
- Source archives: https://www.atariarchives.org/cfn/05/07/0042.php
- Languages: BASIC

# Indirect contributions

## pat
- Project description: Pat is a cross platform Winlink client with basic messaging capabilities.
- Source archive: https://github.com/la5nta/pat
- Credited as: n2qz
- Credits: https://github.com/la5nta/pat/blob/master/README.md

## wl2k-go
- Project description: wl2k-go is a collection of Go packages implementing various parts needed to build a Winlink client.
- Source archive: https://github.com/la5nta/wl2k-go
- Credited as: n2qz
- Credits: https://github.com/la5nta/wl2k-go/blob/master/README.md

</details>
