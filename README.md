# 画像で覚える英単語クイズアプリ　[＊アプリへ](https://photo-wordbook.web.app)　[＊リポジトリへ](https://github.com/sobaotto/photo-wordbook)
## イメージ
<img src="https://user-images.githubusercontent.com/75721044/119998007-45041200-c00b-11eb-9971-15eba0a66bdf.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998022-49c8c600-c00b-11eb-8b65-17327871b128.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998001-43d2e500-c00b-11eb-8d6c-8911b58baf6d.PNG" width="150px">

<img src="https://user-images.githubusercontent.com/75721044/119997946-36b5f600-c00b-11eb-8471-f00b7f800234.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119997973-3cabd700-c00b-11eb-93bc-29fc42b81e74.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998028-4a615c80-c00b-11eb-982e-bc190d7100f0.PNG" width="150px">
 
## 使用技術
項目|詳細
-|-
フロントエンド|- TypeScript　- React
バックエンド|- Firebase
CI/CD|Github Actions

## 制作物のコンセプト
- 従来の単語帳の様な「英語⇄日本語」で記憶するのではなく、「英語⇄画像」で記憶することで英語脳を作ろう

## 技術的な工夫点
- ***SPA***として実装したこと
- DB操作を自作APIで実装したこと
- リファレンスに沿った命名規則を意識したこと
- ***GitHub Actions***を用いてCD環境を構築したこと
- ***webpack***と***tsconfig***の設定を***自前***で行なったこと
- TypeScriptで型付けすることでバグを生みにくくした
- 実務に近づけるために***プルリク〜マージ***までを実践したこと

## 非技術的な工夫点
- 相手の時間を奪わない質問仕方を意識した
- 学んだことをZennに投稿し、発信した[＊Zennアカウントへ](https://zenn.dev/sobaotto)

## 今後の改善方針
- iOSでもPWAとして実装する（Androidは実装済み）
- APIをExpressを用いてRESTfulに実装する
- DB負荷や拡張性を意識して開発する

## 今後学びたい技術
- ESLint/Prettier
- Next.js
- SASS
- PWA
