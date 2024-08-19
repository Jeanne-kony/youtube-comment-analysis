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
タブをそれぞれ選択するとワードクラウド、共起ネットワーク、トピッククラスタリングを見ることができる。画面をスクロールすると下側に動画、コメントに対する批判の総括がまとめられている
<img width="1440" alt="スクリーンショット 2024-08-19 12 30 39" src="https://github.com/user-attachments/assets/edd3ce0d-1d48-4a7f-8595-81da59c25491">
<img width="1440" alt="スクリーンショット 2024-08-19 12 30 48" src="https://github.com/user-attachments/assets/2d77e25f-3244-4a6f-8ac5-f8aa67ce6cef">
<img width="1440" alt="スクリーンショット 2024-08-19 12 31 41" src="https://github.com/user-attachments/assets/95bc58fd-454e-4fa0-aa4b-0f3de166efda">
<img width="1440" alt="スクリーンショット 2024-08-19 12 32 01" src="https://github.com/user-attachments/assets/f1d3b111-312c-4786-ac66-76014b24951c">

