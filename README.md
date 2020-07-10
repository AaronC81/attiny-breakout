# ATtiny Breakout

This is a little breakout board for easy programming of DIP ATtiny25/45/85 chips on a breadboard.

![Assembled board](img/assembled.jpg)
![Bare, unassembled board](img/bare.jpg)
![Assembled board with programmer connected, slotted into a breadboard populated with an LED](img/use.jpg)

(I got mine fabricated by [JLC](https://jlcpcb.com/), which worked out at about £5.50 for five boards, including delivery.)

It has a 6-pin ISP header for programming, so you'll need an AVR programmer. It also passes the ATtiny's pins through headers on the bottom of the board; this means you can plug it straight into a breadboard, and once you're done programming your ATtiny, simply remove the breakout and replace it with the lone chip.

It's been tested with an ATtiny85 (but should work on 25 and 45 too) and a Pololu USB AVR Programmer.

## Creating Gerbers

This repo contains all the KiCad files you should need. Open up the project in KiCad and build gerbers as required for your fabricator of choice!