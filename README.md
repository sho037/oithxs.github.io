# HxSコンピュータ部 GitHub Pages

## このリポジトリについて
　このリポジトリは、HxSコンピュータ部の公式Webサイトのソースコードを管理するためのリポジトリです。
当リポジトリは、[GitHub Pages](https://pages.github.com/)を使用し、公開しています。
リンクは[こちら](https://oithxs.github.io/)です。


## 部員の方へ
　編集は各自自由に行ってください。ただし、以下のルールに従ってください。
- forkを行ってから編集を開始してください
- 公開する際は、mainブランチにマージをしてください

　また、編集の行い方を以下に示します。
1. Dockerをインストールしてください(docker-composeも必要です)
2. このリポジトリをcloneしてください
3. dockerフォルダに移動してください
4. 'docker-compose build'を実行してください
5. 'docker-compose up -d'を実行してください(サーバーが起動します)
6. 'docker-compose exec jekyll bash'を実行してください
7. 'bundle exec jekyll build'を実行してください(サイトのビルドが行われます)

  編集した内容は、'http://localhost:4000/'で確認できます。<br>
  編集が終わったら、'docker-compose down'を実行してください。<br>
  分からないことがあれば、[こちら](https://twitter.com/sho037git)に質問してください。