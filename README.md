# VSC-SE-DEVKIT

## About this Fork

This fork was made because I didn't want to use the OmniSharp extension. Instead I opted for the C# Devkit extension. Unfortunately, the csproj was not update to the new SDK style. This fork tweaks it while keeping most of the csproj intact.

## Old (Slightly Adjusted) README

Here are the steps to set up Visual Studio Code for Space Engineers ingame
script development.

This will provide an environment where autocompletion / intelisense and
syntax checking work.

* I'll assume you already have SE installed!
* Install Visual Studio Code (VSC)
* Install the following VSC Extensions
  * Install C# Dev Kit extension in VSC
    _Note: In the original project, the OmniSharp extension was used._
  * install NuGet Package manager VSC Extension
* install .net cli tools / SDK (needed?)
* install net framwork devpack 4.6.1
  * https://www.microsoft.com/en-us/download/confirmation.aspx?id=49978


* Then clone this directory structure.
* If you have a non-standard SE location, change `SpaceEngineers.csproj`
* 'open folder' (this folder) from VSC.
*  copy `starter-template.cs` to a new file for each script you create
* change the `namespace`
* Put your code changes between the region tags (see comment in template)


Credit to https://github.com/mrdaemon for the working `.csproj` file.
