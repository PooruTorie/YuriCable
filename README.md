# Flipper Zero DCSD Cable

Implementation to use a Flipper-Zero as DCSD-Cable for iPhones

> ![](docs/YuriCableLogo.svg)

## Docs

Here some specs about the protocol used:

* Name: SDQ (IDBUS) developed by Texas Instruments
* Source: [Reversed Protocol](https://nyansatan.github.io/lightning/)

## Flipper Docs

[Flipper Docs](https://docs.flipper.net/)

## Pinout Flipper Zero

![](docs/pinout.jpg)

## Pinout Lightning

![](docs/BreakoutPinout.jpg)
![](docs/Connector.jpg)

### Build

#### Build-Tool

```shell
python -m pip install --upgrade ufbt
```

#### Update Firmware
+ Download Update

```shell
ufbt update --channel=release
```

+ Upload to Flipper

```shell
ufbt flash_usb
```

#### Build

Navigiere in das Rootverzeichnis der App und führe dort nach installation von ufbt folgenden Befehl aus:

```shell
ufbt
```

Die `.fap`-Datei liegt dann im `./dist`-Ordner

#### Auto Launch

```shell
ufbt launch
```

#### UFBT

* Repo:  [UFBT GitHub](https://github.com/flipperdevices/flipperzero-ufbt)
* Docs:  [UFBT DOCS](https://github.com/flipperdevices/flipperzero-ufbt/blob/dev/README.md)

##### Raspberry Pi Pico Implementation

* [Tamarin Firmware](https://github.com/stacksmashing/tamarin-firmware)
