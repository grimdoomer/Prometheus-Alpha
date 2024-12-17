# Prometheus-Pre-Alpha
Welcome to the Prometheus Pre-Alpha test! This page contains some useful resources for learning how to use Prometheus, open issues, and how to report new issues.

## Rules
Please keep the existence and all info regarding this alpha test private. The purpose of this pre-alpha test is to get some initial feedback and testing before a public alpha build is released. To keep the element of "surprise" please refrain from posting any information, pictures, videos, or distributing builds of Prometheus to anyone outside of the pre-alpha test.

## Download
The Prometheus Pre-Alpha build can be downloaded [here](http://icode4.coffee/files/Prometheus/Prometheus_PreAlpha.zip). Upon running you may be prompted to download an updated version, should you accept the latest version will be downloaded and installed automatically.

## How to Use
I've put together some really half-assed videos that cover how to setup and use Prometheus which can be found in the following [youtube playlist](https://www.youtube.com/playlist?list=PLBOX21CcPFvKOpEI89GYJ-YF7TeA-bpte). I highly recommend watching these videos at least once to get familiar with how to use and navigate around Prometheus.

## Reporting Bugs
Before creating a bug report make sure you're on the most recent version and check the [issues](https://github.com/grimdoomer/Prometheus-Pre-Alpha/issues) section to see if your issue/bug has already been reported. It would also be a good idea to check the [Known Issues](https://github.com/grimdoomer/Prometheus-Pre-Alpha/issues/1) page to see if it contains the issue/bug you're experiencing.

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
