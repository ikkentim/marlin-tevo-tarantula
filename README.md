# marlin-tevo-tarantula
My Marlin Tevo Tarantula config. Based roughly on Jim Brown's config, tweaked for my setup.

## Software
- Marlin 2.1.x
- OctoPrint 1.9.0 (OctoPi 1.0.0)

## Hardware
- Tevo Tarantula
- Dual Z motors
- Replaced plastic stuctural parts with laser cut metal parts
- Raspberry Pi 3b
- BLTouch

## Upgrades
Printable upgrades I use
- [BLTouch mount for Tevo Tarantula](https://www.thingiverse.com/thing:2673200)
- [Tevo Tarantula bed level knob](https://www.thingiverse.com/thing:2330042)
- [Adjustable Belt Tensioner/Tightener and Belt Tie (Tevo Tarantula)](https://www.thingiverse.com/thing:1780636)
-[TEVO Tarantula Fan Duct](https://www.thingiverse.com/thing:2284224)

## Stepsticks
Some of my stepsticks are DRV8825. These have a 0.1 Ohm resistor.
The motors are 425HDC4043Z-22B. These are rated 1.5A.
The Vref has been set to 1.0V

```
Vref = I * 8 * Rsense

Rsense = 0.1 Ohm
I = 1.5 * 80% = ~1.25A (80% of max current)
Vref = 1.25 * 8 * 0.1 = 1.0V
```
