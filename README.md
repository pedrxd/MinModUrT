# MinMod for UrbanTerror
**Four basic mods that must not miss on any urt server; infinite Stamina, no fall damage, colours names and infinite wall jumps**

## Cvar/Usage
It contains all the original cvars and 4 more for control the mods added. All mods are enabled by default you can use the following commands for disable it (for enable just replace '0' with '1'):

 > set sv_infiniteStamina 0

 > set sv_infiniteWallJumps 0

 > set sv_nofallDamage 0

 > set sv_colourNames 0


## Installation
You can download directly the binaries from https://github.com/pedrxd/MinModUrT/releases .
### Windows
If you want the **dedicated server** download the file named 'Quake3-UrT-Ded.exe' and replaced it on the UrbanTerror folder, execute it as normal.

For **client version** download 'Quake3-UrT.exe' and replaced it on the UrbanTerror folder, execute it as normal.

### Linux
If you want the **dedicated server** download the file named 'Quake3-UrT-Ded.i386/x86_64'¹ and replaced it on the UrbanTerror folder, execute it as normal.

For **client version** download 'Quake3-UrT.i386/x86_64'¹ and replaced it on the UrbanTerror folder, execute it as normal.

 ¹ *i386 is for 32bits and x86_64 for 64bits*

## Build
First of all download dependences: For **Ubuntu**
```
sudo apt-get install make gcc libsdl-dev
```
And compile it
```
make
```
Binary files are placed on the build folder.



###### ------------------------------ Credits ----------------------------------

Maintainers
  Aaron Gyes <floam at sh dot nu>,
  Ludwig Nussel <ludwig.nussel@suse.de>,
  Thilo Schulz <arny@ats.s.bawue.de>,
  Tim Angus <tim@ngus.net>,
  Tony J. White <tjw@tjw.org>,
  Zachary J. Slater <zakk@timedoctor.org>

Significant contributions from
  Ryan C. Gordon <icculus@icculus.org>,
  Andreas Kohn <andreas@syndrom23.de>,
  Joerg Dietrich <Dietrich_Joerg@t-online.de>,
  Stuart Dalton <badcdev@gmail.com>,
  Vincent S. Cojot <vincent at cojot dot name>,
  optical <alex@rigbo.se>
