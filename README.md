![GitHub tag (with filter)](https://img.shields.io/github/v/tag/audiomaster99/SpawnProtection?style=for-the-badge&label=Version) ![GitHub Repo stars](https://img.shields.io/github/stars/audiomaster99/SpawnProtection?style=for-the-badge) ![GitHub all releases](https://img.shields.io/github/downloads/audiomaster99/SpawnProtection/total?style=for-the-badge)

## Features

- Configurable spawn protection
- Render player models transparent
- Timer with progress bar
- CT Only protection (can be enabled in config)

![Protection Timer](https://i.imgur.com/7un6m3r.gif= "Protection Timer")

## Config

```
  "spawn-protection-time": 10, // for how long will player be protected in seconds
  "spawn-prot-center-message": true, //enable center messages
  "spawn-prot-end-announce": true, // enablee announcement when spawn protection ended
  "attacker-center-message": true, // enable warning message for attacker
  "enable-center-html-message": true, // enable timer and progress bar
  "spawn-prot-transparent-model": true, // enable transparent models while protected
  "ct-protection-only": false, // enable protection only for Counter-Terrorists
  "trigger-hurt-compatibility": false // enable protection from trigger_hurt (Disable if you're on windowsOs)
  "ConfigVersion": 4 // dont change!
```

## Dependencies

- [Metamod:Source](https://www.sourcemm.net/downloads.php/?branch=master "Metamod:Source")
- [CounterStrike Sharp](https://github.com/roflmuffin/CounterStrikeSharp "CounterStrike Sharp")

## Installation

- Place plugin contents to **addons/counterstrikesharp/plugins/SpawnProt**
