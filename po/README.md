# Translating AppManager

## How to Contribute Translations

1. **Edit an existing translation**: Find the relevant `.po` file for your language and submit a PR with your improvements.
2. **Add a new language**: Use `app-manager.pot` as a template, save it as `po/xx.po` (where `xx` is your language code), translate the strings, and create a PR.

## Translation Status

| Language | Code | Status |
| -------- | ---- | ------ |
| Arabic | ar | 0% |
| German | de | 67% |
| Greek | el | 0% |
| Spanish | es | 80% |
| Estonian | et | 67% |
| Finnish | fi | 67% |
| French | fr | 100% |
| Italian | it | 67% |
| Japanese | ja | 67% |
| Kazakh | kk | 90% |
| Korean | ko | 0% |
| Lithuanian | lt | 67% |
| Latvian | lv | 67% |
| Norwegian Bokmål | nb | 67% |
| Dutch | nl | 90% |
| Polish | pl | 0% |
| Portuguese (Brazil) | pt_BR | 100% |
| Swedish | sv | 67% |
| Vietnamese | vi | 100% |
| Chinese (Simplified) | zh_CN | 67% |

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
