# textlint-rule-preset-rk

アールケー開発で利用されているTextLintのルールです。

[ics-creative/textlint-rule-preset-icsmedia](textlint-rule-preset-icsmedia)からフォークして作成しました。

## 使用方法

`.textlintrc`ファイルで校正辞書を指定する。

```json
{
  "rules": {
    "prh": {
      "rulePaths": [
         "./dict/prh_root.yml"
      ]
    }
  }
}
```

### 校正辞書

| 名前                  | 説明 |
|----------------------|------|
| `prh_root.yml`       | 一般的な原稿用 |
| `prh_root_apple.yml` | Appleプラットフォーム用の原稿用 |

