# Translating AppManager

## How to Contribute Translations

1. **Edit an existing translation**: Find the relevant `.po` file for your language and submit a PR with your improvements.
2. **Add a new language**: Use `app-manager.pot` as a template, save it as `po/xx.po` (where `xx` is your language code), translate the strings, and create a PR.

## Translation Status

| Language | Code | Status |
| -------- | ---- | ------ |
| Arabic | ar | 99.7% (298/299) |
| German | de | 99.7% (298/299) |
| Greek | el | 99.7% (298/299) |
| Spanish | es | 99.7% (298/299) |
| Estonian | et | 99.7% (298/299) |
| Finnish | fi | 99.7% (298/299) |
| French | fr | 100% (299/299) |
| Irish | ga | 100% (299/299) |
| Italian | it | 99.7% (298/299) |
| Japanese | ja | 99.7% (298/299) |
| Kazakh | kk | 99.7% (298/299) |
| Korean | ko | 99.7% (298/299) |
| Lithuanian | lt | 99.7% (298/299) |
| Latvian | lv | 100% (299/299) |
| Norwegian Bokmål | nb | 99.7% (298/299) |
| Dutch | nl | 99.7% (298/299) |
| Polish | pl | 99.7% (298/299) |
| Portuguese (Brazil) | pt_BR | 99.7% (298/299) |
| Swedish | sv | 99.7% (298/299) |
| Ukrainian | uk | 99.7% (298/299) |
| Vietnamese | vi | 99.7% (298/299) |
| Chinese (Simplified) | zh_CN | 99.7% (298/299) |

## Note

> Some translations are machine-generated and may contain mistakes. Native speakers are welcome to review and improve them!

## Testing Translations Locally

After building with meson, translations are compiled automatically. To test:

```bash
meson setup build --prefix=$HOME/.local
meson compile -C build
meson install -C build
```

Then run the app with a specific locale:

```bash
LANGUAGE=de app-manager
```

## Further Reading

- [GNU gettext Manual](https://www.gnu.org/software/gettext/manual/gettext.html)
- [Vala i18n documentation](https://wiki.gnome.org/Projects/Vala/TranslationSample)
