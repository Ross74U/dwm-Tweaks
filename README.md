# dwm Tweaks
## patches
- visible border
- full-gap

## completely custom patches
- fullscreen monocle toggle with ```MODKEY + m```
to use bind to ```toggle_auto_nmaster```
- auto master mode (automatically adjust monitor nmaster based on client count
instead of manually adjusting with incnmaster), configurable with masters in
config.h

```c
/* auto_nmaster mappings */
static const int mastermapping[] = {
  1, // nclient=0
  1, // nclient=1
  1, // nclient=2
  2, // nclient=3
  2, // nclient=4
  3, // nclient=5
  // past this just nclients/2
};
```
to use bind to ```toggle_auto_nmaster```
