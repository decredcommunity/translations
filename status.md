---
author: bee
updated: 2022-09-07
---

# Decred Translation Status

_Updated: 2022-09-07_

This page tracks the status of Decred translations that require continuous maintenance, primarily **software**. [About](#about) section at the end explains how to use this page. For a list of completed one-off *article translations* please see [the index](index.md).


## Decrediton

- Decrediton translations are **funded** via the [Translations phase 3 proposal](https://proposals.decred.org/record/7057e0b) until 2022-12-31. Contact @kozel on Matrix for the details.
- [Translating guide](https://github.com/decred/decrediton/blob/master/app/i18n/community_translators.md), contact @matheusd on Matrix for more detais.
- Files to translate: [Basic level](https://github.com/decred/decrediton/tree/master/app/i18n/translations), [Advanced level](https://github.com/decred/decrediton/tree/master/app/i18n/docs).

| Language (Level)         | Release    | Merged     | Changes | Translators |
|--------------------------|------------|------------|---------|-------------|
| English (Basic)          | v1.7.0-rc1 | 2021-12-23 | [#3618](https://github.com/decred/decrediton/pull/3618) | `original.json` last regen \* |
| English (Advanced)       | v1.7.4     | 2022-08-01 | [#3779](https://github.com/decred/decrediton/pull/3779), 3782957 | N/A |
| Arabic (Basic)           | v1.7.0-rc1 | 2022-01-04 | [#3632](https://github.com/decred/decrediton/pull/3632) | arij, abdulrahman4 |
| Arabic (Advanced)        | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _arij?_ } |
| Chinese CN (Basic)       | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _Dominic?_ } |
| Chinese CN (Advanced)    | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _Dominic?_ } |
| Chinese HK (Basic)       | v1.6.1     | 2021-02-22 | [#3086](https://github.com/decred/decrediton/pull/3086), 8d3b9b2 | smartwojak |
| Chinese HK (Advanced)    | v1.6.1     | 2021-02-22 | [#3086](https://github.com/decred/decrediton/pull/3086), 8d3b9b2 | smartwojak |
| French (Basic)           | v1.4.0     | 2018-12-11 | [#1875](https://github.com/decred/decrediton/pull/1875) | { _who?_ }
| French (Advanced)        | v1.4.0     | 2018-12-11 | [#1875](https://github.com/decred/decrediton/pull/1875) | { _who?_ }
| French (Basic)           | UNMERGED   | 2022-01-08 | [#3654](https://github.com/decred/decrediton/pull/3654) | jp, NEEDS REVIEW |
| French (Advanced)        | UNMERGED   | 2022-01-08 | [#3654](https://github.com/decred/decrediton/pull/3654) | jp, NEEDS REVIEW |
| German (Basic)           | v1.7.5 TBR | 2022-09-07 | [#3798](https://github.com/decred/decrediton/pull/3798) | karamble |
| German (Advanced)        | v1.6.0     | 2020-12-15 | [#3088](https://github.com/decred/decrediton/pull/3088) | karamble |
| Greek (Basic)            | UNMERGED   | 2022-03-08 | [#3719](https://github.com/decred/decrediton/pull/3719) | [Xk9eboF6](https://github.com/Xk9eboF6), NEEDS REVIEW |
| Greek (Advanced)         | UNMERGED   | 2022-03-08 | [#3719](https://github.com/decred/decrediton/pull/3719) | [Xk9eboF6](https://github.com/Xk9eboF6), NEEDS REVIEW |
| Italian (Basic)          | v1.7.0-rc2 | 2022-01-18 | [#3659](https://github.com/decred/decrediton/pull/3659), 28c6f61 | teknico, karamble |
| Italian (Advanced)       | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | teknico, karamble |
| Japanese (Basic)         | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _who?_ } |
| Japanese (Advanced)      | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _who?_ } |
| Polish (Basic)           | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _kozel?_ } |
| Polish (Advanced)        | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _kozel?_ } |
| Portuguese BR (Basic)    | v1.7.0-rc1 | 2022-01-03 | [#3619](https://github.com/decred/decrediton/pull/3619) | matheusd, { _others?_ } |
| Portuguese BR (Advanced) | v1.7.0-rc1 | 2022-01-03 | [#3619](https://github.com/decred/decrediton/pull/3619) | matheusd, { _others?_ } |
| Spanish (Basic)          | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _francov\_?_ } |
| Spanish (Advanced)       | v1.6.0     | 2020-12-14 | [#3052](https://github.com/decred/decrediton/pull/3052) | { _francov\_?_ } |

\* "Basic" translations are based on English strings in [`original.json`](https://github.com/decred/decrediton/blob/master/app/i18n/translations/original.json). This file is not the master source of truth, it must be **regenerated** from React sources to get the latest English strings. "Advanced" translations are based on files in the [`docs`](https://github.com/decred/decrediton/tree/master/app/i18n/docs) directory and don't need the regeneration step.

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

- DCRDEX translations are **funded** via the [Translations phase 3 proposal](https://proposals.decred.org/record/7057e0b) until 2022-12-31. Contact @kozel on Matrix for the details. { _Correct?_ }
- [Translating guide](https://github.com/decred/dcrdex/blob/master/docs/wiki/Localization-and-Translation.md), contact @chappjc on Matrix for more details.
- Files to translate: [HTML strings](https://github.com/decred/dcrdex/tree/master/client/webserver/locales), [Notification strings](https://github.com/decred/dcrdex/blob/master/client/core/locale_ntfn.go), [JavaScript strings](https://github.com/decred/dcrdex/blob/master/client/webserver/site/src/js/locales.ts)

| Language      | Release    | Merged     | Changes | Translators |
|---------------|------------|------------|---------|-------------|
| English US    | v0.5.0-rc1 | 2022-07-22 | f541ead, 3d7e73d, 9a7c21e | N/A |
| Chinese CN    | v0.4.0-rc1 | 2021-09-27 | [#1207](https://github.com/decred/dcrdex/pull/1207) | Dominic |
| German        | v0.5.3 TBR | 2022-08-30 | [#1815](https://github.com/decred/dcrdex/pull/1815), [#1831](https://github.com/decred/dcrdex/pull/1831) | karamble |
| Polish        | v0.4.1     | 2022-02-03 | [#1422](https://github.com/decred/dcrdex/pull/1422), cf3dbf4, bc7cff8, 069d6de | kozel |
| Portuguese BR | v0.4.0-rc3\* | 2022-01-18 | [#1405](https://github.com/decred/dcrdex/pull/1405), 1e2fc06 | vctt |

\* Notifications last translated in [#1195](https://github.com/decred/dcrdex/pull/1185) (2021-09-20), preceding v0.4.0-rc1.


## decred.org

- decred.org translations are **funded** via the [D.R.E.A.M. 2](https://proposals.decred.org/record/5ef57f7) proposal until 2022-11-30. Contact @jholdstock on Matrix for the details.
- [Translating guide](https://matrix.to/#/!qYctNXtSHVuWpHwZrK:decred.org/$TrCDyiz_HhmvmO1hv3QrPmDrlzwsL9lfy3KW29gpJ7M?via=decred.org&via=matrix.org) { _TODO please move from chat to a proper Markdown file in the repo_ }
- Files to translate: [transifex_catalogs](https://github.com/decred/dcrweb/tree/master/transifex_catalogs). { _Note: old directory name, Transifex is not used anymore_ }

| Language      | Release | Merged     | Changes | Translators |
|---------------|---------|------------|---------|-------------|
| English       |         | 2022-09-03 | [#1058](https://github.com/decred/dcrweb/pull/1058) | |
| Arabic        |         | 2022-09-07 | [#1068](https://github.com/decred/dcrweb/pull/1068) | arij |
| Chinese CN    |         | 2022-09-06 | [#1067](https://github.com/decred/dcrweb/pull/1067) | Dominic |
| German        |         | 2022-09-07 | [#1069](https://github.com/decred/dcrweb/pull/1069) | karamble |
| Polish        |         | 2022-09-07 | [#1070](https://github.com/decred/dcrweb/pull/1070) | kozel |
| Portuguese BR |         |            |         |             |
| Spanish       |         |            |         |             |


## Android Wallet

- Android Wallet's future maintenance is uncertain. Ask about the status in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/) Matrix room or submit an issue in [dcrandroid issue tracker](https://github.com/planetdecred/dcrandroid/issues).
- Android Wallet translations have no active proposals with funding from Decred Treasury. Ask for updates in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/).
- Translating guide: { TODO }
- Files to translate: { TODO }

| Language | Release | Merged | Changes | Translators |
|----------|---------|--------|---------|-------------|
|          |         |        |         |             |

{ TODO }


## iOS Wallet

- iOS Wallet's future maintenance is uncertain. Ask about the status in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/) Matrix room or submit an issue in [dcrios issue tracker](https://github.com/planetdecred/dcrios/issues).
- iOS Wallet translations have no active proposals with funding from Decred Treasury. Ask for updates in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/).
- Translating guide: { TODO }
- Files to translate: { TODO }

| Language | Release | Merged | Changes | Translators |
|----------|---------|--------|---------|-------------|
|          |         |        |         |             |

{ TODO }


## GoDCR

- GoDCR's future maintenance is uncertain. Ask about the status in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/) Matrix room or submit an issue in [godcr issue tracker](https://github.com/planetdecred/godcr/issues).
- GoDCR translations have no active proposals with funding from Decred Treasury. Ask for updates in the [#planetdecred](https://matrix.to/#/!gruHpujXftcsHcghjx:planetdecred.org/).
- Translating guide: { TODO }
- Files to translate: { TODO }

| Language | Release | Merged | Changes | Translators |
|----------|---------|--------|---------|-------------|
|          |         |        |         |             |

{ TODO }


## About

Users of this page:

- **Managers**: you can overview which translations are up-to-date, which are lagging, and who to contact to update a translation or create a new one.
- **Translators**: you can see where work is required, whether it is funded, and who to contact to get started.

Columns:

- `Release` - Earliest release the translation was updated for (and included in). `UNMERGED` means it is not merged yet (waiting for a review or for the maintainer to merge). `v1.7.5 TBR` means "v1.7.5 To Be Relesed", i.e. it is merged but not released yet.
- `Merged` - When last translation update was merged into a release branch. If `Release` column says `UNMERGED` then it is the last updated date.
- `Changes` - Pull requests or commits that last updated the translation (in both master and release branches).
- `Translators` - Contributors to recent translation updates.

For any questions please join the Matrix [#translations](https://chat.decred.org/#/room/#translations:decred.org) room.
