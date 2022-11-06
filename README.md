# kak-replace-mode

Replace mode for [kakoune](https://github.com/mawww/kakoune). Characters that
you type while in replace mode will replace the character under the cursor.

## Installation

Copy `replace-mode.kak` into your autoload folder, or use a plugin manager.

## Usage

Invoke the `enter-replace-mode` command to enter replace mode, and use escape
to leave it.

Recommended mapping:
```
map global normal "<a-r>" ":enter-replace-mode<ret>"
```

## Contributing

Please send questions, requests, bug reports, and patches to the
[mailing list](https://lists.sr.ht/~raiguard/public-inbox).
