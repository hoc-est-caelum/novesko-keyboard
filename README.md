# Novesko keyboard

A [Keyman](https://keyman.com/) keyboard for typing **Novesko**, a constructed language written in a 29-letter Cyrillic alphabet. Full reference grammar: <https://somniacaeli.wordpress.com/>.

## Install

1. Install Keyman (free) for your platform from <https://keyman.com/>.
2. Download [`build/novesko.kmp`](build/novesko.kmp) and open it; Keyman installs the keyboard.

Works on Windows, macOS, Linux, Android and iOS (the package includes a touch layout for phones and tablets).

## Layout

On a physical keyboard the letters sit on the QWERTY key of their nearest Latin sound where there is one, and on Q, W, [, ; and ' otherwise:

| QWERTY keys             | Novesko letters        |
|-------------------------|------------------------|
| Q W E R T Y U I O P [   | џ ў е р т й у и о п ѕ  |
| A S D F G H J K L ; '   | а с д ф г һ ж к л ч ш  |
| Z X C V B N M           | з х ц в б н м          |

Shift gives capitals; Caps Lock works on every letter key; digits and punctuation pass through from the underlying layout. **AltGr + vowel** types the vowel with an acute accent (the stress mark used in adapted names): AltGr+E → е́, AltGr+Shift+E → Е́. On touch devices, long-press the vowel.

## Build from source

Open `novesko.kpj` in the free [Keyman Developer](https://keyman.com/developer/) and compile; the keyboard source is `source/novesko.kmn` and the touch layout `source/novesko.keyman-touch-layout`.

## License

See [LICENSE.md](LICENSE.md).
