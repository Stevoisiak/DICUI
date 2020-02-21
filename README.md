# DICUI

DiscImageCreator/DiscimageChef UI in C#

[![Build status](https://ci.appveyor.com/api/projects/status/3ldav3v0c373jeqa?svg=true)](https://ci.appveyor.com/project/mnadareski/dicui/build/artifacts)

This is a community project, so if you have some time and knowledge to give, we'll be glad to add you to the contributor of this project :)

DICUI relies on the following projects:
- **DiscImageCreator** by Sarami - Dumping - [GitHub](https://github.com/saramibreak/DiscImageCreator)
- **DiscImageChef** by Claunia - Dumping - [GitHub](https://github.com/discimagechef/DiscImageChef)
- **BurnOutSharp** - Protection scanning - [GitHub](https://github.com/mnadareski/BurnOutSharp)
- **UnshieldSharp** - Protection scanning - [GitHub](https://github.com/mnadareski/UnshieldSharp)

**Note:** Both DiscImageCreator and DiscImageChef have WIP builds. In general, WIP builds are not supported with new flags or features until they make it into the stable release. The exception to this rule is currently DiscImageChef, due to the very old last stable release. It is recommended that you either download or build the latest version of DiscImageChef for use with DICUI.

## System Requirements

Even though this is written in C#, this program can only be used on Windows systems due to one of the base programs, DiscImageCreator, being Windows-only. There is some preliminary support for Linux underway, and we will try to integrate with that when the time comes.

- Windows 7 (newest version of Windows recommended)
- [.NET Framework 4.6.2](https://www.microsoft.com/en-us/download/details.aspx?id=53344), [.NET Framework 4.7.2](https://support.microsoft.com/en-us/help/4054530/microsoft-net-framework-4-7-2-offline-installer-for-windows), or .NET Core 3.0 Runtimes (.NET Core 3.0 is not currently functional due to a dependency, please do not use it)
- 128 MB of free RAM
- As much hard drive space as amount of discs you will be dumping (20+ GB recommended)

Ensure that your operating system is as up-to-date as possible, since some features may rely on those updates.

## Releases

For those who would rather the most recently stable build, ownload the latest release here:
[Releases Page](https://github.com/SabreTools/DICUI/releases)

For those who like to test the newest features, download the latest AppVeyor WIP build here: [AppVeyor](https://ci.appveyor.com/project/mnadareski/dicui/build/artifacts)

## Changelist

A list of all changes can now be found [here](https://github.com/SabreTools/DICUI/blob/master/CHANGELIST.md).

## Contributors

Here are the talented people who have contributed to the project so far:

- **darksabre76** - Project Lead / Backend Design
- **ReignStumble** - Former Project Lead / UI Design
- **Jakz** - Primary Feature Contributor
- **NHellFire** - Feature Contributor

## Notable Testers

These are the tireless individuals who have dedicated countless hours to help test the many features of DICUI and have worked with the development team closely:

- **Dizzzy/user7** - Concept, ideas, tester
- **Kludge** - Primary stress tester
- **ajshell1** - Tester
- **eientei95** - Tester
