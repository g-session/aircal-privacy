# aircal-privacy

[aircal](https://github.com/g-session/aircal) のプライバシーポリシー公開用リポジトリ。
内容は aircal の `lib/assets/l10n/intl_*.arb` を元にスクリプトで自動生成しているため、
このリポジトリのファイルを直接編集しないこと。

## 公開URL

| 言語 | URL |
|---|---|
| 日本語 | https://g-session.github.io/aircal-privacy/ja/ |
| English | https://g-session.github.io/aircal-privacy/en/ |
| 한국어 | https://g-session.github.io/aircal-privacy/ko/ |
| 简体中文 | https://g-session.github.io/aircal-privacy/zh/ |
| 繁體中文 | https://g-session.github.io/aircal-privacy/zh-Hant/ |
| Español | https://g-session.github.io/aircal-privacy/es/ |
| Português | https://g-session.github.io/aircal-privacy/pt/ |

App Store Connect / Google Play Console の言語別プライバシーポリシーURL欄に登録する。

## 更新方法

aircal リポジトリ側で:

```bash
# ARB を編集後
python3 resources/generate_privacy_html.py
```

または Claude Code から:

```
/update-privacy
```

スクリプトが本リポジトリを clone / pull → 生成 HTML 上書き → 差分があれば commit & push する。
