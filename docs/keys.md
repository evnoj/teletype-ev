<div class="KeyList">
# Keys

## Global key bindings

These bindings work everywhere.

| `Key`                                | Action                                         |
|--------------------------------------|------------------------------------------------|
| **`<tab>`**                          | change modes, live to edit to pattern and back |
| **`<esc>`**                          | preset read mode, or return to last mode       |
| **`alt-<esc>`**                      | preset write mode                              |
| **`win-<esc>`**                      | clear delays, stack and slews                  |
| **`shift-alt-?`** / **`alt-h`**      | help text, or return to last mode              |
| **`<F1>`** to **`<F8>`**             | run corresponding script                       |
| **`<F9>`**                           | run metro script                               |
| **`<F10>`**                          | run init script                                |
| **`alt-<F1>`** to **`alt-<F8>`**     | edit corresponding script                      |
| **`alt-<F9>`**                       | edit metro script                              |
| **`alt-<F10>`**                      | edit init script                               |
| **`ctrl-<F1>`** to **`ctrl-<F8>`**   | mute/unmute corresponding script               |
| **`ctrl-<F9>`**                      | enable/disable metro script                    |
| **`<numpad-1>`** to **`<numpad-8>`** | run corresponding script                       |
| **`<num lock>`** / **`<F11>`**       | jump to pattern mode                           |
| **`<print screen>`** / **`<F12>`**   | jump to live mode                              |

## Text editing

These bindings work when entering text or code.

In most cases, the clipboard is shared between _live_, _edit_ and the 2 _preset_ modes.

| `Key`                                          | Action                                  |
|------------------------------------------------|-----------------------------------------|
| **`<left>`** / **`ctrl-h`**                    | move cursor left                        |
| **`<right>`** / **`ctrl-l`** / **`ctrl-f`**    | move cursor right                       |
| **`ctrl-<left>`** / **`ctrl-b`** / **`alt-b`** | move left by one word                   |
| **`ctrl-<right>`** / **`ctrl-w`** / **`alt-f`**| move right by one word                  |
| **`<home>`** / **`ctrl-a`**                    | move to beginning of line               |
| **`<end>`** / **`ctrl-e`**                     | move to end of line                     |
| **`<backspace>`**                              | backwards delete one character          |
| **`<delete>`** / **`ctrl-d`**                  | forwards delete one character           |
| **`shift-<backspace>`** / **`ctrl-u`**         | delete from cursor to beginning         |
| **`shift-<delete>`**                           | delete from cursor to end               |
| **`alt-<backspace>`** / **`ctrl-<backspace>`** | delete from cursor to beginning of word |
| **`alt-d`**                                    | delete from cursor to end of word       |
| **`ctrl-x`** / **`alt-x`**             | cut to clipboard                        |
| **`ctrl-c`** / **`alt-c`**             | copy to clipboard                       |
| **`ctrl-v`** / **`alt-v`**             | paste to clipboard                      |

## Live mode

