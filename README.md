# Tomorrow's Gift

夜だけ開いて、明日の自分に予定と手紙を送るスケジュールアプリ。

- 夜 21:00〜朝 5:00：明日の予定をつくって送る
- 朝 6:00〜：昨日の自分からの手紙が届く
- 昼：いまの予定と、予定に合わせて動くアバター

データはブラウザ（localStorage）にだけ保存されます。

## Googleカレンダー連携（読み込みのみ）

明日のGoogleカレンダーの予定を、タイムラインに「🔒 予定あり」として表示します。
アプリで立てた予定はGoogleカレンダーに書き込みません。

使うには `index.html` の `GOOGLE_CLIENT_ID` に、Google Cloud の OAuth クライアント ID（ウェブ アプリケーション）を入れます。
承認済みの JavaScript 生成元には `https://benkyoryuta-jpg.github.io` を登録します。
