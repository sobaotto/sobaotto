# 【制作物】画像で覚える英単語クイズアプリ
### [アプリへのリンク](https://photo-wordbook.web.app)　[リポジトリへのリンク](https://github.com/sobaotto/photo-wordbook)
## 目次
### 1. アプリ概要
- アプリイメージ
- コンセプト
- 実装機能（できること）
### 2. 開発に関して
- こだわり
- なぜ作ったのか？
- 開発で難しかったこと
### 3. 技術的なまとめ
- 使用技術
- 技術的に学んだこと
### 4. 今後の改善TODOなど（ユーザーからのフィードバックを元に）
- アプリの改善点
- 今後学びたい技術

# ①アプリ概要
## アプリイメージ
<img src="https://user-images.githubusercontent.com/75721044/119998007-45041200-c00b-11eb-9971-15eba0a66bdf.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998022-49c8c600-c00b-11eb-8b65-17327871b128.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998001-43d2e500-c00b-11eb-8d6c-8911b58baf6d.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119997946-36b5f600-c00b-11eb-8471-f00b7f800234.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119997973-3cabd700-c00b-11eb-93bc-29fc42b81e74.PNG" width="150px"> <img src="https://user-images.githubusercontent.com/75721044/119998028-4a615c80-c00b-11eb-982e-bc190d7100f0.PNG" width="150px">
 
## コンセプト
- 従来の単語帳の様な「英語⇄日本語」で記憶するのではなく、「英語⇄イメージ」で記憶することで英語脳を作ろう
> 参考画像（出典：https://fun-english.net/what-is-eigonou/ ）
<img src="https://user-images.githubusercontent.com/75721044/121796237-a276a080-cc52-11eb-8cda-d5be9cf6ce34.png" width="700px">

## 実装機能（できること）
1. ログイン機能
- ゲストorメアドでログインできる
2. クイズ機能
- クイズができる
- 結果は自動で保存される
3. 復習機能
- 覚えた単語の数を確認できる
- 覚えた単語にチェックができる
- 単語ごとにイメージ画像が確認できる

# ②開発に関して
## なぜ作ったのか？
1. 現在中国語を学習しており、その学習の質を向上させるため  
（将来的に、中国に向けてサービス開発をしてみたいと考えている。）
2. ユーザーが付くアプリに必須な、リッチなUIを実装できるようになるため  
（ReactのUIコンポーネントライブラリを試す中で、TypeScriptやFirebaseについても理解を深めようと考えた。）

## こだわり
1. ミニマムな機能でも、デプロイして使ってもらうこと
2. チーム開発のように、プルリク〜マージまでを擬似的に実践したこと
3. アドバイスをしてもらっていた先輩の時間を奪わないように、質問仕方を意識したこと
4. 学んだことをZennで発信し、知識定着を狙ったこと[＊Zennアカウントへ](https://zenn.dev/sobaotto)

## 開発で難しかったこと
1. 知識が少ない中でも、ドキュメントを読み解く必要があったこと（Qiitaなどに逃げない）
2. stateの管理場所を間違え、コードをほどき直す必要がでたこと
3. 画像の表示が遅く、クイズの進行に支障が出てしまったこと

# ③技術的なまとめ
## 使用技術
項目|詳細
-|-
フロントエンド|TypeScript, React
デプロイ先|Firebase Hosting
DB|Cloud Firestore
認証|Firebase Authentication
API作成|Cloud Functions
UIライブラリ|Chakra UI

## 技術的に学んだこと
1. TypeScript
 - 名前補完が効くこと
 - 型を使い回すことができること

2. React
 - コンポーネント単位でUIを構築できること
 - UIのコンポーネントライブラリが使えること

3. Firebase
 - アプリが公開しやすいこと
 - サーバー管理が不要であること
 - 多様な機能があるので拡張性があること

# ④今後の改善TODOなど（ユーザーからのフィードバックを元に）
## アプリの改善点
1. ゲスト会員から正規会員へ変更する導線を作る
2. 音で正誤を判定できるようにする
3. 間違えた問題の復習機能を作る
4. iOSでもPWAとして実装する（Androidは実装済み）
5. 辞書APIを用いて意味を充実させる

## 今後学びたい技術
1. フロントエンド
- Next.js
- Sass
2. 自然言語処理 API（GCP）
- Cloud Natural Language
- Cloud Speech-to-Text
