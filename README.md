# zmk-config

Config for the [Chocofi](https://github.com/pashutk/chocofi) keyboard (36 keys), inspired by:
- [Seniply](https://stevep99.github.io/seniply)
- [urob's config](https://github.com/urob/zmk-config)
- [Wellum](https://github.com/braindefender/wellum)

## Layouts

- English - the [Gallium](https://github.com/GalileoBlues/Gallium) (Colstag) layout
- Russian - generated with [oxeylyzer](https://github.com/o-x-e-y/oxeylyzer)

## Learning layouts

- [keybr](https://www.keybr.com/) - learning
- [monkeytype](https://monkeytype.com/) - practice

## Layers

> [!NOTE]
> Each layer is activated by [Layer-Tap](https://zmk.dev/docs/keymaps/behaviors/hold-tap#layer-tap), except the Game layer which uses [Toggle Layer](https://zmk.dev/docs/keymaps/behaviors/layers#toggle-layer)

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
- Game layer toggle 
- **Delete** accessible from the left hand during mouse + keyboard use

### Calculator

![](/images/calculator_layer.png)

#### Highlights
- Sticky **Meh** (Ctrl+Alt+Shift) and **Hyper** (Ctrl+Alt+Shift+GUI) modifier keys

### Symbols

![](/images/symbols_layer.png)

### Functions

![](/images/functions_layer.png)

### Game

![](/images/game_layer.png)

![](/images/alt_game_layer.png)

#### Highlights
- <kbd>W</kbd> and <kbd>S</kbd> keys moved down one row (arrow keys follow the same shift)
- <kbd>Tab</kbd> and <kbd>Shift</kbd> in their familiar positions
- <kbd>Esc</kbd> added in the pinky position
- <kbd>Ctrl</kbd> moved to the thumb for ergonomics
- Frequently used keys on the main layer; less common ones moved to the alternate game layer

### Tiling

![](/images/tiling_manager_layer.png)

#### Highlights
- **Meh** (Ctrl+Alt+Shift) keys that convert to **Hyper** (Ctrl+Alt+Shift+GUI) when combined with Right Shift, using [mod-morph](https://zmk.dev/docs/keymaps/behaviors/mod-morph)
