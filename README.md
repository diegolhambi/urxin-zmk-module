# Urxin ZMK Module

This repository contains the shield files for the [Urxin](https://github.com/diegolhambi/urxin).

## Usage

Edit your west.yml file found in your zmk-config's config directory following the example below.

```yaml
manifest:
  remotes:
    - name: zmkfirmware
      url-base: https://github.com/zmkfirmware
    - name: diegolhambi
      url-base: https://github.com/diegolhambi
  projects:
    - name: zmk
      remote: zmkfirmware
      revision: main
      import: app/west.yml
    - name: zmk-keyboard-urxin
      remote: diegolhambi
      revision: main
  self:
    path: config

```
