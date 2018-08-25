FORMAT: 1A

# RailApi

<!-- include(rail.md) -->
<!-- include(record.md) -->

# Data Structure
## Error
+ message: `error message` (string, required) - エラーに合わせてメッセージを返す

## Success
+ message: `Success` (string, required)

## Rail
+ id: `1` (number, required) - 線路データ(rail) の id
+ line_id: `2` (number, required) - 路線データ(line) の id
+ data: ``"[[139.77818, 35.62961], [139.77888, 35.63]]"`` (string, required) - 線路データ
+ order: `10` (number, required) - 路線内での線路の順番
+ is_station: `true` (boolean, required) - その線路データが駅の座標か

