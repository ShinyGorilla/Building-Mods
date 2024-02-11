# Building-Mods
A guide to build un-released Gorilla Tag mods that have a github repo

## Requirements
* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/) **USE THE FREE DOWNLOAD**
* C# knowledge

## Instructions
* Download the source code of the mod you want to build
* Unzip the downloaded file, we will call this "Source Code Folder"
* In the source code folder find a file with .CSPROJ at the end
* Right click that file, click open with and find "Microsoft Visual Studio 2022"
* A screen should pop up with a bunch of code
* Hold CTR+B on your keyboard
* If an error shows up ask for a fix in the [Gorilla Tag Modding Group Discord](https://discord.com/invite/bucBZEdxce) please be very specific as we may not know what you are talking about
* Once the error is fixed or if you didn't have an error, wait until the thing at the bottom completes

## Finding the DLL
* Depending on what mod you have the built dll will go in different locations

### Method 1
* Most common way is going back the the source code folder, open the Bin folder then open the Debug folder
* In the Debug folder click Date Modified
* The first thing on the list should be the mods name and then ".DLL"
* If this doesn't work use Method 2

### Method 2
* In visual studio at the bottom there should be this thing that says something similar to "Name of mod -> C:\PLACEHOLDER"
* Copy all of the text in that line after the arrow
* Paste it into the search in file explorer but before searching delete the ".DLL" part of it
* Click enter and then click Date Modified and the mod dll should be the first thing on the list
* Copy that into your plugins folder, sometimes it may already be in your plugins folder if the mod was set up that way
