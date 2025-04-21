## README：honda-sr-office_20250323（親孝行中）

このリポジトリは、**ホンダ社会保険労務士事務所**の静的Webサイト構成ファイルを管理するためのものです。HTML、CSS、画像などを用いた軽量なウェブサイトで、S3などの静的ホスティング環境へのデプロイを想定しています。

### ディレクトリ構成

```
honda-sr-office_20250323
├── README.md                 # この説明ファイル
├── contact.html              # お問い合わせページ
├── css/                      # スタイルシートフォルダ
│   ├── contact.css           # お問い合わせページ用スタイル
│   ├── index.css             # トップページ用スタイル
│   └── style.css             # 全体共通スタイル
├── images/                   # 画像フォルダ
│   ├── bridge.png            # トップ用イメージ画像
│   └── logo.png              # ロゴ画像
├── index.html                # トップページ
├── info/
│   └── 20241226093859.html   # お知らせ記事（日時付き）
├── office.html               # 事務所案内ページ
├── services.html             # サービス紹介ページ
└── support-a.html            # 就労支援A型に関するページ
```

### サイト概要

- **トップページ**：`index.html`
- **お問い合わせページ**：`contact.html`
- **事務所案内**：`office.html`
- **サービス案内**：`services.html`
- **就労支援A型**：`support-a.html`
- **お知らせ一覧**：`info/` 内に格納

### テスト公開中

https://honda-ehime-dev-20250323.s3.ap-northeast-1.amazonaws.com/honda-sr-office_20250323/index.html

### 備考

- HTMLとCSSのみで構成された静的Webサイトです。
- お問い合わせフォームなどは Formsubmit など外部サービスを活用。
- CloudFrontやRoute53によるカスタムドメイン運用も今後検討予定。

---

最終更新日：2025年3月27日  
制作・管理：ホンダ社会保険労務士事務所
