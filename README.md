# 【制作物】画像で覚える英単語クイズアプリ
## [＊アプリへ](https://photo-wordbook.web.app)　[＊リポジトリへ](https://github.com/sobaotto/photo-wordbook)
## アプリイメージ
<img src="https://user-images.githubusercontent.com/75721044/119998007-45041200-c00b-11eb-9971-15eba0a66bdf.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998022-49c8c600-c00b-11eb-8b65-17327871b128.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998001-43d2e500-c00b-11eb-8d6c-8911b58baf6d.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119997946-36b5f600-c00b-11eb-8471-f00b7f800234.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119997973-3cabd700-c00b-11eb-93bc-29fc42b81e74.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998028-4a615c80-c00b-11eb-982e-bc190d7100f0.PNG" width="150px">
 
## 制作物のコンセプト
- 従来の単語帳の様な「英語⇄日本語」で記憶するのではなく、「英語⇄画像」で記憶することで英語脳を作ろう

## 実装機能（できること）
- クイズができる
- 結果は自動で保存される
- 覚えた単語の数を確認できる
- 覚えた単語は手動でチェックできる
- 単語ごとにイメージ画像が確認できる
- ゲストorメアドでログインできる


## なぜ作ったのか？
- 語学はイメージで覚えることが重要だと思った、また、自分が欲しいと感じたから。

## 使用技術
項目|詳細
-|-
フロントエンド|- TypeScript　- React
バックエンド|- Firebase
CI/CD|Github Actions

## 技術の選定理由
1. TypeScript
 - 名前補完が効くこと
 - 型を使い回すことができること

1. React
 - コンポーネント単位でUIを構築できること
 - UIのコンポーネントライブラリが使えること

1. Firebase
 - アプリが公開しやすいこと
 - サーバー管理が不要であること
 - 多様な機能があるので拡張性があること

1. Github Actions 
 - GitHubに組み込まれているので、扱いやすいこと


## 開発で難しかったところ
- 設計。stateの管理場所など。

## 技術的な工夫点
- 画像を事前に一括で読み込むことで、UXの向上を図った
- webpackとtsconfigの設定を自前で行なったこと

## その他のこだわり
- チーム開発のように、プルリク〜マージまでを擬似的に実践したこと
- アドバイスをしてもらっていた先輩の時間を奪わないように、質問仕方を意識した
- 学んだことをZennで発信、また知識定着を狙った[＊Zennアカウントへ](https://zenn.dev/sobaotto)

## 今後の改善方針
- ゲスト会員から正規会員へ変更する導線を作る
- 音で正誤を判定できるようにする
- 復習機能をつける
- UIを綺麗にする
- iOSでもPWAとして実装する（Androidは実装済み）
- 辞書APIを用いて単語に加える

## 今後学びたい技術
- ESLint/Prettier
- Next.js
- Sass
- PWA
