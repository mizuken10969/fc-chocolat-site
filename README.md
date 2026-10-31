# 青梅新町FCショコラ 公式サイト

東京都青梅市の小学生女子サッカーチーム「青梅新町FCショコラ」の公式Webサイトです。
旧ペライチ版（fc-chocolat.hp.peraichi.com）から移行し、Cloudflare Pages で公開しています。

## 構成

```
index.html        … ページ本体（HTML / CSS を1ファイルに集約）
images/
  hero.jpg          … メイン画像（ロゴ入り）
  photo-match.jpg   … チーム紹介の写真
  photo-practice.jpg… 体験入部欄の写真
  banner1〜3.jpg    … 区切り用バナー
```

ビルド不要の静的サイトです。

## 更新方法

- **文章の修正**：`index.html` を編集して `main` に push → Cloudflare Pages が自動で公開
- **写真の差し替え**：`images/` 内の同名ファイルを上書きして push
  - 掲載する写真は、事前に代表・保護者の掲載許可を取ってください
  - 横幅 1600px 程度・300KB 以下を目安に圧縮すると表示が速くなります

## Cloudflare Pages 設定

- フレームワーク：なし
- ビルドコマンド：（空欄）
- 出力ディレクトリ：`/`
