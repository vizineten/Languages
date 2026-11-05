# Vizinet app languages

UI texts of Vizinet apps, one folder per app and one file per language:
`{"English text": "translation"}`. The apps are built with English only and download the
language they need from here. Only texts of the apps' screens are here: no code, no user data.

| Folder | App |
| --- | --- |
| [`worldbuilder/`](worldbuilder) | [Worldbuilder](https://vizinet.dev) |
| [`beliefy/`](beliefy) | Beliefy |

Placeholders like `{name}` stay as they are. Counted nouns (`#place`, Worldbuilder) hold the forms the
language needs, separated by `|`.

The `*.json` files in the root are a copy of `worldbuilder/` for older Worldbuilder versions, which
download from the root. They will be removed once those versions are no longer in use.

Found a mistake? Write to support@vizinet.dev.
