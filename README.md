# SAMURAI ZMK KEYMAP

This is a bluetooth-enabled [ZMK firmware](https://zmk.dev/) configuration for:
 - Compatible Hardware: [Corne keyboard](https://github.com/foostan/crkbd)
 - Compatible Microcontroller: [nice!nano v2](https://nicekeyboards.com/nice-view/)
 - (Optional) Compatible Displays: [nice!view](https://nicekeyboards.com/nice-view/) (Uses PIN 008 on the MC)

## Typing Layer

- Layer 0 - `COL-DH` - is the default typing layer. It is a Colemak ModDH layout.
- You can change the layout by clicking an alternate one on the right side of the `SYSTEM` layer.
- All supported typing layer layouts can be viewed [here](LAYOUTS.md).

![Layer 0](/visual/v8/LAYER0.png)

## Other Layers

![Layer 5](/visual/v8/LAYER5.png)
![Layer 6](/visual/v8/LAYER6.png)
![Layer 7](/visual/v8/LAYER7.png)

## Notes
- Shift Lock is a toggle, not a modifier. It will lock the shift key in the on position until pressed again. Useful for games and applications that require you hold shift for a long duration.
- Num Lock is included for compatibility with some applications. It does not change the behavior of the numpad cluster.
- The Bootloader and Reset keys will trigger for the side that the button is pressed on.
