---
status: draft
last_update: 2023-01-20T18:22:00+02:00
revision: "1.0.0"
---

# Ergonomic keyboard layout design
[[media/keyboard-layout.png]]

[keyboard-layout-editor json](media/keyboard-layout.json)

## Motivation and Goals
Create an ergonomic keyboard layout design with the following goals:

1. Split design for ergonomic posture
2. Minimum pinky stress (no weird movements, no double key taps / holds)
3. Proper utilization of thumb fingers
4. Optimized for:
    1. Programming (mainly in `vim`)
    2. Writing in English
    3. Number crunching (accounting)
5. MacOS mainly
6. Not too different from standard keyboard in terms of:
    1. Placement of modifier keys such as `tab`, `shift`, and `backspace`
    2. Arrangement of numbers and symbols rows

## Board, switches, and key caps
* PCB - Corne ([crkbd](https://github.com/foostan/crkbd)) 3x6+3
* Switches - MX hot-swappable
    * Alpha keys (excluding pinky finger), space, and enter keys - Boba U4 tactile 68g - 26 total
    * Pinky alpha keys, and tap-able modifiers - Boba U4 tactile 62g - 10 total
    * Pinky and thumb hold-able modifiers - Boba gum 62g linear - 6 total
* Key caps - SA Profile, blanks
    * Q Row - R3 1U - 12 total
    * A Row - R2 1U - 12 total
    * Z Row - R1 1U - 12 total
    * Thumb Row
        * R1 1U - 4 total
        * R1 1.25U / 1.5U - 2 total

## Layout
Colemak Mod DH. 3 Layers - base, lower, raise

### Base layer
Optimized for writing. Contains alpha keys, punctuation (dot and comma), quotes (single and double) as well as question
mark. Exclamation mark is on a layer. It's not great, but it's behind shift on a regular keyboard as well.
The only problem is that dash (`-`) is not there and is behind a layer.

#### Dual shift
Dual shift for proper capitalization by the opposite hand. Both shifts act as a shift on hold, and permanent caps lock
on double tap.

#### Escape key
Standalone caps lock key is removed in favor of a dual function key: `esc` on tap, MacOS option (`⌥`) on hold.

### Raise layer
Optimized for numbers and symbols. Contain standard number row on home row, and standard symbol row above the number
row. Have dedicated math symbols such as addition, subtraction, division, and equality. Also contains dedicated delete
key instead of backspace.

### Lower layer
Optimized for programming. Contains `vim` style navigation on `mnei` (to retain `hjkl` muscle memory), as well as coding
symbols like pipe (`|`), tilde (`~`) is located on `tab` as in many 60% keyboards, backtick (`\``) on `Z`, as well as curly braces (`{}`) and square brackets
(`[]`) on dedicated index fingers as they are used widely.

The pipe and backslash are reversed from traditional keyboard. Pipe is default, while backslash is under shift.

Audio controls are under the left hand home row, for fast play/pause and navigation.

## What's missing?
* RGB controls
* F keys
* `PgUp`, `PgDown`, `Home`, and `End` keys
* Dedicated `Hyper` key
* Dedicated mouse keys
* `Ctrl` key on a layer to allow `Command+Option+Control` style shortcuts (might be solved with Hyper key)

## Acknowledgements
This layout was created for my needs. I'll continue to optimize it to suit my needs. It might not be suited for you.
Feel free to adopt and modify it according to your needs. If you find a better layout, I'd appreciate if you will share it
with me as well [contact[at]yieldcode.blog](mailto:contact@yieldcode.blog).
