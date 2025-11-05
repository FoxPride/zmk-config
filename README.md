# zmk-config

Config for [Chocofi](https://github.com/pashutk/chocofi) keyboard with 36 keys inspired by:
- [Seniply](https://stevep99.github.io/seniply)
- [urob's config](https://github.com/urob/zmk-config)
- [Wellum](https://github.com/braindefender/wellum)

## Layouts

- English - [Gallium Colstag](https://github.com/GalileoBlues/Gallium)
- Russian - generated with [oxeylyzer](https://github.com/o-x-e-y/oxeylyzer)

## Learning layouts

- [keybr](https://www.keybr.com/) - for memorization
- [monkeytype](https://monkeytype.com/) - for further practice

## Layers

> [!NOTE]
> Each layer is activated by [Layer-Tap](https://zmk.dev/docs/keymaps/behaviors/hold-tap#layer-tap), except for the Game and Mouse layers (activated by [Toggle Layer](https://zmk.dev/docs/keymaps/behaviors/layers#toggle-layer))

Icons legend:
- ↻ [Key Repeat](https://zmk.dev/docs/keymaps/behaviors/key-repeat)
- ␣ Space
- ⌫ Backspace
- ⌦ Delete
- ⇥ Tab
- ⌘ Gui
- ⌥ Alt
- ⌃ Ctrl
- ⇧ Shift

### Base

![](/images/base_layer_win.png)
![](/images/base_layer_mac.png)

#### Highlights
- Base layers are separated for Windows and macOS to support:
	- basic operations (Copy, Paste, Cut, Undo)
	- language switch
	- home-row modifier order 
- Rare letters in the Russian layout have been moved to combos 
- [Timeless](https://zmk.dev/docs/keymaps/behaviors/hold-tap?examples=home_row_mods#custom-hold-tap-examples) home-row mods

### Navigation

![](/images/navigation_layer.png)

#### Highlights
- modifier keys with [Sticky Behavior](https://zmk.dev/docs/keymaps/behaviors/sticky-key)
- Bluetooth profile selection (with corresponding Windows or macOS layer)
- Game/Mouse layer toggle 
- **Delete** for left hand in mouse with keyboard situation

### Calculator

![](/images/calculator_layer.png)

### Symbols

![](/images/symbols_layer.png)

### Functions

![](/images/functions_layer.png)

### Game

![](/images/game_layer.png)

![](/images/alt_game_layer.png)

#### Highlights
- <kbd>W</kbd> and <kbd>S</kbd> keys shifted downward (as well as arrow keys) for more comfortable use
- <kbd>Tab</kbd> and <kbd>Shift</kbd> in their familiar positions
- <kbd>Esc</kbd> added in the pinky position
- <kbd>Ctrl</kbd> moved to the thumb for ergonomics
- The most used keys are present, additional keys have been moved to the alternative game layer

### Mouse

![](/images/mouse_layer.png)
