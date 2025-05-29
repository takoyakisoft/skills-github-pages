## ステップ3: サイトを設定する

ホームページの更新、お疲れ様でした ✨

サイトの見栄えを良くするために、少し**設定**を行いましょう！

### 📖 理論: Jekyll と \_config.yml

Jekyll は `_config.yml` というファイルを使用して、サイトの設定、テーマ、サイトタイトルや GitHub ハンドルなどの再利用可能なコンテンツを保存します。詳細は [Jekyll の設定ドキュメント](https://jekyllrb.com/docs/configuration/) をご覧ください。

このアクティビティでは、「minima」というブログ向けのテーマを使用します。

### ⌨️ アクティビティ: サイトを設定する

1. `main` ブランチの `_config.yml` ファイルに移動します。
1. 右上隅にあるファイルエディタを開きます。
1. 以下のように `_config.yml` ファイルに表示されるように、`theme:` を **minima** に設定して追加します。

   ```yml
   theme: minima
   ```

1. (任意) `title:`、`author:`、`description:` などの他の設定変数を変更して、サイトをさらにカスタマイズできます。

   <details>
   <summary>例</summary><br/>

   ```yml
   theme: minima
   title: {{ login }} の個人的なブログ
   description: ここでは私の人生に関するクールなことを共有します
   author: {{ login }}
   ```

   </details>

1. 変更を `main` ブランチにコミットします。
1. 変更をコミットすると、Mona がこの演習の次のステップを準備します！

<details>
<summary>困ったときは？ 🤷</summary><br/>

- `main` ブランチの `_config.yml` ファイルを編集していることを確認してください。
- YAML の書式を再確認してください。インデントとコロンが重要です！

</details>