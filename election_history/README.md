# election_history
* 因 1998 年修改過內政部編碼，1998 年（包含）以前的選舉地區編碼方式不同，此份資料先排除 1998 年以前由中選會提供的資料
## 一般選舉

* 選舉類別
	* citycon: 議員
	* citymayor: 縣市長
	* congress: 立法委員
	* president: 總統副總統

* 檔案類型
	* elctks: 票數細節
	* elprof: 區域票數統整
	* partyresult: 不分區立委選舉結果

* 後綴
	* _[yyyy]: 選舉年份
	* _dc: 直轄市
	* _cc: 其他縣市
	* _am: 山地原住民
	* _an: 平地原住民
	* _all: 其他區域立委
	* _party: 不分區政黨票

* 其他
	* congress_2020_liCode_mapping: 2020 年立委有同一個開票所代表多個村里投票的狀況，在資料上，liCode 最前方會加上英文代號（如 1001 會變成 A1001），此為 mapping 檔案

## 公投
* 選舉類別
	* referendum: 公投

* 檔案類型
	* rfctks: 票數細節
	* rfprof: 區域票數統整

* 後綴
	* _[no]: 公投案號
	* _hc: 新竹市地方公投