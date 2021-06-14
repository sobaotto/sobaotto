# 【制作物】画像で覚える英単語クイズアプリ
### [アプリへのリンク](https://photo-wordbook.web.app)　[リポジトリへのリンク](https://github.com/sobaotto/photo-wordbook)
## 目次
1. アプリ概要
- アプリイメージ
- コンセプト
- 実装機能（できること）
2. こだわりなど
- こだわり
- なぜ作ったのか？
- 開発で難しかったこと
3. 技術的なまとめ
- 使用技術
- 技術的に学んだこと
4. 今後の改善TODOなど（ユーザーからのフィードバックを元に）
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

# ②こだわりなど
## こだわり
- ミニマムな機能でも、デプロイして使ってもらうこと
- チーム開発のように、プルリク〜マージまでを擬似的に実践したこと
- アドバイスをしてもらっていた先輩の時間を奪わないように、質問仕方を意識したこと
- 学んだことをZennで発信し、知識定着を狙ったこと[＊Zennアカウントへ](https://zenn.dev/sobaotto)

## なぜ作ったのか？
### 技術以外の理由

- 現在行っている中国語学習をより効果的にするため

学習している理由は、IT先進国である中国に興味があるからだ。  
将来的に、「コーチングができるBot」を作りたいと考えており海外の事例も効果的に参考にできるようになりたい。  

### 技術的な理由

- ReactのUIコンポーネントライブラリを試す中で、TypeScriptやFirebaseについても理解を深めるため

個人開発をする上で重視していたことは以下の2点である   

①ユーザーに愛されるアプリが作れること  
②技術的な成長ができること  

愛されるアプリの必要条件としてリッチなUIであることが重要だと考えたため、UIコンポーネントライブラリを試すことにした。  

## 開発で難しかったこと
- 知識が少ない中でも、ドキュメントを読み解く必要があったこと（Qiitaなどに逃げない）
- stateの管理場所を間違え、コードをほどき直す必要がでたこと
- 画像の表示が遅く、クイズの進行に支障が出てしまったこと

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
- ゲスト会員から正規会員へ変更する導線を作る
- 音で正誤を判定できるようにする
- 間違えた問題の復習機能を作る
- iOSでもPWAとして実装する（Androidは実装済み）
- 辞書APIを用いて意味を充実させる

## 今後学びたい技術
- ESLint/Prettier
- Next.js
- Sass
- PWA
