# Portfolio Site — 角川 花歩 (Sumikawa Kaho)

近畿大学 経営学部 3年 / 2028年卒
ゲーム企画・エンジニア志望

自己紹介・スキル・制作物をまとめた個人ポートフォリオサイトです。
企画から実装まで一貫して自分の手で形にすることを目指し、Web・ゲームの両面で制作に取り組んでいます。

**公開URL:** https://kaho-sumikawa.github.io/Kaho.Portfolio/

---

## 制作物 (Works)

このサイトからアクセスできる主な制作物です。

| 作品 | 概要 | 使用技術 |
| --- | --- | --- |
| [セミファイナル](https://unityroom.com/games/semifinal) | 個人制作・実装1日のミニゲーム。セミ側の視点で「死んだふり」の駆け引きを描く（[GitHub](https://github.com/Kaho-Sumikawa/semiFinal)） | Unity / C# / TextMeshPro |
| [後ろの白い城を白日にしろ](https://unityroom.com/games/shiroioshiro) | unity1week「しろ」お題参加作品（[GitHub](https://github.com/Kaho-Sumikawa/shiro-jam)） | Unity / C# |
| Portfolio Site | 本ポートフォリオサイト | HTML / CSS / JavaScript / Figma |
| こいのぼりゲーム | Unityで制作したミニゲーム（unityroom公開） | Unity / C# |
| 知り合いコレクション | 学内ハッカソンで開発したアバターWebアプリ（[開発記事](https://zenn.dev/kaho_s/articles/d9b34f8c325330)） | EJS / Node.js / Express / SQLite |
| 爆走！近大マグロ | 学生チームでのゲーム開発（3Dモデリング担当） | Unity / Blender |

---

## このサイトについて

### 使用技術

- **HTML / CSS** — レスポンシブ対応（PC / タブレット / スマートフォン）
- **JavaScript** — スクロール連動のアニメーションやインタラクションをバニラJSで実装
- **Figma** — サイト全体のデザイン・レイアウト設計

### 工夫した点

- スクロールに応じて要素がフェードインする演出を、外部ライブラリに頼らずJavaScriptで実装
- Figmaでデザインを固めてからコーディングし、余白・配色・タイポグラフィに一貫性を持たせた
- 画面幅に応じてレイアウトが崩れないよう、CSSでレスポンシブ設計を実施

### ディレクトリ構成

```
Kaho.Portfolio/
├── index.html          # トップページ
├── css/
│   ├── reset.css       # リセットCSS
│   ├── style.css       # メインスタイル
│   └── responsible.css # レスポンシブ対応
├── js/
│   └── app.js          # アニメーション・インタラクション
└── assets/
    └── img/            # 画像素材
```

---

## 制作者 (Author)

**角川 花歩 / Sumikawa Kaho**

- Email: sumikawa.kaho@gmail.com
- GitHub: https://github.com/Kaho-Sumikawa
