# SAMURAI ZMK KEYMAP

This is a bluetooth-enabled [ZMK firmware](https://zmk.dev/) configuration for:
 - Compatible Hardware: [Corne keyboard (aka crkbd; helidox)](https://github.com/foostan/crkbd)
 - Compatible Microcontroller: [nice!nano v2](https://nicekeyboards.com/nice-view/)
 - (Optional) Compatible Displays: [nice!view](https://nicekeyboards.com/nice-view/)

## Typing Layer

Layer 0 is the default layer, `COL-DH`. You can change the layout at any time by activating a magenta item on the `SYSTEM` layer.

All supported typing layers can be viewed [here](LAYOUTS.md).

![Layer 0](/visual/v6/LAYER0.png)

## Other Layers

![Layer 5](/visual/v6/LAYER5.png)
![Layer 6](/visual/v6/LAYER6.png)
![Layer 7](/visual/v6/LAYER7.png)

## Notes
- Shift Lock is a toggle, not a modifier. It will lock the shift key in the on position until pressed again. Useful for games and applications that require you hold shift for a long duration.
- Num Lock is included for compatibility with some applications. It does not change the behavior of the numpad cluster.
- On the `SYSTEM` layer, the Bootloader and Reset keys will trigger for the side that the button is pressed on.
