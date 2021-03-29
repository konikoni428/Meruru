# Meruru改

本家: https://github.com/castaneai/Meruru

A Simple [Mirakurun](https://github.com/Chinachu/Mirakurun)/[mirakc](https://github.com/mirakc/mirakc) Client for Mac OS

![Meruru](Meruru.png)

## Config

The Meruru config file is placed in `~/.config/meruru/config.json`.
Put the Mirakurun HTTP endpoint in `"mirakurunPath"` as follows:

```json
{
  "mirakurunPath": "http://192.168.x.x:40772"
}
```

## Build

- Install [Carthage](https://github.com/Carthage/Carthage)
- Run `carthage bootstrap`

## 本家との違い
- mirakcへの対応
- インターレース解除

## License

[Apache License, Version 2.0](LICENSE)
