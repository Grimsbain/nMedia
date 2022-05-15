# nMedia
Add custom fonts and sounds using LibSharedMedia.

# How to use the .bat files.
Open the addon directory in the terminal and then do the following commands.
This will generate new files that include and any new fonts or sounds by filename.

* .\Fonts.bat | out-file Fonts.lua -encoding utf8
* .\Sounds.bat | out-file Sounds.lua -encoding utf8

If you don't want or can't use the batch files you can add a new font or sound by adding one of the following lines to the approrite file.

* LSM:Register("font", "FontNameHere", path.."Filename.Here")
* LSM:Register("sound", "SoundNameHere", path.."Filename.Here")
