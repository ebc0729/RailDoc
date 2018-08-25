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


