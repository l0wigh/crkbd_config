# Corne V4 Layout

This repo contain my layout(s) for AZERTY Coding with the Corne keyboard. Using VIAL to flash them

Currently using the **V3.4**. Might change in the future

## What compose this layout

There is 4 main layers :
- Default layer containing letters. Specials letters are accessed with tap dancing
- Coding layer containing most (if not all) the characters that are used in source code
    - They are mostly placed in a symetric way for better hands coordination.
- Numerical layer containing numbers and an utility variant of the same key with Shift being pressed
- Functions layer which contains FN keys, arrows, and some keyboard RGB configuration

## How to swap from layer to layer

In the V2 Layers are placed in a circular way.

```
0 <-> 1 <-> 2 <-> 0
```

While in the V3 the left layer key is used to reset the layers and go back to the default one.

```
0 -> 1 -> 2 -> 0
0 -> 1 -> 0 -> 1 -> 2
```

The V4 layout is pretty much a mix of the V3 and the V2. I simply added a reset combo that works on any layer. Just press left and right layer key and it goes back to the layer 0.
It's a safer solution for the V2 and more efficient solution for the V3.

## Color changing based on layout

This is really basic. It works by using macros that will change the Hue value.

So it's not a fixed color that you will get. It's purely based on what is the default color at the time. Also it only works in static color mode.

Currently my setup is like this :
- Layer 0 : Red
- Layer 1 : Yellow
- Layer 2 : Blue

If you put orange as a default color you'll get :
- Layer 0 : Orange
- Layer 1 : Green
- Layer 2 : Purple

## Why you use temporary layout toggle only on one layer

Since you most of the time will type more than one key from layers, holding a key when typing isn't really confortable. The only layer that I accept to hold is the fourth one since it's used for a short period of time and that it's only functions keys.

## Will this change in the future ?

I might tweak how I use the keyboard in the future. I'm still thinking about other ways to use the layers in a more optimal way or a safer way. If massive changes happens I'll increment the major version of the keyboard. The README will be changed according to what I'm using at the time. Use the commit history to see how to use older version of the layout.

## What is the Morpho layout that is in this repo ?

It's just me testing some strange stuff that can be done with the software.

It's the same layout that the V2, but with a different way to work in mind. Read the MORPHO.md to know more.

## How versioning works

Every major number changes means that I use a new method to play with layers.
Minor ones means that I fix some letters and do some little tweaks.

## Fix History

- V3.4
  - Adding macros to also change colors based on the layer im in (only for fixed layer, the fourth one isn't affected)
- V4.3
  - Same fixes as the V3.3
  - Adding tap dance for caps lock on the Rshift key since V3 uses the reset combo for caps lock
- V3.3
  - Fixing tap dance timing for less error
  - Adding dot to number layout for faster ip typing (lol)
- V4.2
  - Adding a reset combo (V3 style) on top of the V2 layer chain system.
- V3.2
  - Reset layer button is now present on the left thumb for less brain damage when I'm lost.
  - The ç tap dance is now hold instead of double tap for easier access and less mistypes.
  - The tap dancing values are now higher for less mistypes when writing in french.
  - Added the û tap dancing
  - Readding some mathematical keys on the numerical layer.
- V2.1
  - Fixing layer 0 for easier use of Fluorite
  - Switching from using LShft to RShft for special keys because of a utility on Windows
- V2.0
  - First proper version of the layout that is now able to be used for coding
- V1.0
  - Just a very basic AZERTY layout
