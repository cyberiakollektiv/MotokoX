# Roadmap
Somewhere I can keep my thoughts about what I'm currently working on.

## Main Menu
Currently the main menu is controlled via using the left/right stick as a mouse and selecting the menu options. It's fine, but it makes it feel like a PC game running on a console as opposed to a PC game properly ported to a console, so menu code should ideally be rewritten at some point to handle similarly to the PS2 version's menu.

## Controls
As above, the controls are essentially keyboard mappings bound to controller buttons, which is fine for the most part, but does lead to moments where it feels more like a PC game running on a console as opposed to a properly ported game. Button prompts still currently show the keyboard button name, which should be changed to controller icons (best) or controller-specific text (fine, and also the way the PS2 version does it).

## Hardware Renderer
Currently, the game runs using a basic software renderer. This is fine ensuring everything else works as expected, but is completely unplayable outside of testing. There are two options here, modifying the existing OpenGL renderer to be compatible with pbGL, or creating an NV2A-specific renderer from scratch.
