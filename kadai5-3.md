## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* エンドポイント：https://zipcloud.ibsnet.co.jp/api/search
* 機能：日本の郵便番号から住所情報を検索
* リクエストとレスポンスのフォーマット
* リクエストはzipcodeパラメータに郵便番号を指定してGETで送信。
* レスポンスはJSON形式で、results配列に住所情報が入っている。
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* API名称: OpenWeatherMap
* URL：https://openweathermap.org/api
* エンドポイントと機能
* エンドポイント：https://api.openweathermap.org/data/2.5/weather
* 機能：都市名から現在の天気情報を取得
* リクエストとレスポンスのフォーマット
* リクエストパラメータに都市名やAPIキーを付ける。
* レスポンスには天気、気温、湿度などが含まれる。
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など
