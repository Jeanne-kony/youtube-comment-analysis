# youtube comments analysis
youtube comments analysisはYotube動画のURLを入力するとその動画のコメントをワードクラウド、共起ネットワーク、トピックごとに
可視化してChatGPTによる批判の総括が分かるアプリケーションです

![無題のプレゼンテーション (1)](https://github.com/user-attachments/assets/11efd55f-3232-4f08-8a21-7120d82fa105)

# 主な特徴
* 辞書をipadicとしてMeCabによりテキストを形態素解析して名詞、動詞、形容詞を抽出しベクトル化
* NetworkXを使用して共起ネットワークを作成
* BERTopicによるトピッククラスタリング
* ChatGPTによる批判点の総括

# 使い方
* コメント分析をしたい動画のURLをEnter YouTube Video URLに入力します。今回は下記動画のURLを入力します
![スクリーンショット 2024-08-21 13 17 34](https://github.com/user-attachments/assets/c4251bbc-a099-4bd5-b14b-bc44dce319d8)
<br>

* word cloudタブをクリックするとワードクラウドが表示されます
![スクリーンショット 2024-08-21 12 23 23](https://github.com/user-attachments/assets/5dfcdc3b-986c-45ac-8011-5c25a9346078)
<br>
<br>

* word co-occurrence networksタブをクリックすると共起ネットワークが表示されます
![スクリーンショット 2024-08-21 12 24 23](https://github.com/user-attachments/assets/a5d1e40a-76b9-4c34-855d-8137734cf439)
<br>
<br>

* clusteringタブをクリックするとトピッククラスタリングが表示されます
![スクリーンショット 2024-08-21 12 24 47](https://github.com/user-attachments/assets/ecdba646-0082-4e30-96d8-a183998ef157)
<br>
<br>

* 下にスクロールすると批判の総括が表示されます
![スクリーンショット 2024-08-21 12 25 04](https://github.com/user-attachments/assets/8149b0ba-317f-48af-9244-afd6004066fd)
<br>

# 今後実装予定機能
コメントがポジティブ、ネガティブ、ニュートラルのどの割合が多いのか示す機能を実装予定です。試しに分類してみたところ
判定が甘い部分があるため、モデルのチューニングなどを行い改善を図りたいと思います
<br>
<br>
![スクリーンショット 2024-08-21 11 20 28](https://github.com/user-attachments/assets/fb0e4b04-4665-4ee5-b5b7-e2798c3ea3df)
