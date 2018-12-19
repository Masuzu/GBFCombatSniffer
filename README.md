# GBF Combat Sniffer

**Notice: work in progress**

GBF Combat Sniffer is a comprehensive multiboxing solution for Granblue Fantasy for competitive gameplay, which allows you to play with several windows open at the same time.

Whatever your ping is, be on even ground with other competitive players by not waiting for animations to complete and making the most of playing without any downtime.

- Cast skills and summons from multiple simultaneously open Granblue Fantasy windows. This also includes the use of consumable items such as  recovery potions.
- Undetectable and seamless integration with your favorite Granblue Fantasy extensions.
- Beat the competition by taking more turns on average than other players, while respecting the in-game limitations.

## Requirements

- Chrome browser version of the game: http://game.granbluefantasy.jp
- Download and install [Visual C++ Redistributable for Visual Studio 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48145). Make sure to download the 32-bit version (`vc_redist.x86.exe`).

After making sure that you satisfied the prerequisites, you will need to register a new account on the [download website](https://gbtools.azurewebsites.net/CombatSniffer/en/Home). This will grant you access to the [GBF Combat Sniffer management page](https://gbtools.azurewebsites.net/CombatSniffer/en/Manage), where you can get a new licence as well as the download link. Use the serial number generator provided on that same page (direct download [here](https://gbtools.azurewebsites.net/en/Account/GBFPokerBotSerialNumberGenerator)) to obtain a serial number for your computer.

Download the _GBF Combat Sniffer ZIP archive_ from the [GBF Combat Sniffer management page](https://gbtools.azurewebsites.net/CombatSniffer/en/Manage), **extract** the downloaded file and proceed as described below.


## Installation

As [ZooeyBot](https://gbtools.azurewebsites.net/ZooeyBot/en/Home) and [SarasaBot](https://gbtools.azurewebsites.net/SarasaBot/en/Home), GBF Combat Sniffer requires the installation of a Chrome extension.

### Installing the GBF Combat Sniffer extension

Navigate to [chrome://extensions/](chrome://extensions/) in your Chrome browser, then tick the _Developer mode_ checkbox:

![](https://i.imgur.com/c0sBgx7.png)

Then click on the _Load unpacked extension_ button and select the folder `gbf-combat-sniffer-extension`.
![](https://i.imgur.com/ywBf84F.png)

For people worried about the use of Chrome extensions, please [read this](https://github.com/Masuzu/ZooeyBot/wiki/FAQ#why-viramate-or-insert-here-any-other-extension-name-which-can-be-found-on-the-chrome-store-can-be-easily-detected).

**The GBF Combat Sniffer does not mess with any of the elements of the HTML page, neither does it try to modify any of the Javascript variables on the GBF webpage in a way that would infringe in-game limitations.**


## Getting started

1. Run GBFCombatSniffer.exe

2. Open Chrome devtool windows on each of the window you are using to play Granblue Fantasy (by pressing F12)

3. Start the GBF Combat Sniffer extension.

4. That is it! Whenever you start or resume a raid, attack or use abilities or summons, you will see details about the combat displayed in the console and the combat state will be synchronized accross all your Granblue Fantasy windows.

What happens if details were not updated (after refreshing too fast for instance while the response server response has not yet been received, resulting in an error page being displayed the next time you try to attack or cast a skill or summon)? No worries! Simply refresh any of the page and the combat details will be updated in the console and the different windows will all be synchronized together.
