# Eclipse用Javaフォーマッター定義ファイル

## Setup

### Visual Studio Code

以下の設定を加える．

```json
"java.format.settings.profile": "java-code-style",
"java.format.settings.url": "https://raw.githubusercontent.com/tmiyachi/java-code-style/master/java-code-style.xml",
```

### Eclipse

- プロジェクト - プロパティ を開く．
- Java コード・スタイル - フォーマッター 項目から インポート を選択しこのXMLファイルを読み込む．
