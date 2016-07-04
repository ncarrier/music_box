# Music Box

Simple music player shell script, controlled by gpio buttons.

## Description

This script is the base software of a toy I'm building for my 2 year old son,
which consists in a raspberry pi playing music through a little amplifier /
speaker, with 4 buttons for control wired on in GPIOs and four colored leds for
visualisation. A phone power bank provides the power supply.

The shell scripts polls regularly the buttons' state and controls the leds via
sysfs.

Music is played with sox' play command.

The aim is to have something really simple, allowing to choose the songs, but
still sufficiently rugged to survive being manipulated by small hands.

## State of the project

The software is functional, even if very basic and not-so-clean.

The electronics are functional as a prototype and I'm working to transform it in
the real thing.

The hardware has not been started yet, conception is still ongoing.
