# aircal-privacy

[aircal](https://github.com/g-session/aircal) のプライバシーポリシー・利用規約 公開用リポジトリ。
内容は aircal の `lib/assets/l10n/intl_*.arb` を元にスクリプトで自動生成しているため、
このリポジトリのファイルを直接編集しないこと。

## 公開URL

### プライバシーポリシー

| 言語 | URL |
|---|---|
| 日本語 | https://g-session.github.io/aircal-privacy/privacy/ja/ |
| English | https://g-session.github.io/aircal-privacy/privacy/en/ |
| 한국어 | https://g-session.github.io/aircal-privacy/privacy/ko/ |
| 简体中文 | https://g-session.github.io/aircal-privacy/privacy/zh/ |
| 繁體中文 | https://g-session.github.io/aircal-privacy/privacy/zh-Hant/ |
| Español | https://g-session.github.io/aircal-privacy/privacy/es/ |
| Português | https://g-session.github.io/aircal-privacy/privacy/pt/ |
| Français | https://g-session.github.io/aircal-privacy/privacy/fr/ |
| Deutsch | https://g-session.github.io/aircal-privacy/privacy/de/ |
| Bahasa Indonesia | https://g-session.github.io/aircal-privacy/privacy/id/ |
| Italiano | https://g-session.github.io/aircal-privacy/privacy/it/ |
| Tiếng Việt | https://g-session.github.io/aircal-privacy/privacy/vi/ |
| Русский | https://g-session.github.io/aircal-privacy/privacy/ru/ |
| ไทย | https://g-session.github.io/aircal-privacy/privacy/th/ |
| Polski | https://g-session.github.io/aircal-privacy/privacy/pl/ |
| Nederlands | https://g-session.github.io/aircal-privacy/privacy/nl/ |
| Svenska | https://g-session.github.io/aircal-privacy/privacy/sv/ |
| Čeština | https://g-session.github.io/aircal-privacy/privacy/cs/ |
| Norsk bokmål | https://g-session.github.io/aircal-privacy/privacy/nb/ |
| Magyar | https://g-session.github.io/aircal-privacy/privacy/hu/ |
| Bahasa Melayu | https://g-session.github.io/aircal-privacy/privacy/ms/ |

英語の地域変種 (en_GB / en_AU / en_CA) は専用 ARB を持たず、共通の `en` (US) にフォールバックするため公開 URL も `/privacy/en/` 1 つに集約している。

### 利用規約

| 言語 | URL |
|---|---|
| 日本語 | https://g-session.github.io/aircal-privacy/terms/ja/ |
| English | https://g-session.github.io/aircal-privacy/terms/en/ |
| 한국어 | https://g-session.github.io/aircal-privacy/terms/ko/ |
| 简体中文 | https://g-session.github.io/aircal-privacy/terms/zh/ |
| 繁體中文 | https://g-session.github.io/aircal-privacy/terms/zh-Hant/ |
| Español | https://g-session.github.io/aircal-privacy/terms/es/ |
| Português | https://g-session.github.io/aircal-privacy/terms/pt/ |
| Français | https://g-session.github.io/aircal-privacy/terms/fr/ |
| Deutsch | https://g-session.github.io/aircal-privacy/terms/de/ |
| Bahasa Indonesia | https://g-session.github.io/aircal-privacy/terms/id/ |
| Italiano | https://g-session.github.io/aircal-privacy/terms/it/ |
| Tiếng Việt | https://g-session.github.io/aircal-privacy/terms/vi/ |
| Русский | https://g-session.github.io/aircal-privacy/terms/ru/ |
| ไทย | https://g-session.github.io/aircal-privacy/terms/th/ |
| Polski | https://g-session.github.io/aircal-privacy/terms/pl/ |
| Nederlands | https://g-session.github.io/aircal-privacy/terms/nl/ |
| Svenska | https://g-session.github.io/aircal-privacy/terms/sv/ |
| Čeština | https://g-session.github.io/aircal-privacy/terms/cs/ |
| Norsk bokmål | https://g-session.github.io/aircal-privacy/terms/nb/ |
| Magyar | https://g-session.github.io/aircal-privacy/terms/hu/ |
| Bahasa Melayu | https://g-session.github.io/aircal-privacy/terms/ms/ |

App Store Connect / Google Play Console の言語別 URL 欄に登録する。

## 更新方法

aircal リポジトリ側で:

```bash
# ARB を編集後
python3 resources/generate_legal_docs.py
```

または Claude Code から:

```
/update-legal-docs
```

スクリプトが本リポジトリを clone / pull → 生成 HTML 上書き → 差分があれば commit & push する。