| `Key`                                | Action               |
|--------------------------------------|----------------------|
| **`<down>`** / **`C-n`** / **`C-j`** | history next         |
| **`<up>`** / **`C-p`** / **`C-k`**   | history previous     |
| **`<enter>`**            | execute command          |
| **`~`**                  | toggle variables         |
| **`[`** / **`]`**        | switch to edit mode      |
| **`alt-g`**              | toggle grid visualizer   |
| **`shift-d`**            | live dashboard           |
| **`alt-<arrows>`**       | move grid cursor         |
| **`alt-shift-<arrows>`** | select grid area         |
| **`alt-<space>`**        | emulate grid press       |
| **`alt-/`**              | switch grid pages        |
| **`alt-\`**              | toggle grid control view |
| **`alt-<prt sc>`**       | insert grid x/y/w/h      |

In full grid visualizer mode pressing `alt` is not required.

## Edit mode

In _edit_ mode multiple lines can be selected and used with the clipboard.

| `Key`                             | Action              |
|-----------------------------------|---------------------|
| **`<down>`** / **`C-n`** / **`C-j`** | line down        |
| **`<up>`** / **`C-p`** / **`C-k`**   | line up          |
| **`[`**                 | previous script           |
| **`]`**                 | next script               |
| **`<enter>`**           | enter command             |
| **`shift-<enter>`**     | insert command            |
| **`alt-/`** / **`ctrl-/`** | toggle line comment    |
| **`shift-<up>`**        | expand selection up       |
| **`shift-<down>`**      | expand selection down     |
| **`alt-<delete>`**      | delete selection          |
| **`alt-<up>`**          | move selection up         |
| **`alt-<down>`**        | move selection down       |
| **`ctrl-z`**            | undo (3 levels)           |

## Tracker mode

The tracker mode clipboard is independent of text and code clipboard.

| `Key`                   | Action                                                                                |
|-------------------------|---------------------------------------------------------------------------------------|
| **`<down>`** / **`j`**            | move down                                                                   |
| **`alt-<down>`** / **`ctrl-j`**   | move a page down                                                            |
| **`<up>`** / **`k`**              | move up                                                                     |
| **`alt-<up>`** / **`ctrl-k`**     | move a page up                                                              |
| **`<left>`** / **`h`**            | move left                                                                   |
| **`alt-<left>`** / **`ctrl-h`**   | move to the very left                                                       |
| **`<right>`** / **`l`**           | move right                                                                  |
| **`alt-<right>`** / **`ctrl-l`**  | move to the very right                                                      |
| **`[`**                 | decrement by 1                                                                        |
| **`]`**                 | increment by 1                                                                        |
| **`alt-[`**             | decrement by 1 semitone                                                               |
| **`alt-]`**             | increment by 1 semitone                                                               |
| **`ctrl-[`**            | decrement by 7 semitones                                                              |
| **`ctrl-]`**            | increment by 7 semitones                                                              |
| **`shift-[`**           | decrement by 12 semitones                                                             |
| **`shift-]`**           | increment by 12 semitones                                                             |
| **`alt-<0-9>`**         | increment by `<0-9>` semitones (0=10, 1=11)                                           |
| **`shift-alt-<0-9>`**   | decrement by `<0-9>` semitones  (0=10, 1=11)                                          |
| **`<backspace>`**       | delete a digit                                                                        |
| **`shift-<backspace>`** | delete an entry, shift numbers up                                                     |
| **`<enter>`**           | commit edit (increase length if cursor in position after last entry)                  |
| **`shift-<enter>`**     | commit edit, then duplicate entry and shift downwards (increase length as `<enter>`)  |
| **`alt-x`**             | cut value (n.b. `ctrl-x` not supported)                                               |
| **`alt-c`**             | copy value (n.b. `ctrl-c` not supported)                                              |
| **`alt-v`**             | paste value (n.b. `ctrl-v` not supported)                                             |
| **`shift-alt-v`**       | insert value                                                                          |
| **`shift-l`**           | set length to current position                                                        |
| **`alt-l`**             | go to current length entry                                                            |
| **`shift-s`**           | set start to current position                                                         |
| **`alt-s`**             | go to start entry                                                                     |
| **`shift-e`**           | set end to current position                                                           |
| **`alt-e`**             | go to end entry                                                                       |
| **`-`**                 | negate value                                                                          |
| **`<space>`**           | toggle non-zero to zero, and zero to 1                                                |
| **`0`** to **`9`**      | numeric entry                                                                         |
| **`shift-2`** (`@`)     | toggle turtle display marker (`<`)                                                    |
| **`ctrl-alt`**          | insert knob value scaled to 0..31                                                     |
| **`ctrl-shift`**        | insert knob value scaled to 0..1023                                                   |

## Preset read mode

| `Key`                    | Action      |
|--------------------------|-------------|
| **`<down>`** / **`C-n`** | line down   |
| **`<up>`** / **`C-p`**   | line up     |
| **`<left>`** / **`[`**   | preset down |
| **`<right>`** / **`]`**  | preset up   |
| **`<enter>`**            | load preset |

## Preset write mode

| `Key`                    | Action      |
|--------------------------|-------------|
| **`<down>`** / **`C-n`** | line down   |
| **`<up>`** / **`C-p`**   | line up     |
| **`[`**                  | preset down |
| **`]`**                  | preset up   |
| **`<enter>`**            | enter text  |
| **`shift-<enter>`**      | insert text |
| **`alt-<enter>`**        | save preset |

## Help mode

| `Key`                    | Action          |
|--------------------------|-----------------|
| **`<down>`** / **`C-n`** | line down       |
| **`<up>`** / **`C-p`**   | line up         |
| **`<left>`** / **`[`**   | previous page   |
| **`<right>`** / **`]`**  | next page       |
| **`C-f`** / **`C-s`**    | search forward  |
| **`C-r`**                | search backward |
</div>
