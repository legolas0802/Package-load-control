# Package-load-control
Home assistant package that prevents meter detachment

# Requirements:

- Home Assistant version 2021.4 or later
- Configured packages, possibly you can follow our [Guide](https://hassiohelp.eu/2018/11/30/package-configurazione/)
- A sensor that reads the instantaneous power taken from the meter such as [pzem](https://hassiohelp.eu/2019/01/02/consumi-pzem/) or [Shelly EM](https://hassiohelp.eu/2020/01/13/shelly-em/)

# Installation:

- copy the "controllo_carichi.yaml" file into the Home Assistant package folder
- Compile your "secrets.yaml" file as the example

# My Lovelace Card:
> custom: 
  > - [Lovelace Card Mod](https://github.com/thomasloven/lovelace-card-mod)
  > - [Banner Card](https://github.com/nervetattoo/banner-card)
  > - [Lovelace Paper Buttons Row](https://github.com/jcwillox/lovelace-paper-buttons-row)
  > - [Custom Hui Element](https://github.com/thomasloven/lovelace-hui-element)
