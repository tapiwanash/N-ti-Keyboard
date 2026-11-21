# N'ti keyboard

A virtual keyboard for typing N'ti text in your web browser. It is a single HTML file with the **TSG N'ti** font built in, so it works offline, needs no installation, and sends nothing over the internet.

## Try it

**[Open the keyboard](https://YOUR-USERNAME.github.io/nti-keyboard/)**

Or download `nti-keyboard.html` and double-click it to open it in any current browser (Chrome, Edge, Firefox or Safari).

## How to type

You can tap the keys on the screen, type on your computer keyboard, or mix both.

- **Bases and marks are separate keys.** Type a vowel, consonant or digit first, then a mark. The font joins them into one glyph automatically.
- **Marks that will join are outlined.** After you type a base, the marks that combine with it are highlighted in teal.
- **Computer keyboard:** the small letter in the corner of each on-screen key shows which key types it. Use the **Key hints** button to show or hide these labels.
- **Copy text** copies everything to the clipboard so you can paste it into other programs.

### Computer keyboard mapping

| Type | Result |
|---|---|
| `a` `u` `i` `e` `o` | ah, ooh, ee, eh, oh |
| `x` `m` `l` `h` `r` `c` `q` `p` `g` `d` `k` `t` `y` `f` `w` `j` `n` `b` `s` | xa, ma, la, ha, ra, cha, qa, pa, ga, da, ka, ta, ya, fa, wa, ja, na, ba, sa |
| `Shift+M` `Shift+N` `Shift+G` | nm, nya, nga |
| `0` to `9` | zero to nine |
| `.` `-` | xupu, gilonde |
| `;` `'` `[` `]` | xansegeye, xanyanqaye, xanxotte, yinduro |
| `Shift+;` `Shift+'` `Shift+[` | xansegeyefutiye, xanyanqayefutiye, xanxottefutiye |
| `\` | yilla |
| `Shift+1` to `Shift+8` | E0D0 to E0D7 |

Keys follow the physical position on a QWERTY keyboard. Combinations with Ctrl, Cmd or Alt are never intercepted, so copy, paste and undo work as usual.

## Using the text elsewhere

The text uses ordinary Unicode characters. A joined glyph is a base followed by a mark, drawn as one shape by the font, so it stays two characters when you paste it. To see the text correctly in another program, install the TSG N'ti font and use a program that applies the font's `ccmp` feature (most current ones do).

## Files

| File | What it is |
|---|---|
| `nti-keyboard.html` | The keyboard (rename to `index.html` to host it with GitHub Pages) |

## License

This project is licensed under the **GNU General Public License**. See the [LICENSE](LICENSE) file for the full text.
