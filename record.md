## 乗車記録作成 [/records/index]
### 乗車記録作成 [POST]
乗車駅と降車駅を送信することで乗車記録を作成する

+ Request (application/json)
	+ Attributes
		+ user_id: `1` (number, required) - ユーザId
		+ route_id: `2` (number, required) - 路線Id
		+ start_station_id: `3` (number, required) - 乗車駅のstation_id
		+ end_station_id: `4` (number, required) - 降車駅のstation_id

+ Response 200 (application/json)
	+ Attribute(Success)
		
+ Response 400 (application/json)
	+ Attribute(Error)
