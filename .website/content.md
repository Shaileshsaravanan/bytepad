bytepad is a small, simple, fully customizable macropad built around the seeed studio xiao rp2040. it is designed to be easy to build, easy to understand, and useful in a lot of different setups — shortcuts, media control, small tools, or just something satisfying to press.

## why this exists

i wanted something compact and functional without turning into a complicated keyboard project. bytepad sits in that space: minimal hardware, simple firmware, still powerful enough to be genuinely useful.

## what it includes

• 9 programmable keys  
• Kailh Choc switches with hotswap sockets  
• rotary encoder for scrolling, volume, or whatever you map it to  
• Seeed Studio XIAO RP2040 as the controller  
• usb-c  
• runs [kmk](https://kmkfw.io/) so the firmware stays approachable and python-based  

everything is meant to be diy-friendly and understandable.

## build

the repository includes:

• pcb design  
• schematic  
• cad  
• firmware  
• production files  

so the whole project can be built end-to-end.

## firmware

bytepad runs on **[kmk](https://kmkfw.io/)**, which keeps configuration simple and flexible using python. layouts, keymaps, encoder behavior, and macros can all be edited cleanly.

## current state

hardware is designed, firmware direction is clear, and bytepad is at a point where it is practical to build and use. further refinements will likely focus on firmware polish and ergonomics.