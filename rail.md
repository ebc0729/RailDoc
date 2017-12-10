## 線路データ作成 [/rail/index]
### 線路データ取得 [POST]
乗車駅と降車駅をもとに線路データを取得します。  

+ Request (application/json)
	+ Attributes
		+ line_id: `1000` (number, required) - 路線Id
		+ start: `1` (number, required) - 乗車駅のstation_id
		+ end: `2` (number, required) - 降車駅のstation_id

+ Response 200 (application/json)
	+ Attribute(Rail)
		
+ Response 400 (application/json)
	+ Attribute(Error)


# Data Structure
## Rail
+ id: `1` (number, required) - 線路データ(rail) の id
+ line_id: `2` (number, required) - 路線データ(line) の id
+ data: ``"[[139.77818, 35.62961], [139.77888, 35.63]]"`` (string, required) - 線路データ
+ order: `10` (number, required) - 路線内での線路の順番
+ is_station: `true` (boolean, required) - その線路データが駅の座標か

## Error
+ message: `error message` (string, required) - エラーに合わせてメッセージを返す

