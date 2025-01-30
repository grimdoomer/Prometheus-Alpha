# Prometheus Alpha
Welcome to the Prometheus Alpha test! Prometheus is a modding tool for the Original Xbox version of Halo 2. It allows you to modify and create new maps, place spawns, edit object properties, and more. This page contains some useful resources for learning how to use Prometheus, open issues, and how to report new issues.

https://github.com/user-attachments/assets/1e61f729-cf7a-43f7-bbfb-86bdddd36c35

## Download
The Prometheus Pre-Alpha build can be downloaded [here](http://icode4.coffee/files/Prometheus/Prometheus_0.12.13.447_PreAlpha.zip). Upon running you may be prompted to download an updated version, should you accept the latest version will be downloaded and installed automatically.

## Notes
This build is still very rough around the edges and you will encounter issues while using it. This is a "debug" build that has not been optimized and will most likely perform poorly (low FPS, etc). This is done intentionally so that extra debugging information can be exposed via exception/assert dialogs when issues or crashes occur.

Functionality related to importing MCC tags is not available in the alpha builds. MCC BSP imports still need some additional work for shader conversions but will be available soon!

## How to Use
I've put together some really half-assed videos that cover how to setup and use Prometheus which can be found in the following [youtube playlist](https://www.youtube.com/playlist?list=PLBOX21CcPFvKOpEI89GYJ-YF7TeA-bpte). I highly recommend watching these videos at least once to get familiar with how to use and navigate around Prometheus. Note that these videos were made for the pre-alpha testers before the alpha build was made public. They are very rough and I will look into recording newer more refined versions sometime soon.

## Questions/Help
If you have questions or need help using Prometheus you can join the [Remnant Mods discord](https://discord.gg/HwjyBRMNnK) server and ask in the Prometheus channel.

## Reporting Bugs
Before creating a bug report make sure you're on the most recent version and check the [issues](https://github.com/grimdoomer/Prometheus-Alpha/issues) section to see if your issue/bug has already been reported. It would also be a good idea to check the [Known Issues](https://github.com/grimdoomer/Prometheus-Alpha/issues/1) page to see if it contains the issue/bug you're experiencing.

When reporting a new issue/bug please try to include as much detail as possible such as:
- Prometheus version number, ex: 0.8.5.49.
- Steps taken that led to the issue/bug, ex:
  ```
  1. Open 'scenarios\multi\ascension\ascension.scenario' in the bsp view.
  2. Click the spawn transformation tool, enable machine spawns.
  3. Select one of the 'antenna' machine spawns.
  4. Right click the spawn and select edit.
  5. After the tag editor opens right click the spawn again and click delete.
  6. The spawn has now been deleted but the tag editor is still open and can edit fields.
  ```
- If possible include screenshots that may help illustrate and show the issue/bug (these can be copy pasted into github without needing to upload elsewhere).
- If an exception or assert dialog was shown please screenshot and if possible copy ALL of the exception info into the issue report (you can format the exception info into a code block using [triple backticks](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code)).

## Attribution
Prometheus uses icons made by Freepik, Pixel perfect, Uniconlabs, Roundicons, Dave Gandy, Muhammad_Usman, Royyan Wijaya, Dimitry Miroliubov, vectaicon, and Good Ware from [www.flaticon.com](www.flaticon.com).
