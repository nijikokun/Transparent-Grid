# Transparent Grid

A responsive grid system that works for fixed and fluid layouts.
 
Written in Stylus for maximum minimalism, based on Profound Grid.

### Usage

```stylus
@import "grid/transparent"

width     = 100%
margin    = 1%
gutter    = 2%

.some-container
  container()

.some-column
  column(9)

.some-sidebar
  column(3)
  push(9)
```

### License

    DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE Version 2, December 2004
    Copyright (C) 2013 Nijiko Yonskai

    Everyone is permitted to copy and distribute verbatim or modified copies of this license document, and changing it is allowed as long as the name is changed.

    DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION
    0. You just DO WHAT THE FUCK YOU WANT TO.