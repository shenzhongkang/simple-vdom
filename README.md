# Building a Simple Virtual DOM from Scratch

> Referring to [This Article](https://dev.to/ycmjason/building-a-simple-virtual-dom-from-scratch-3d05).

## Side Notes
- `$` - when referring to real doms, e.g. `$div`, `$el`, `$app`
- `v` - when referring to virtual doms, e.g. `vDiv`, `vEl`, `vApp`

## Result
Our app now will generate a random number `n` between 0 and 9 and display `n` cat photos on the page. If you go into the dev tools, you will see how we are "intelligently" inserting and removing `<img>` depending on `n`.