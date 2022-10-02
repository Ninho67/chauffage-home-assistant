## Home Assistant - Gestion de bout en bout du chauffage

Forked original blueprints to do the following modifications:
* Changed `opening` to `window` to be consistent with existing binary sensors
* Reversed control logic of the switch to heat by turning the switch `off` (instead of `on`)

=== ORIGINAL README ===

This repository contains the files of a post in HACF french forum.

It is the complete implementation of a heating management system for home assistant: 
- Proportional thermostat
- window opening management
- Heating modes (eco, comfort)
- Time zones

Please see https://forum.hacf.fr/t/gestion-de-bout-en-bout-du-chauffage/4897

