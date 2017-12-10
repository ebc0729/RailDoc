## 線路データ作成 [/rail/index]
### 線路データ取得 [POST]
路線IDと乗車駅と降車駅をもとに線路データを取得します。  

+ Request (application/json)
	+ Attributes
		+ line_id: `1000` (number, required) - 路線Id
		+ start_order: `1` (number, required) - 乗車駅のrail_order
		+ end_order: `2` (number, required) - 降車駅のrail_order

+ Response 200 (application/json)
	+ Attribute(Rail)
		
+ Response 400 (application/json)
	+ Attribute(Error)

