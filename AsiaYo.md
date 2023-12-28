# AsiaYo
* Method: Get
* Params:
	* source: String, ex. ["USD", "JPY", "NTD"]
	* target: String, ex. ["USD", "JPY", "NTD"]
	* amount: String, ex. ["$123,456", "12345"]
* Return:
	```
	{"msg":"success","amount":"$170,496.53"}
	```
* 功能說明:
	* 透過 `Get` 給予 `source` 幣種，會根據預先提供的匯率轉換成 `target` 幣種回傳