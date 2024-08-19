# youtube comments analysis
youtube comments analysisはYotube動画のURLを入力するとその動画のコメントをワードクラウド、共起ネットワーク、トピックごとに可視化してChatGPTによる総括が分かるアプリケーションです。

![無題のプレゼンテーション (1)](https://github.com/user-attachments/assets/11efd55f-3232-4f08-8a21-7120d82fa105)

# 主な特徴
* 辞書をipadicとしてMeCabによりテキストを形態素解析して名詞、動詞、形容詞を抽出しベクトル化
* NetworkXを使用して共起ネットワークを作成
* BERTopicによるトピッククラスタリング
* ChatGPTによる批判点の総括

# 使い方
コメント分析をしたい動画のURLを入力をEnter YouTube Video URLに入力  
タブをそれぞれ選択するとワードクラウド、共起ネットワーク、トピッククラスタリングを見ることができる。画面を下側にスクロールすると動画、コメントに対する批判の総括がまとめられている
<img width="1440" alt="スクリーンショット 2024-08-19 12 30 39" src="https://github.com/user-attachments/assets/5b74a241-661c-46db-b75e-3dda519e5ffd">
<img width="1440" alt="スクリーンショット 2024-08-19 12 30 48" src="https://github.com/user-attachments/assets/c00245b4-89f6-47c0-9265-d255ff07c4cc">
<img width="1440" alt="スクリーンショット 2024-08-19 12 31 41" src="https://github.com/user-attachments/assets/48c3eb94-9bbf-42f9-bfa4-e9c130764645">
<img width="1440" alt="スクリーンショット 2024-08-19 12 32 01" src="https://github.com/user-attachments/assets/e5f4e109-9d3b-47cd-b6e7-7242455b7d21">

