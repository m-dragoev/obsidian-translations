# Translate Obsidian

Help translate Obsidian into your language.

## Add a new language

To add a new language, follow these steps:

1. Copy all of the content of the raw `en.json`: https://raw.githubusercontent.com/obsidianmd/obsidian-translations/master/en.json
2. Paste into here: https://github.com/obsidianmd/obsidian-translations/new/master
3. Translate some strings to your language
4. Find the language code of the language you're contributing: https://www.wikiwand.com/en/List_of_ISO_639-1_codes
5. Name the new file "[language code].json" and submit

## Staying up-to-date

Merge conflicts are nasty. They happen when you're translating an outdated version of the template, part of which might have been translated by someone else. To prevent this, try to fork our repository right before you translate.

If you want to do multiple translation pull requests, before doing work each time, use the "Compare" UI on your own fork to pull in all the newest changes from `obsidianmd:master` first by creating a pull request on your own repository and merge it in yourself, so that your own copy is up-to-update.

## Submit changes

To translate, [fork this repo](https://guides.github.com/activities/forking/) and edit the JSON file of your language. After that, [submit a pull request](https://guides.github.com/activities/forking/).

Note that you don't have to clone your fork to make the edits; you can do everything on GitHub's web UI. Simply open a file in your own forked repo and click on the pencil icon to start editing.

## Translating

The translation JSON file consists of key-value pairs. The key should give you a good idea of where the text is in the app.

To translate, simply edit the value. For example, let's say you see

```json
"plugin": "Plugin"
```

Simply change it to:

```json
"plugin": "pLU9IN"
```

where "pLU9IN" is the phrase "plugin" in the target language. I'm using leetspeak as an example here.

If you encounter something like

```json
"label-welcome": "Welcome, {{name}}!"
```

leave the `{{name}}` part alone and do not translate it. "name" is not part of the text and will be replaced by the appropriate value when the app runs.

## Existing languages

Here is a table of language code to language name, in alphabetical order. These languages have their template files ready, but are not necessarily ready to be used in the app.

| Language code | Language name | Native name | Status |
| --- | --- | --- | :---: |
| `en` (default) | English | English | ✅ |
| `af` | Afrikaans | Afrikaans | 🚧 |
| `am` | Amharic |  አማርኛ | ✅ |
| `ar` | Arabic | العربية | 🚧 |
| `eu` | Basque | Euskara | 🚧 |
| `be` | Belarusian | беларуская мова | 🚧 |
| `bg` | Bulgarian | български език | 🚧 |
| `bn` | Bengali | বাংলা | 🚧 |
| `ca` | Catalan | català | 🚧 |
| `cs` | Czech | čeština | ✅ |
| `da` | Danish | Dansk | ✅ |
| `de` | German | Deutsch | ✅ |
| `el` | Greek | Ελληνικά | 🚧 |
| `eo` | Esperanto | Esperanto | 🚧 |
| `es` | Spanish | Español | ✅ |
| `fa` | Persian | فارسی | ✅ |
| `fi-fi` | Finnish | suomi | 🚧 |
| `fr` | French | français | ✅ |
| `gl` | Galician  | Galego | 🚧 |
| `he` | Hebrew  | עברית 🇮🇱 | 🚧 |
| `hi` | Hindi | हिन्दी | 🚧 |
| `hu` | Hungarian | Magyar nyelv | 🚧 |
| `id` | Indonesian | Bahasa Indonesia | ✅ |
| `it` | Italian | Italiano | ✅ |
| `ja` | Japanese | 日本語 | ✅ |
| `ko` | Korean | 한국어 | ✅ |
| `lv` | Latvian | Latviešu valoda | 🚧 |
| `ml` | Malayalam | മലയാളം | 🚧 |
| `ms` | Malay | Bahasa Melayu | 🚧 |
| `nl` | Dutch | Nederlands | ✅ |
| `no` | Norwegian | Norsk | ✅ |
| `oc` | Occitan | Occitan | 🚧 |
| `pl` | Polish | język polski | ✅ |
| `pt` | Portuguese | Português | ✅ |
| `pt-BR` | Brazilian Portuguese | Portugues do Brasil | ✅ |
| `ro` | Romanian | Română | 🚧 |
| `ru` | Russian | Русский | ✅ |
| `sr` | Serbian | српски језик | 🚧 |
| `se` | Swedish | Svenska | 🚧 |
| `sk` | Slovak | Slovenčina | 🚧 |
| `sq` | Albanian | Shqip | ✅ |
| `ta` | Tamil | தமிழ் | 🚧 |
| `te` | Telugu | తెలుగు | 🚧 |
| `th` | Thai | ไทย | ✅ |
| `tr` | Turkish | Türkçe | ✅ |
| `uk` | Ukrainian | Українська | 🚧 |
| `ur` | Urdu | اردو | 🚧 |
| `zh` (see note below) | Chinese (Simplified) | 简体中文 | ✅ |
| `zh-TW` | Chinese (Traditional) | 繁體中文 | ✅ |

> Note: the Chinese translation is maintained by Obsidian.zh. If you want to discuss it, please come here: https://github.com/obsidianzh/obsidian-translations.

