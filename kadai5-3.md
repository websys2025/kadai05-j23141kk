## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  エンドポイント
  　https://zipcloud.ibsnet.co.jp/api/search
  機能
  　指定した7桁の郵便番号に対応する日本の住所情報を返す無料のWebAPI
リクエストとレスポンスのフォーマット JSON形式
* リクエストとレスポンスのフォーマット
  郵便番号を入力。
  { "message": null, "results": [ { "address1": "千葉県", "address2": "市原市", "address3": "松ケ島", "kana1": "ﾁﾊﾞｹﾝ", "kana2": "ｲﾁﾊﾗｼ", "kana3": "ﾏﾂｶﾞｼﾏ", "prefcode": "12", "zipcode": "2900035" } ], "status": 200 }
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* エンドポイントと機能
  エンドポイント
  　https://official-joke-api.appspot.com/jokes/random';
  　機能
  　　ランダムでジョークを返してくれる
* リクエストとレスポンスのフォーマット
  実行ボタンを押すことで、
  Setup: Why dot net developers don't wear glasses?
  Punchline: Because they see sharp.
  と返してくれる。サイトによると、英語のジョークは英語であるから良いそうなので、翻訳はせずに、そのままにしている。
### Q3-3. 感想
* 今回の課題で苦労したこと
  APIの使用方法。
  有料が多く、キーを取得しなければ使えないものなど、とにかくやりづらかった。
* 演習を通して理解できたこと
　キーを取得しなくてもAPIを利用できる。
* Web APIの利便性や課題など
  利便性を把握できるほど理解できていない。
  APIを探しているときに気づいた点をあげるならば、日常で使っているツールはみんなAPI。
