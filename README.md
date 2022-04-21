# milkdrop - buildable for Visual Studio 2019
This is the well-known Winamp plugin, written by Ryan Geiss. Full credit goes to him for creating it. It was open sourced from the official web site here:
https://www.geisswerks.com/milkdrop/

This version has been modernized to build with Visual Studio 2019, for my own personal convenience. It has the following changes:
* Auto VS project/sln conversion
* Project has a NuGet reference to the D3DX package
* Added hack to use unlocalized printf and scanf because the localized ones were causing problems
