## 全エリア [/areas]
### 全エリア取得 [GET]
エリアを取得します。  

+ Response 200 (application/json)
	+ Attribute(Areas)
		
+ Response 400 (application/json)
	+ Attribute(Error)

## 指定エリア [/area/{id}] 
### 指定エリア取得 [GET]
エリアIDを元にエリアを取得します。

+ Parameters
	+ id: `1` (number, required) - エリアID

+ Response 200 (application/json)
	+ Attribute(Area)
		
+ Response 400 (application/json)
	+ Attribute(Error)


