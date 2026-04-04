# DAR_KEY_PAD
The Dumb As Rocks Key Pad for the 8BitDo retro keyboard. A single 8 button keypad equivalent to 4 8BitDo Dual Super Buttons. Probably usable elsewhere, but also just as probable that it's a bad idea.

<img width="502" height="735" alt="image" src="https://github.com/user-attachments/assets/cfabda24-642b-4bf9-bc13-a514b283d6ea" />

# SUMMARY
The Dumb As Rocks (DAR) Key Pad is a single-sided integrated replacement of 4 8BitDo Dual Super Buttons. There are absolutely no brains on board. Only 12 passive components, 4 audio cables, and a handful of screws and standoffs are required to use this pad. The absolute minimum of design work has been done on this board. At present, it is designed to be easily manufactured, easily readable, and easily modifyable. With some modification, it is likely possible to CNC mill this keypad on copper clad board.

Should this have been a PCB? No. Boredom is a hell of a thing.

# DETAILS

## THE JACKS
The 8BitDo Retro line of keyboards possess a unique feature. Specifically, the keyboard supports the use of 10 programmable buttons. Two buttons are integrated into the keyboard, and 8 are modular. The modular buttons are coupled up, and bound to individual 3.5mm "audio" jacks on the back of the keyboard. What makes this novel is that different devices can be attached to these ports juch as joysticks. The rest is handled in OEM software.

Annoyingly, each jack isn't indexed by number, but by letters frequently found on a standard controller. A, B, X, and Y. This gets even more confusing when the peripherals are attached.

## THE BUTTONS
The pinout of the 3.5mm jack/plug is:

Sleeve: VCC

Ring: A button

Tip: B button

The Super Buttons are the perfect example of a minimum viable product stuffed into a nice case (affectionately). The only components in a Super Button are cable, a switch, a carrier PCB (sometimes), and maybe a socket. All electronics to handle the button, such as pull down resistors, debouncing, and diodes are integrated into the keyboard itself. This makes the peripherals inexpensive. More importantly, this makes them easy to build yourself.

Most peripherals, like the jacks, are indexed in the order A, B, X, and Y. What makes this frustrating is that the jack the peripheral is attached to is indexed in the exact same way. Meaning an owner of a fully expanded 8BitDo Retro keyboard will have situations like "Programming A on X" or "Trobleshooting B on B".

On the DAR KEY PAD, the format [JACK].[INPUT] is used when labeleing the buttons to minimise confusion. Confusion will still likely occur (I'm not stupid, you're stupid!).

## THE PARTS
Aside from the PCB, only the following parts are required to assemble and use the DAR KEY PAD on an 8BitDo Retro keyboard:

4x SJ1-3523N or compatible (ex. uxcell a12062600ux0366)

8x Cherry MX Compatible Keyswitch

8x Cherry-style 1x1 keycaps

4x 3.5mm aux cables, 1.5 ft. or longer

4x M2 machine screws

4x M2 standoffs
