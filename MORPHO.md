# Corne V4 Morpho Layout

The Morpho layout is based on the concept of completely separeted keyboard

## How it works ?

Layers are activated only on left or right side.

When both are active, you access the numerical layer.

```
<0> --- <0> : Default
<1> --- <0> : Left is active
<2> --- <2> : Both are active
<0> --- <1> : Left is deactivated
<0> --- <0> : Right is deactivated
```

## Obvious issues with this layout

If I want to do an arrow (->) I need to do this : 

```
Left Layer Active
"-"
Left Layer Inactive
Right Layer Active
">"
Right Layer Inactive
```

Which is too complicated for nothing.

Also, without a full layer reset, You can loose yourself pretty quickly (especially when blind typing your password).

The only time that I felt like it was useful is with numerical stuff. I was blazing fast when typing stuff like "2.0" for example.

## Version History

- V1.0
  - First working concept of the morpho layout