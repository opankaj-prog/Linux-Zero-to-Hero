# History of UNICS/UNIX and LINUX or GNU/LINUX
## The Early Days of Computing (1950s–1960s):
Before UNIX, computers were huge, expensive, and ran specific software. Every vendor (IBM, DEC, etc.) had its own proprietary OS. This made sharing software and knowledge across systems almost impossible.
### Proprietary OS:
A proprietary operating system (OS) is one that is owned and controlled by a single company or individual, and its source code is not openly available to the public. It Requires you to buy a license or agree to terms of use, Very limited — you cannot change the internals and you rely on the vendor for any Support and Updates (you depend on them).

### In the 1950s–60s:
- Each computer had its own unique OS, often written in machine-specific assembly.
- If you bought a new model, you had to rewrite your OS and software.
- Operating systems were deeply entangled with the hardware they ran on.

## 1964 – Multics Project starts at Bell Labs:
  - In Murray Hill, New Jersey, Bell Labs, along with MIT and General Electric, started developing a project called Multics (Multiplexed Information and Computing Service).
  - The goal was to Build a next-generation, multi-user, time-sharing OS.
  - Multics was innovative but became too complex, slow, hard to maintain and delayed in delivery because of these Bell Labs stopped the Multics project in 1969.

## 1969 – Birth of UNIX (UNICS → UNIX):
- After dropping Multics project, Ken Thompson who was working alone initially at Bell Labs later with the Dennis Ritchie and Rudd Canaday, created a simpler OS on a PDP(Programmed Data Processor)-7 minicomputer using assembly language.
- This system was first called UNICS ("Uniplexed Information and Computing Services") and Later renamed as UNIX.

## 1971 – UNIX V1 – The first operational version:
- UNIX V1 ran on PDP-11 which featured the basic tools like File system, Shell, and Basic text editors.
## 1973 – UNIX Rewritten in C (Version 4):
By **1973**, UNIX was rewritten in the C programming language by Dennis Ritchie and it was a groundbreaking move. This was the first system to decouple OS from hardware which made UNIX portable to other systems.
## 1975 – UNIX Version 6 (V6) - this version changed the world:
- The UNIX V6 ran on PDP-11 and first widely distributed version to universities and academic institutions.
- It was useful for research, modifications and teaching OS internals.
- It influenced Andrew S. Tanenbaum, who was a Computer science professor at Vrije Universiteit Amsterdam (Netherlands), created MINIX (Mini UNIX — a small, educational version of the UNIX operating system) in 1987.
- **Used in:**
    - MIT
    - Harvard
    - UC Berkeley (which later created BSD)

## Late 1970s–1980s – UNIX Evolves and Splits:
- UNIX V7 (1979) was considered the last "clean" Bell Labs version.
- **Branches began:**
     - System V (AT&T)
     - BSD (Berkeley)
- **Features added:**
     - vi editor
     - C Shell (csh)
     - TCP/IP stack (in BSD)
- **Commercial versions emerged:** SunOS, HP-UX, AIX, SCO UNIX

- ***This fragmentation led to the “UNIX Wars”.***



## 1983 – GNU Project Begins:
- Richard Stallman started GNU (GNU’s Not UNIX) to create a free UNIX-compatible OS and developed gcc (C Compiler), bash (Shell), and coreutils (ls, cat, etc.) but GNU lacked a kernel.

## 1991 – Linux is Born:
- Linus Torvalds, a 21-year-old computer science student at the University of Helsinki, was frustrated by MINIX (an educational UNIX clone by Andrew Tanenbaum) because MINIX was closed for modification and couldn’t use full hardware features.
- So Linus created a kernel for his Intel 386 PC and Used GCC (GNU compiler) to build it.
- On August 25, 1991, he posted this on comp.os.minix:
 “I’m doing a free operating system (just a hobby, won’t be big and professional like GNU)…”  and Licensed it under the GNU GPL(General Public Licence) to ensure it stays free.

## 1992 – GNU + Linux  Full OS:
- People combined GNU tools (compiler, shell, etc.) and Linux kernel. The result was the GNU/Linux Operating System  fully functional UNIX-like system.
- It could boot, compile, run services, and connect to the internet. 

## 1993 Onward – Rise of Distributions:
- **First distributions:**
        - Slackware (1993)
        - Debian (1993)
        - Red Hat (1994)
 ### ***They bundled Linux Kernel, GNU tools , Installer, package managers.*** ###
  
## 2000s–till now – Linux Dominates the World:
- 90%+ of **cloud servers**
- 100% of **supercomputers**
- 70%+ of **mobile devices (Android)**
- **Most IoT devices**
