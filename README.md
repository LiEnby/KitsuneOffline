# KitsuneOffline

![CI/CD Badge](https://github.com/KuromeSan/KitsuneOffline/actions/workflows/buildnw.yml/badge.svg)

Local Offline version of Kitsune Google Doodle, (Doodle Champion Island Games) 
useful if you want to play without internet (or just want to mod the game)

*rc7 version files located in logos/ folder*

How to play: (for noobs)  
Goto the releases page, download the zip and open kitsune.exe, there your done!   
https://github.com/KuromeSan/KitsuneOffline/releases/latest   
   
For pros (or if you just dont trust my executables):   
WHAT DO YOU MEAN YOU DONT TRUST SOME RANDOM GAL ON THE INTERNETS EXECUTABLES???!!!    
gosh okay, you wanna do it yourself? FINE    
    
download the latest nw.js from: https://nwjs.io/downloads/,   
then download the latest release of https://github.com/iteufel/nwjs-ffmpeg-prebuilt and replace nwjs ffmpeg.dll with that one   
(this makes video playback work)    
   
finally copy package.json and logos/ from this repository into the NWJS folder. start nw.exe and your done   
   
If you like living on the edge:  
You can download the releases from Github Actions directly. NOTE: THESE BUILDS ARE CREATED AFTER EVERY COMMIT!!! That means that if a game-breaking bug gets accidentally introduced, then the build will be broken and not work. This is in contrast to the releases page where builds are tested before release.
