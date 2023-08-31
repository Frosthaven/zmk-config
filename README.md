# SAMURAI ZMK KEYMAP

This is a bluetooth-enabled [ZMK firmware](https://zmk.dev/) configuration for:
 - Compatible Hardware: [Corne keyboard (aka crkbd; helidox)](https://github.com/foostan/crkbd)
 - Compatible Microcontroller: [nice!nano v2](https://nicekeyboards.com/nice-view/)
 - (Optional) Compatible Displays: [nice!view](https://nicekeyboards.com/nice-view/)

## Layers
Layer 0 is the default layer, `COLE-DH`. This is a ColemakDH layout.

You can change the layout at any time by activating a magenta item on the `SYSTEM` layer. The extra layouts can be viewed [here](LAYOUTS.md).

![Layer 0](/visual/v4/LAYER0.png)
![Layer 5](/visual/v4/LAYER5.png)
![Layer 6](/visual/v4/LAYER6.png)
![Layer 7](/visual/v4/LAYER7.png)

## Notes
- Shift Lock is a toggle, not a modifier. It will lock the shift key in the on position until pressed again. Useful for games and applications that require you hold shift for a long duration.
- Num Lock is included for compatibility with some applications. It does not change the behavior of the numpad cluster.
- On the `SYSTEM` layer, the Bootloader and Reset keys will trigger for the side that the button is pressed on.
