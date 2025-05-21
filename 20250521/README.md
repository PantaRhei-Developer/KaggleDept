# Kaggle部お題！

<B> スプリントコンペ ~Fake Newsかどうかを当てよう~</B>

# お題
ニュースの内容がフェイクかどうかを当てよう！

与えられるカラムは、

- id
- タイトル
- 記事本文
- サブジェクト(区分)
- 日付

これらから、そのニュースが真実がフェイクかを当てよう！

True: 0

Fake: 1

となっています！

# 評価指標
Accuracy(正解率)

# 提出回数
制限なし

# ...裏テーマ
idのリークに気が付けるか！？

実はidの早い方は真実ニュースで遅い方はフェイクニュースとなっている。
その境目を見つけたらルールベースで100%の精度が出る。

# データ
1. [元データ](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data)
2. [訓練データ](https://drive.google.com/file/d/1G67yNxwlJ63QgGafLVyIoYS1YmkvMKrz/view?usp=drive_link)
3. [テストデータ](https://drive.google.com/file/d/1h-OZg5gn_rstj7g29xVin-X8-iTEIFlT/view?usp=drive_link)
4. [サンプルサブミッション](https://drive.google.com/file/d/1Y44ttwGeWtQ-G-ImyC3AerZKagTMmNZA/view?usp=drive_link)

# 諸々のIpynb
for_compe.ipynb