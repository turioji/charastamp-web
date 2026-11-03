# 🎭 きゃらスタンプメーカー（CharaStamp）

自分のキャラクター画像を登録して、**吹き出し付きの画像**を作れるWebアプリです。
noteやブログの「掛け合い形式」の記事づくりにぴったりです。

👉 **使ってみる：** https://turioji.github.io/charastamp-web/

## できること

- キャラ画像を名前つきで登録・検索（辞書登録の感覚）
- クリックで画像をコピー → note・メール・LINEなどに Ctrl+V で貼り付け
- 吹き出し画像づくり
  - 吹き出しの色（16色＋好きな色）、アイコンの左右
  - 文字の色・太字（全体も、一部だけも）
  - 枠の色・太さ・枠なし、こさ（スマホで縮小されても読みやすく）
  - 言葉の切れ目で自動改行（BudouX の日本語モデルを使用）
  - 吹き出しに出す「表示名」（「クロちゃん_01」→「クロちゃん」）
- 縮小してもくっきり見える「くっきり補正」
- バックアップの書き出し・読み込み（JSON）
- 日本語／English の切り替え（右上のボタン。最初はブラウザの言語に合わせて自動で選びます）

## データについて

登録した画像は、**使っている人のブラウザの中（IndexedDB）だけ**に保存されます。
サーバーには送信されず、ほかの人には見えません。
ブラウザのデータを消すと画像も消えるので、大切なキャラはバックアップを取っておいてください。

## 動作環境

HTMLファイル1枚だけで動きます。インストールや登録は不要、無料です。
画像のクリップボードコピーは、HTTPSのページで、新しめのブラウザ（Chrome / Edge / Safari / Firefox）で動きます。
コピーできない環境では「PNG保存」をお使いください。

## クレジット

- 文節区切り：[BudouX](https://github.com/google/budoux)（Google / Apache License 2.0）の日本語モデルを同梱しています
- 作者：釣りおじ（[@turioji](https://github.com/turioji)）／釣りおじ編集部

---

## English

**Kyara Stamp Maker** turns your own character images into speech-bubble images for chat-style blog posts.
Free, no sign-up, runs right in your browser — switch the language with the 🌐 button at the top right.

👉 **Try it:** https://turioji.github.io/charastamp-web/

- Add your characters with names, then click to copy and paste them anywhere (Ctrl+V)
- Make speech bubbles: 16 colors + custom, left/right icons, text color & bold, border color & width
- Automatic line breaks that keep words together
- Your images are stored **only in your browser** (IndexedDB) — nothing is sent to a server. Please keep a backup (JSON export).
