# youtube comments analysis
youtube comments analysisはYotube動画のURLを入力するとその動画のコメントをワードクラウド、共起ネットワーク、トピックごとに可視化してChatGPTによる批判の総括が分かるアプリケーションです

![無題のプレゼンテーション (1)](https://github.com/user-attachments/assets/11efd55f-3232-4f08-8a21-7120d82fa105)

# 主な特徴
* 辞書をipadicとしてMeCabによりテキストを形態素解析して名詞、動詞、形容詞を抽出しベクトル化
* NetworkXを使用して共起ネットワークを作成
* BERTopicによるトピッククラスタリング
* ChatGPTによる批判点の総括

# 使い方
コメント分析をしたい動画のURLを入力をEnter YouTube Video URLに入力します  
タブをそれぞれクリックするとワードクラウド、共起ネットワーク、トピッククラスタリングを見ることができます。画面を下側にスクロールすると動画、コメントに対する批判の総括がまとめられています
![スクリーンショット 2024-08-21 11 20 28](https://github.com/user-attachments/assets/fb0e4b04-4665-4ee5-b5b7-e2798c3ea3df)
![スクリーンショット 2024-08-21 12 23 23](https://github.com/user-attachments/assets/5dfcdc3b-986c-45ac-8011-5c25a9346078)
![スクリーンショット 2024-08-21 12 24 23](https://github.com/user-attachments/assets/a5d1e40a-76b9-4c34-855d-8137734cf439)
![スクリーンショット 2024-08-21 12 24 47](https://github.com/user-attachments/assets/ecdba646-0082-4e30-96d8-a183998ef157)
![スクリーンショット 2024-08-21 12 25 04](https://github.com/user-attachments/assets/8149b0ba-317f-48af-9244-afd6004066fd)

<br>
<br>
<br>
<br>
word co-occurrence networksタブをクリックすると共起ネットワークが表示されます
<img width="1440" alt="スクリーンショット 2024-08-21 9 16 09" src="https://github.com/user-attachments/assets/7e20d3a2-a3c7-4046-bd76-6a3733c651de">
<br>
<br>
<br>
<br>
clusteringタブをクリックするとトピッククラスタリングが表示されます
<img width="1440" alt="スクリーンショット 2024-08-21 9 15 06" src="https://github.com/user-attachments/assets/00b615a7-8f14-4793-8bdf-3fcc807a9e0c">
<br>
<br>
<br>
<br>
下にスクロールすると批判の総括が表示されます
<img width="1440" alt="スクリーンショット 2024-08-21 9 17 13" src="https://github.com/user-attachments/assets/406fc8dc-c3e3-4d63-ad41-ba4116e01b8c">

