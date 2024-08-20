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
<img width="1440" alt="スクリーンショット 2024-08-19 12 30 39" src="https://github.com/user-attachments/assets/5b74a241-661c-46db-b75e-3dda519e5ffd">
<br/>
word co-occurrence networksタブをクリックして共起ネットワークを表示
<br/>
<img width="1440" alt="スクリーンショット 2024-08-19 14 08 18" src="https://github.com/user-attachments/assets/6f608dd2-f711-42d1-9ae9-2dd147283c6f">
clusteringタブをクリックしてトピッククラスタリングを表示
<img width="1440" alt="スクリーンショット 2024-08-19 12 31 41" src="https://github.com/user-attachments/assets/48c3eb94-9bbf-42f9-bfa4-e9c130764645">
下にスクロールして批判の総括を表示
<img width="1440" alt="スクリーンショット 2024-08-19 12 32 01" src="https://github.com/user-attachments/assets/e5f4e109-9d3b-47cd-b6e7-7242455b7d21">

