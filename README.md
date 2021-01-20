# line-bot_vocabulary

gas(Google apps script)を使ったプロジェクトです。わからなかった英語表現をLINEで送信すると、意味を返してくれます。その後、その表現を忘れないように毎日以下のルールで繰り返しLINEを送ってくれます。
- 5回以下の場合は毎日送る
- 6回以上10回以下の場合は奇数回目に送り、偶数回目に送らない
- 11回以上50回以下の場合は5日おきに送る
- 50日経過した単語は削除


[こちら](https://docs.google.com/spreadsheets/d/16jWcdkhSVfqTtAn58pDsIqRzN-labrADVeIk-4j70jY/edit?usp=sharing)でスプレッドシートを開けます。コードを見るには[ツール]->[スクリプトエディタ]と進んでください。
