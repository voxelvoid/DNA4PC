GRPViewer Readme File

Authored and Copyrighted (C)2006-2010 by Roma Loom
E-Mail: romaloom@hotmail.com
Site: www.loomsday.com

[WARNING]: This is the work on progress, use this program at Your own risk, any
instabilities and bugs supposed to be reported to my E-Mailbox.

Introduction
------------
GRP Viewer is a Windows utility that allows the user to browse, play, extract, delete, add and rename files from the Ken Silverman group file [.grp].

GRP Viewer was originally started from rebuilding of an unreleased DOS program
of mine named GView. The program was written for my own purposes never being
planned of releasing. That's why there is no supplemental help included yet.

Installation
------------
N/A yet

WARNING: there's no need to place both "palette.dat" and "names.h" files into
GRPViewer's directory in GRPViewer version starting from 1.c [06.13.05].

Extract both "GViewer.exe" and (optional)"GViewer.ini" from the archive into any directory.
Also you may put "names.h" and/or "palette.dat" files into GRPViewer's dir. This will disable
GRPV's ability to detect games and to load the apropriate palette and/or names
for the opened GRP file and force GRPV to strictly use the external palette and names you may want to put into GRPV's directory. If ART Tiles are not shown or
corrupted - take a look into GRPV's log window to see the error concerning
palette or names handling.

System Requirements
-------------------
OS: Win95, 98, NT, 2000, XP, Vista, Win7
[Warning]: This program was tested under WindowsXP and Win7 only, but supposed to be
fully functional under other versions of Windows.

Using GRP Viewer
----------------
Before You start: Every functional button has a hint wich describes the button
purpose, You can easily read this hint in the bottom of the main window.

After executable is launched You can either add files to an empty list to create
a compilation or open existing group file to extract or change its content and
then to save modified file.
[Warning: You cannot save modified GRP file directly, its format requires total
rebuilding of file, You can save modified file with name, different from
source file name, or change saving directory.]

GRP Viewer is capable of viewing embedded ART subfiles and converting it's
entries to Bitmaps [.bmp]. Find such ART file in the list and press Enter or
perform a double click by mouse to view its content. For viewing MAP files
rules are the same.

To rename the entry - select the entry You want to rename and press F2 button on
the keyboard.
[Warning]: renaming applies immediately and directly overwrites the name of the
corresponding entry in opened GRP File, so You have no need to save it via Save
button
[HINT]: performing a single click to the entry wich is already selected also
enters the rename mode]

Other operations (Add/Delete/AddAll/Extract/ExtractAll) can be performed by
corresponding buttons, placed on the window and requires to use Save button
aftermath.

[WARNING] Using HRTT is not recommended, it's broken
Using Hi-Res Textures Tool [HRTT]
---------------------------------
When started, GRPViewer writes (in log window) if there was 'duke3d.def' found
in the jfDuke dir. jfDuke directory is "D:\Games\Duke3d" by default, it's
written in "GViewer.ini" file. To set jfDuke directory You have to enter it in
the directory window and then press "Set JFD Path" in menu "Edit". The other way
is that jfDuke directory automatically sets when "duke3d.grp" file is opened to
the directory "duke3d.grp" belongs...
When jfDuke dir is set and "duke3d.def" found go to "JFDuke Tools" menu and see
that "Hi-Res Textures" submenu is not grayed, press it...
When the "HRTT" window appears the GRPViewer window is not operatable to prevent
multiple access to the "duke3d.grp"...
HRTT window contains:
1. ART files/ARTTiles list for selecting and browsing ART files found in
"duke3d.grp"...
2. ARTTile preview window
3. HiTile preview window
4. HiTile files list

The "BIND" button virtually assigns the selected HiTile file to the selected
ARTTile.
The "SAVE" button writes all the virtually assigned/reassigned definitions into
the "duke3d.def" file. The "SAVE" button activates only after any assignement is done.

WARNING:
The correct behaviour of BIND action in case of working with HR-Packs has not been confirmed yet.

HRTT subTools
-------------
This section is not available now

Models Tool
-------------
This section is not available now

SkyBox Tool
-------------
This section is not available now


Special Thanks
--------------
Ken Silverman (no comments)
JonoF (for giving the second life to "Duke Nukem 3D")
Devastator (for testing)
Mean Person (for testing & bug reports)
Piterplus (testing & bug reports)
Parkar (for giving me additional headache on making GRPV compatible with HRP)
Krado (for nice comments)
Dark Productions (for bug reports & suggestions)
Hitm4n (for introducing me to the "names.h" for SW)
Gambini (for reports and suggestions)
Kim Robinson of DN3D Repository [ http://dukerepository.com ]

And all other guys who are participating in "Duke Nukem 3D" enhancing project.

