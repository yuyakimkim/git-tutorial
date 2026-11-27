# Gitチュートリアル

本文中に脚注[^1]を挿入します。

[^example] 脚注の1行目です。\
2行目以降は4スペースでインデントします。

    - リスト項目1
    - リスト項目2

Github Flavored Markdown[^gfm]はGithub独自の拡張仕様です。
CommonMark[^commonmark]をベースにしています。

[^1]: ここに脚注の内容を記述します
[^example]: example
[^gfm]: GFMは2017年に正式仕様が公開されました。
[^commonmark]: CommonMarkはMarkdownの標準化を目指す仕様です。

このドキュメントは以上です。

```mermaid
gantt
    title プロジェクトスケジュール
    dateFormat YYYY-MM-DD
    section 設計
        要件定義    :a1, 2025-01-01, 14d
        基本設計    :a2, after a1, 10d
    section 開発
        フロントエンド    :b1, after a2, 20d
        バックエンド    :b2, after a2, 25d
    section テスト
        結合テスト    :c1, after b2, 10d
```

<detail>
<summary>クリックして展開</summary>

ここに折りたたまれる内容を記述します。
</detail>
