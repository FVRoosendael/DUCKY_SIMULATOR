# DUCKY_SIMULATOR
Executes your DUCKY SCRIPTS so you can test them before the need to compile them

After simulating the scripts they can be compiled for the following devices:
  https://shop.hak5.org/products/usb-rubber-ducky-deluxe
Payloads can be found at:
  https://github.com/hak5/usbrubberducky-payloads

Currently the following commands are being supported:
see: https://docs.hak5.org/hc/en-us/articles/360010555153-Ducky-Script-the-USB-Rubber-Ducky-language

REM
DEFAULT_DELAY OR DEFAULTDELAY
DELAY
STRING
WINDOWS OR GUI
MENU OR APP
SHIFT
  SHIFT | DELETE, HOME, INSERT, PAGEUP, PAGEDOWN, WINDOWS, GUI, UPARROW, DOWNARROW, LEFTARROW, RIGHTARROW, TAB
ALT
  ALT |END, ESC, ESCAPE, F1…F12, Single Char, SPACE, TAB
CONTROL OR CTRL
  CONTROL | BREAK, PAUSE, F1…F12, ESCAPE, ESC, Single Char | | CTRL | BREAK, PAUSE, F1…F12, ESCAPE, ESC, Single Char
ARROW KEYS
  DOWNARROW or DOWN | | LEFTARROW or LEFT | | RIGHTARROW or RIGHT | | UPARROW or UP
BREAK or PAUSE
CAPSLOCK
DELETE
END
ESC or ESCAPE
HOME
INSERT
NUMLOCK
PAGEUP
PAGEDOWN
PRINTSCREEN
SCROLLOCK
SPACE
TAB
REPEAT

We are still working on the following commands:
   ALT-SHIFT (Input Lanugage Swap)
   CTRL-ALT [key name] (ex: CTRL-ALT DEL)
   CTRL-SHIFT [key name] (ex: CTRL-SHIFT ESC)
   COMMAND | COMMAND [key] (For OSX Users ex: COMMAND SPACE)
   SHIFT [key name] (ex: SHIFT DEL)
   [key name] (anything in the keyboard.properties)
