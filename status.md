---
author: bee
---

# Decred Translation Status

This page tracks Decred translations that require continuous maintenance, primarily **software translations**. [About](#about) section at the end explains how to use this page. For a list of completed one-off *content translations* please see [the index page](index.md).


## Decrediton

- Decrediton translations are **funded** via the [Translations phase 3 proposal](https://proposals.decred.org/record/7057e0b) until 2022-12-31. [Contact](#contact) @kozel on Matrix for the details.
- Read the [Translating Guide](https://github.com/decred/decrediton/blob/master/app/i18n/community_translators.md) and [contact](#contact) @matheusd on Matrix for more detais.
- Files to translate: [Basic level](https://github.com/decred/decrediton/tree/master/app/i18n/translations), [Advanced level](https://github.com/decred/decrediton/tree/master/app/i18n/docs).
- **Beware**: Basic level translations use English `original.json` file which **may be outdated**! See note \[1\] below. Ask repository maintainers if it's latest and safe to work with.

_Status as of: 2022-10-14_

| Language (Level)         | Release    | EN base \[2\] | Changes | Translators and notes |
|--------------------------|------------|---------------|---------|-----------------------|
| English original.json    | v1.7.5     | [2022-10-12](https://github.com/decred/decrediton/commit/72ade34059391e716675c406712168df17a21b7a) | 72ade34 | Last regen of *intermediary* EN Basic file \[1\] |
| English original.json    | master     | [2022-10-10](https://github.com/decred/decrediton/commit/b6dd4b9f32b5b44a6ec06084984b03fccc9bd6dd) | [#3807](https://github.com/decred/decrediton/pull/3807) | Last regen of *intermediary* EN Basic file \[1\] |
| English (Basic)          | v1.7.5     | [2022-10-12](https://github.com/decred/decrediton/commit/009c9da23a67589ae1c4d27371adeb26ecd4635a) | [#3791](https://github.com/decred/decrediton/pull/3791) | Last change of *real originals* of EN Basic \[1\] |
| English (Basic)          | master     | [2022-09-07](https://github.com/decred/decrediton/commit/78a6a3bd864509dceff2e33c4aa6bbb45a89af1c) | [#3791](https://github.com/decred/decrediton/pull/3791) | Last change of *real originals* of EN Basic \[1\] |
| English (Advanced)       | v1.7.4     | [2022-08-01](https://github.com/decred/decrediton/commit/37829575d8eac147b076cef9c798fa04359b9353) | 3782957 | |
| English (Advanced)       | master     | [2022-08-01](https://github.com/decred/decrediton/commit/76cb05b77abf353329253df358444fd930896a9a) | [#3779](https://github.com/decred/decrediton/pull/3779) | |
| Arabic (Basic)           | v1.7.0-rc1,<br>master | [2021-10-14](https://github.com/decred/decrediton/commit/e2bfe00500c7f21b5b2b8b56713ffe8223999eee) | [#3632](https://github.com/decred/decrediton/pull/3632) | arij, abdulrahman4 |
| Arabic (Advanced)        | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _arij? Transifex?_ } |
| Chinese CN (Basic)       | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _Dominic? Transifex?_ } |
| Chinese CN (Basic)       | master     | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3813](https://github.com/decred/decrediton/pull/3813) | **UNMERGED**, Dominic |
| Chinese CN (Advanced)    | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _Dominic?_ } |
| Chinese HK (Basic)       | v1.6.1     | [2020-12-14](https://github.com/decred/decrediton/commit/4fdf91a283fb108e84ab780d8764ca6f76f82eec) | 8d3b9b2 | smartwojak, based on .po |
| Chinese HK (Basic)       | master     | [2020-12-14](https://github.com/decred/decrediton/commit/4fdf91a283fb108e84ab780d8764ca6f76f82eec) | [#3086](https://github.com/decred/decrediton/pull/3086) | smartwojak, based on .po |
| Chinese HK (Advanced)    | v1.6.1     | [2020-12-14](https://github.com/decred/decrediton/commit/4fdf91a283fb108e84ab780d8764ca6f76f82eec) | [#3086](https://github.com/decred/decrediton/pull/3086) | 8d3b9b2 | smartwojak |
| Chinese HK (Advanced)    | master     | [2020-12-14](https://github.com/decred/decrediton/commit/4fdf91a283fb108e84ab780d8764ca6f76f82eec) | [#3086](https://github.com/decred/decrediton/pull/3086) | smartwojak |
| French (Basic)           | v1.4.0,<br>master | [2018-12-11](https://github.com/decred/decrediton/commit/d5f68b365e2353e719e89e07bc5b509e42f5116c) | [#1875](https://github.com/decred/decrediton/pull/1875) | { _who?_ } |
| French (Basic)           | master     | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3654](https://github.com/decred/decrediton/pull/3654) | **UNMERGED, needs review**, jp |
| French (Advanced)        | v1.4.0,<br>master | [2018-12-11](https://github.com/decred/decrediton/commit/d5f68b365e2353e719e89e07bc5b509e42f5116c) | [#1875](https://github.com/decred/decrediton/pull/1875) | { _who?_ } |
| French (Advanced)        | master     | [2022-01-07](https://github.com/decred/decrediton/commit/2fe22577aea0c71e4183bc0322f49a8687d35da5) | [#3654](https://github.com/decred/decrediton/pull/3654) | **UNMERGED, needs review**, jp |
| German (Basic)           | v1.7.5     | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | b96b7a6 | karamble |
| German (Basic)           | master     | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3798](https://github.com/decred/decrediton/pull/3798) | karamble |
| German (Advanced)        | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/4fdf91a283fb108e84ab780d8764ca6f76f82eec) | [#3088](https://github.com/decred/decrediton/pull/3088) | karamble |
| Greek (Basic)            | master     | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3719](https://github.com/decred/decrediton/pull/3719) | **UNMERGED, needs review**, [Xk9eboF6](https://github.com/Xk9eboF6) |
| Greek (Advanced)         | master     | [2022-03-08](https://github.com/decred/decrediton/commit/ee04c5d79dafd9323a2945d0fc8eda8b896248e9) | [#3719](https://github.com/decred/decrediton/pull/3719) | **UNMERGED, needs review**, [Xk9eboF6](https://github.com/Xk9eboF6) |
| Italian (Basic)          | v1.7.0-rc2 | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | 28c6f61 | teknico, karamble |
| Italian (Basic)          | master     | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3659](https://github.com/decred/decrediton/pull/3659) | teknico, karamble |
| Italian (Advanced)       | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | teknico, karamble |
| Japanese (Basic)         | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _who?_ } |
| Japanese (Advanced)      | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062)| [#3052](https://github.com/decred/decrediton/pull/3052) | { _who?_ } |
| Polish (Basic)           | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _kozel?_ } |
| Polish (Advanced)        | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _kozel?_ } |
| Portuguese BR (Basic)    | v1.7.0-rc1,<br>master | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3619](https://github.com/decred/decrediton/pull/3619) | matheusd, { _others?_ } |
| Portuguese BR (Advanced) | v1.7.0-rc1,<br>master | [2021-12-23](https://github.com/decred/decrediton/commit/bd6cdd70a585423bdc82573b3b2a01daaafd8e72) | [#3619](https://github.com/decred/decrediton/pull/3619) | matheusd, { _others?_ } |
| Spanish (Basic)          | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _francov\_?_ } |
| Spanish (Advanced)       | v1.6.0,<br>master | [2020-12-14](https://github.com/decred/decrediton/commit/c4c6ee3a9a645cef64385243fc1a379b42ac8062) | [#3052](https://github.com/decred/decrediton/pull/3052) | { _francov\_?_ } |

\[1\] Decrediton translations are more complex compared to other projects. There are two sets of files to translate, referred to as [Basic](https://github.com/decred/decrediton/tree/master/app/i18n/translations) and [Advanced](https://github.com/decred/decrediton/tree/master/app/i18n/docs), and they are updated with different workflows. Basic translations are updated in 2 stages. First a developer runs a script to copy all *real original* English strings from many .js and .jsx files into a single file `app/i18n/translations/original.json`. Then translators use this file to update `app/i18n/translations/XXX.json` for their target language. I call the stings in .js and .jsx files "real originals" here because `original.json` is a misleading file name, it is not an original copy that the app loads strings from, it is a derived/generated *intermediate* copy made solely for the translations. A problem with this derived `original.json` file is it always behind the real original strings, so please ask the devs if it's up to date before translating it. Advanced translations are simpler, they are based on Markdown files in the [`app/i18n/docs`](https://github.com/decred/decrediton/tree/master/app/i18n/docs) directory and don't need the regeneration step, so you can pick and translate them at any time.

\[2\] `EN base` for **Basic** translations shows the date of last regeneration of `original.json` that the translation was based on. Decrediton's Basic translations is the only case where intermediate files are translated instead of the real originals (which are hard-coded in .js and .jsx files). It is harder to calculate `EN base` for Basic but it allows to quickly see how old the translation is. `EN base` for **Advanced** translations is the version of [`app/i18n/docs`](https://github.com/decred/decrediton/tree/master/app/i18n/docs) files that were translated (these are real originals and there are no intermediary layers like in Basic).

Historical translators:

- Chinese - guang ([Guang168](https://github.com/Guang168), till v1.4.0)
- French - { _who? (till ?)_ }
- German - { _who? (till ?)_ }
- Italian - { _karamble (till v1.6.0)?_ }
- Japanese - { _who? (till ?)_ }
- Polish - { _who? (till ?)_ }
- Portuguese BR - { _who? (till ?)_ }
- Spanish - { _who? (till ?)_ }


## DCRDEX

- DCRDEX translations are **funded** via the [Translations phase 3 proposal](https://proposals.decred.org/record/7057e0b) until 2022-12-31. [Contact](#contact) @kozel on Matrix for the details. { _Correct?_ }
- Read the [Translating Guide](https://github.com/decred/dcrdex/blob/master/docs/wiki/Localization-and-Translation.md) and [contact](#contact) @chappjc on Matrix for more details.
- Files to translate: [HTML strings](https://github.com/decred/dcrdex/tree/master/client/webserver/locales), [Notification strings](https://github.com/decred/dcrdex/blob/master/client/core/locale_ntfn.go), [JavaScript strings](https://github.com/decred/dcrdex/blob/master/client/webserver/site/src/js/locales.ts)

_Status as of: 2022-10-14_

| Language      | Release    | EN base    | Changes \[3\] | Translators and notes |
|---------------|------------|------------|---------------|-----------------------|
| English       | v0.5.0-rc1 | [2022-07-22](https://github.com/decred/dcrdex/commit/f541eadb4f3a1978cddb86b470c90f844114a0d7) | [#1600](https://github.com/decred/dcrdex/pull/1600) | |
| English       | master     | [2022-10-11](https://github.com/decred/dcrdex/commit/70452f4ffc35225a78d5d84e0d3d4ca18a7dea0e) | [#1840](https://github.com/decred/dcrdex/pull/1840) | |
| Chinese CN    | v0.4.0-rc1 | [2021-09-24](https://github.com/decred/dcrdex/commit/d11f1ce9ea1313e17fdc588d0f3d9f0e9e153444) | [#1207](https://github.com/decred/dcrdex/pull/1207) | Dominic |
| Chinese CN    | master     | [2022-10-12](https://github.com/decred/dcrdex/commit/ba711dcf326f063061b35d1754ecc8a12c2a7668) | [#1871](https://github.com/decred/dcrdex/pull/1871) | Dominic |
| German        | v0.5.3     | [2022-08-19](https://github.com/decred/dcrdex/commit/0dee62f8587b714acf49c322dde781ddd3a32bee) | [#1815](https://github.com/decred/dcrdex/pull/1815) | karamble |
| German        | master     | [2022-09-15](https://github.com/decred/dcrdex/commit/7389105a62b31d9f2937a47fad5b3aad8e0ed720) | [#1831](https://github.com/decred/dcrdex/pull/1831) | karamble |
| Polish        | v0.4.1     | [2022-02-03](https://github.com/decred/dcrdex/commit/3c6e02590db6bafe6aac3d047f9067bc2288abca) | 069d6de       | kozel |
| Polish        | v0.5.0-rc1,<br>master | [2022-01-25](https://github.com/decred/dcrdex/commit/677252eb0abf4b477ebdb811ccc05f94c30175b5) | [#1423](https://github.com/decred/dcrdex/pull/1423) | kozel |
| Portuguese BR | v0.4.0-rc3 \[4\] | [2022-01-18](https://github.com/decred/dcrdex/commit/524b5a1019eb543cb41e49d5a50443f25f2b18f2) | 1e2fc06 | vctt |
| Portuguese BR | v0.5.0-rc1,<br>master | [2022-01-12](https://github.com/decred/dcrdex/commit/8be584684e2be3c6b93bf168c8a088c6e6a07fec) | [#1405](https://github.com/decred/dcrdex/pull/1405) | vctt |

\[3\] Last change directly authored by the main translator. Some translated strings may have been updated later by other people.

\[4\] pt-BR notifications may be older, last translated in [#1195](https://github.com/decred/dcrdex/pull/1185) (2021-09-20), preceding v0.4.0-rc1.


## decred.org

- decred.org translations are **funded** via the [D.R.E.A.M. 2](https://proposals.decred.org/record/5ef57f7) proposal until 2022-11-30. [Contact](#contact) @jholdstock on Matrix for the details.
- Read the [Translating Guide](https://github.com/decred/dcrweb/tree/master/transifex_catalogs#readme).
- Files to translate: [`transifex_catalogs`](https://github.com/decred/dcrweb/tree/master/transifex_catalogs). { _Note: This is just an old directory name, Transifex is not used anymore._ }

_Status as of: 2022-10-14_

| Language      | Release | EN base    | Changes \[5\] | Translators and notes |
|---------------|---------|------------|---------------|-----------------------|
| English       |         | [2022-10-11](https://github.com/decred/dcrweb/commit/c7f21ad70b5da52e86dd000584677d22fba0f0d6) | [#1090](https://github.com/decred/dcrweb/pull/1090) | |
| Arabic        |         | [2022-09-08](https://github.com/decred/dcrweb/commit/9d2874ff2af30bdabaddbca4c0a82560e24ffc65) | [#1072](https://github.com/decred/dcrweb/pull/1072) | arij |
| Chinese CN    |         | [2022-09-03](https://github.com/decred/dcrweb/commit/34c7d833ff020d3353c5917fdc199df89edaebe6) | [#1067](https://github.com/decred/dcrweb/pull/1067) | Dominic |
| German        |         | [2022-09-08](https://github.com/decred/dcrweb/commit/9d2874ff2af30bdabaddbca4c0a82560e24ffc65) | [#1072](https://github.com/decred/dcrweb/pull/1072) | karamble |
| Polish        |         | [2022-09-08](https://github.com/decred/dcrweb/commit/9d2874ff2af30bdabaddbca4c0a82560e24ffc65) | [#1072](https://github.com/decred/dcrweb/pull/1072) | kozel |
| Portuguese BR |         |            |               |                       |
| Spanish       |         |            |               |                       |

\[5\] Last change directly authored by the main translator. Some translated strings may have been updated later by other people.


## Android Wallet

- Android Wallet's future maintenance is uncertain. Ask about the status in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/) Matrix room or submit an issue in [dcrandroid issue tracker](https://github.com/planetdecred/dcrandroid/issues).
- Android Wallet translations have no active proposals with funding from Decred Treasury. Ask for updates in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/).
- Translating guide: { TODO }
- Files to translate: { TODO }

| Language | Release | EN base | Changes | Translators |
|----------|---------|---------|---------|-------------|
|          |         |         |         |             |

{ TODO }


## iOS Wallet

- iOS Wallet's future maintenance is uncertain. Ask about the status in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/) Matrix room or submit an issue in [dcrios issue tracker](https://github.com/planetdecred/dcrios/issues).
- iOS Wallet translations have no active proposals with funding from Decred Treasury. Ask for updates in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/).
- Translating guide: { TODO }
- Files to translate: { TODO }

| Language | Release | EN base | Changes | Translators |
|----------|---------|---------|---------|-------------|
|          |         |         |         |             |

{ TODO }


## GoDCR

- GoDCR's future maintenance is uncertain. Ask about the status in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/) Matrix room or submit an issue in [godcr issue tracker](https://github.com/planetdecred/godcr/issues).
- GoDCR translations have no active proposals with funding from Decred Treasury. Ask for updates in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/).
- Translating guide: { TODO }
- Files to translate: { TODO }

| Language | Release | EN base | Changes | Translators |
|----------|---------|---------|---------|-------------|
|          |         |         |         |             |

{ TODO }


## About

Users of this page:

- **Managers**: you can overview which translations are up-to-date, which are lagging, and who to contact to update a translation or create a new one.

- **Translators**: you can see where help is needed, whether it is funded, and who to contact to get started.

Columns:

- `Release`
  - Release version the translation was included in for.
  - `v1.7.5 TBR` means "v1.7.5 To Be Relesed", i.e. it is merged but not released yet.
  - Note that `v1.7.5` in `Release` column does *not* mean that release `v1.7.5` has been fully and correctly translated! It means that *some* translation work made it into `v1.7.5`. [Ask the translators](#contact) to determine how complete/accurate each translation is.
  - `v1.7.5, master` means the exact same translation is in both `v1.7.5` release branch and the `master` branch. Such translations occupy only one row in the table. If the translation was first made on `master` and then ported to the release branch in a separate commit (or vice versa), it must be two rows in the table.
- `EN base`
  - Version of original English strings that was translated.
  - It shows how *possibly* outdated the translation is.
  - For example, `Language = Polish, EN base = 2022-01-01` means that Polish translation is based on English strings that were last updated on 2022-01-01. If today is 2023-01-01, it means the translation *may* be 1 year behind the English originals, BUT only *if* English strings have changed since 2022-01-01.
  - `EN base` date is taken from Git *committer date* (not *author date*).
  - Decrediton requires a more complex process to find the `EN base` date, see footnotes after [Decrediton](#decrediton) status table.
- `Changes`
  - Pull requests or commits that last updated the translation.
- `Translators and notes`
  - Contributors to recent translation updates.
  - `UNMERGED` means it is not merged yet (waiting for a review, waiting for a rebase, or waiting for the maintainer to merge).


## Contact

Decred translations are coordinated in the Matrix [#translations](https://chat.decred.org/#/room/#translations:decred.org) public chat room. Feel free to ask any questions there.

To update for this page, submit an issue or a pull request in the [translations repository](https://github.com/decredcommunity/translations).
