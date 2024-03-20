[dmenu](https://tools.suckless.org/dmenu/) with some patches I use.

Updated to VERSION: 5.3

# Patches  

- XY: add -x and -y options to configure X and Y positions of dmenu. (Adapted from [XYW Patch](https://tools.suckless.org/dmenu/patches/xyw/dmenu-xyw-5.0.diff))  
- Lineheight: add -h option to set minimum dmenu height ([Line Height Patch](https://tools.suckless.org/dmenu/patches/line-height/))  

The patches in the 'patches' directory are supposed to be applied in alphabetical order on top of a clean 5.3 dmenu codebase.  
Alternatively the main branch already has all patches applied.  

# Install
```
make && sudo make install
```
