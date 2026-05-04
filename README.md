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
