# Sagattto.github.io

アプリの規約・サポート・`app-ads.txt` を置く公開サイト。
`https://sagattto.github.io/` で配信される（GitHub Pages / main ブランチのルート）。

```
index.html            開発者サイトの入口。App Store のマーケティング URL
app-ads.txt           AdMob。**ドメイン直下でないと読まれない**
style.css             共通スタイル
shikaku/
  index.html          資格の過去問シリーズの紹介
  privacy.html        プライバシーポリシー（シリーズ共通）
  support.html        サポート（App Store のサポート URL）
```

- **利用規約は置いていない。** Apple 標準の EULA
  （https://www.apple.com/legal/internet-services/itunes/dev/stdeula/）を使っている
- 規約はシリーズ共通。アプリが増えたら `shikaku/privacy.html` の対象アプリ一覧に1行足す
- `app-ads.txt` の publisher ID は未記入。AdMob でアプリを作ってから入れる

既存の `Sagattto/github-pages-site`（pdf-jump / offline-audit の規約）はそのまま。
あちらはプロジェクトページで `https://sagattto.github.io/github-pages-site/` に出る。
