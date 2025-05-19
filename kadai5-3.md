## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* エンドポイント：https://zipcloud.ibsnet.co.jp/api/search
* 機能：日本の郵便番号から住所情報を検索
* リクエストとレスポンスのフォーマット
* リクエスト：GET /api/search?zipcode=1000001 HTTP/1.1
* レスポンス：
* {
  "message": null,
  "results": {"address1": "東京都","address2": "千代田区","address3": "千代田","prefcode": "13","zipcode": "1000001"},
  "status": 400
}
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* API名称: OpenWeatherMap
* URL：https://openweathermap.org/api
* エンドポイントと機能
* エンドポイント：https://api.openweathermap.org/data/2.5/weather
* 機能：都市名から現在の天気情報を取得
* リクエストとレスポンスのフォーマット
* リクエスト：GET /data/2.5/weather?q=Tokyo&units=metric&appid=API_KEY HTTP/1.1
* レスポンス：
* {
  "weather": {"description": "broken clouds","icon": "01d","id": 800,"main": "Clear"},
  "main": {"temp": 18.36,"humidity": 73,"pressure": 1012},
  "name": "Tokyo",
  "cod": 200
}
### Q3-3. 感想
* 今回の課題で苦労したこと
* 非同期処理: async/awaitの動作理解に時間を要した。
* 演習を通して理解できたこと
* 非同期処理の実践的な活用方法。
* Web APIの利便性や課題など
* 利便性：リアルタイムデータの取得が容易
