# zmk-config

Config for [Chocofi](https://github.com/pashutk/chocofi) keyboard with 36 keys inspired by:
- [Seniply](https://stevep99.github.io/seniply/)
- [Wellum](https://github.com/braindefender/wellum)

## Layouts

For English, [Gallium Rowstag](https://github.com/GalileoBlues/Gallium) (Gallium v2) is used, and for Russian I generated my layout with [oxeylyzer](https://github.com/o-x-e-y/oxeylyzer), taking into account the ideas from Wellum 

## Learning layouts

To study the layout, I recommend using:
- [keybr](https://www.keybr.com/) - for memorizing
- [monkeytype](https://monkeytype.com/) - further practice

## Layers

- <kbd>NAV</kbd> for navigation
- <kbd>CLC</kbd> for calculator
- <kbd>SYM</kbd> for symbols
- <kbd>FUN</kbd> for functional keys
- <kbd>GME</kbd> for games

> [!NOTE]
> Each of the layers is activated by [Layer-Tap](https://zmk.dev/docs/keymaps/behaviors/hold-tap#layer-tap), except for the Game layer (activated by [Toggle layer](https://zmk.dev/docs/keymaps/behaviors/layers#toggle-layer))

## Base layer

![](/images/base_layer.png)

Key: ⇥ Tab, ␣ Space, ⌫ Backspace, ⌦ Delete

> The only reason to use separate base layers for Windows and macOS is to open the corresponding navigation layer

Some Russian letters have been moved to use via <kbd>Alt</kbd> + <kbd>Key</kbd> to accommodate everything: 

|       Letter | Combination                   |
| -----------: | :---------------------------- |
| <kbd>Ъ</kbd> | <kbd>Alt</kbd> + <kbd>Ь</kbd> |
| <kbd>Щ</kbd> | <kbd>Alt</kbd> + <kbd>Ш</kbd> |
| <kbd>Ф</kbd> | <kbd>Alt</kbd> + <kbd>.</kbd> |
| <kbd>Э</kbd> | <kbd>Alt</kbd> + <kbd>,</kbd> |
| <kbd>Ё</kbd> | <kbd>Alt</kbd> + <kbd>Е</kbd> |

## Navigation

![](/images/navigation_layer.png)

This layer gives us:
- the most commonly used combinations (copy, paste, undo)
- modifier keys with [Sticky Behavior](https://zmk.dev/docs/keymaps/behaviors/sticky-key)
- switching between Bluetooth profiles (with appropriate select of Windows or macOS layers)
- switching between languages
- toggle Game layer

> [!NOTE]
> Caps Lock activates by pressing <kbd>Shift</kbd> + <kbd>LANG</kbd>

### Windows and macOS differences

- Home row mods are changed to be comfortable with usual combos (<kbd>Ctrl/GUI</kbd> + <kbd>Key</kbd>)
- Most used combos use appropriate combinations
- The combination for changing the language corresponds to the current OS

## Calculator

![](/images/calculator_layer.png)

## Symbols

![](/images/symbols_layer.png)

## F-keys and functions

![](/images/functions_layer.png)

## Game layer

![](/images/game_layer.png)

![](/images/functional_game_layer.png)

- <kbd>W</kbd> and <kbd>S</kbd> keys (as well as the arrow keys) have been shifted for comfortable use
- <kbd>Tab</kbd> and <kbd>Shift</kbd> in familiar places
- <kbd>Esc</kbd> added for pinky key position
- <kbd>Ctrl</kbd> is moved to the thumb for ergonomics
- The most used keys are present, additional keys have been moved to the functional game layer
