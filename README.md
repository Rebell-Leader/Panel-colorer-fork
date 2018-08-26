# Panel-colorer-fork-
Plugin for the Far Manager and ConEmu
panel-colorer
Innovative UI plugin for FAR manager and ConEmu console emulator

Panel Colorer is an innovative and highly experimental plugin for FAR manager and ConEmu console emulator (i.e. it requires both).

Though FAR is a console application, ConEmu adds GUI flavor to it and allows some behavior a console application alone can't implement. Panel Colorer uses ConEmu to dynamically change the background of FAR application based on current FAR panels/windows state.

This is how it looks like:

http://panel-colorer.googlecode.com/svn/files/preview.png

http://panel-colorer.googlecode.com/svn/files/preview2.png

Features
Panels are colored based on volume drive type (fixed, removable, etc.), and each type has a set of slightly different colors to distinguish one drive from another.
Each panel features drive description, its size and free/total usage meter at the bottom of the panel.
Volumes mounted as folders (NTFS junctions) are recognized.
Plugin panels have their own color, too; Panel Colorer recognizes most popular FAR plugins and provides special text and images for them.
Rules for special directories like "C:\Windows\Temp" or ".svn".
Requirements
FAR 2.0 (build 1661+) x86.
ConEmu 100906+ (either x86 or x64 version).
Installation
Install FAR.
Install ConEmu into the same folder where FAR is located.
Unpack plugin to FAR 'plugins' folder.
Start ConEmu (which will load FAR, and plugin will be enabled by default).
In ConEmu options, make sure 'Enable plugins' option is turned on.
In ConEmu options, adjust background opacity to your liking (recommended is the middle value of 127).
TODO
Configurability (work in progress).
