# LabVIEWFontsFix
Tookit for Fix LabVIEW Fonts BUG In Asia CJK Language Windows, Apply To LabVIEW version later than 2011.

## What is the Bug?
If you set "Control Panel\Clock, Language, and Region\Region and Language\Formats\Format": as "Chinese/Japanese/Koarean"(which is default in localized Windows)

Using LabVIEW 2012 and later, some fonts such as "small fonts" or "NI7SEG" is not working

## How did this Fix work
add fonts config in LabVIEW.ini to make LabVIEW deal fonts Correctly 

## How to use this fix
### Source VI
run VI in sourcecode folder

If you install mutiple LabVIEW in Default Path(C:\Program Files (x86)\National Instruments or C:\Program Files\National Instruments) , you can enable "FixAllVersionOfLabVIEW" button.

###VIPM Install

Run from "LabVIEW\Tools\Fix Fonts..." menu

## Change Log
### 1.0.0.5

Make the fix to a LabVIEW Menu Tool

Use LabVIEW Install Path to Instead fixed path

Publish This Tool to VIPM

###1.0.0.1

First Release


## Todo
Make a dialog version.
Choose fonts to add to LabVIEW.ini.
make this fix work in Runtime envorment.
fonts auto install
## License
BSD3

## Reference
NI KB about the bug

https://knowledge.ni.com/KnowledgeArticleDetails?id=kA00Z0000019ZTFSA2&l=zh-CN


NI Community Discuss

https://forums.ni.com/t5/LabVIEW/quot-Small-Font-quot-in-LabVIEW-2013-2012-Icon-Editor/m-p/3291620/highlight/true#M962267

