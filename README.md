# MKV_GM
# v 1.0.0
 MKV_GM(Group MetaEditor) for editing multiple MKV files at once



Table of contents
-----------------

1. Introduction
2. Installation
2.1. Requirements
3. Examples / tutorial
4. Extra
-----------------

1. Introduction
---------------

with this tool you can quickly remove subtitles,specific audio track from any number or matroska fies at once
and afterwards you can rename the output files if you want.
if you use it for episodes in any web series you will just have to paste episode name when asked and the renaming pattern will be-
S{season number}E{episde number}- {name you enter}



for details on matroska files:-
http://www.matroska.org/

mkvmerge.exe is required by this tool and is included in the file
The full documentation for each command is now maintained in its
man page only. Type 'mkvmerge -h' to get you started.

2. Installation
---------------

just download and run MKV_GM.exe


 2.1. Requirements
 
 1-> mkvmerge.exe(included)
 2-> the folder path that you provide for mkv files NUST NOT contain anything other than specified number of MKV files by you, 
 move any other folders in that folder or srt files to different location before using MKV_GM
 
3. Examples / tutorial
---------------


Here is a simple example:-

Let's say you want to work on 10 episodes of season 1 of a certain show
that season folder path is:-
"D:\Downloads\cetrain show\season 1"

just rum MKV_GM from anywhere
it will ask for season number enter {1}
then total epispdes enter {10}

then enter if you want output files to be renamed (y or n)

if y then it will ask you for new names
so if you want episodes to be named like "S01E01-a.mkv" "S01E02-b.mkv" "S01E03-c.mkv".......so on for 10 files
just enter "a" then "b" then "c" and the rest will be done on its own

then give ypur choice about subtitles(y or n)
then about audio tracks it will show you available audio tracks for eg:-
1. Hindi
2. English
Enter the number you wanna remove and enter 0 to go to next step
then it will ask if you want to carry this audio configuration to all upcoming files (Y/N)

and then wait your output files will be stored in a sub directory named "processes" in your "season 1" directory


4. Extra
---------------
I'm Working on GUI interface and also automatic renamer so you wont have to enter episode names manually....

to Show support and kepp yourself up-to-date pls star this project
