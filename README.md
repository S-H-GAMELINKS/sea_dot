### サービス概要
---
海の情報共有サービスです。海上で生き物を発見した際、その詳細情報をなどを地図上で共有する事できます。  
**URL: https://seadot.herokuapp.com**

### 作成背景
---
**長い航海を楽しみにするサービスを作りたかった**  
私は３年間大型船舶の船員でした。船に乗船すれば３ヶ月以上家に帰らず、船内で生活をしていました。  
船内でできる事は限られていましたが、１番の楽しみは海を眺めながら生き物を探す事で、それを共有できるサービスがあればより楽しむことが出来たと思います。

### 機能一覧
---
- ログイン (devies)
- ゲストログイン
- ログアウト
- ユーザー登録
- ユーザー情報編集
- 退会
- 詳細情報投稿/削除
- 画像アップロード/削除 (carrierwave,s3)
- 投稿詳細表示
- 投稿一覧表示
- ページネーション (kaminari)
- 位置情報を地図に登録/表示 (googleMap API)
- 一つのマップで全ての登録情報表示

### 使用技術一覧
---
- Ruby 2.6.6
- Rails 5.1.6
- JavaScript
- heroku
- bootstrap4
- rubocop