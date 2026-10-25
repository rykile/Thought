# Thought — サイト構成

## フォルダ・ファイル

```text
Thought/
├── index.html              # 公開サイトのトップページ
├── README.md               # リポジトリの説明（GitHub上で表示）
├── assets/
│   ├── css/
│   │   └── style.css       # 共通デザイン用CSS（分離する場合）
│   ├── js/
│   │   └── main.js         # 必要になった場合の共通JavaScript
│   └── images/             # ロゴ・画像など
└── pages/
    ├── about.html          # プロフィール・このサイトについて（将来用）
    ├── thoughts.html       # 考え方の詳細（将来用）
    └── updates.html        # 更新履歴（将来用）
```

## 運用メモ

- GitHub Pages の入口は小文字の `index.html` にします。
- 今回のトップページはCSSをHTML内に含めた、単独で動作する構成です。
- `assets/css/style.css` と `assets/js/main.js` は、共通化が必要になった段階で使います。
- `pages/` 内のHTMLは将来ページを追加するための予定枠です。空のファイルを増やす必要はありません。
- 画像を追加する場合は `assets/images/` に保存し、HTMLから相対パスで参照します。
- 公開URLは通常 `https://rykile.github.io/Thought/` です。
