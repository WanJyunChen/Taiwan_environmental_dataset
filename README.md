# 臺灣陸域環境因子多時序資料集 (A multi-temporal and terrestrial environmental dataset of Taiwan)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
* 盤點國內外環境資料集，篩選其中高解析度且訊息最完整之臺灣範圍內資料，運用GIS空間分析建構1 km網格解析度的「臺灣陸域環境因子多時序資料集」
* 資料集時間橫跨1970-2010年，以每10年為時間分點，共分成5個年代
* 資料範圍含括臺灣整體陸域，並依地理位置分別建立兩個子資料集
  * TWD97/TM2 Zone 119 (EPSG: 3825)，包含馬祖列島、金門群島、澎湖群島與東沙群島
  * TWD97/TM2 Zone 121 (EPSG: 3826)，包含臺灣本島、琉球嶼、北方三島、龜山島、綠島與蘭嶼
* 資料集內的環境因子包含8個地形因子、79個氣候因子、9個土地覆蓋因子與4個其他人文地理因子等共100項變數
  * 地形因子  
  (1)	平均海拔 (Mean of Elevation, ELE)：海拔高度的平均值，單位m。  
  (2)	最高海拔 (Maximum Elevation, ELEMAX)：海拔高度的最大值，單位m。  
  (3)	最低海拔 (Minimum Elevation, ELEMIN)：海拔高度的最小值，單位m。  
  (4)	海拔跨幅 (Elevation Range, ELERA)：海拔高度的跨幅，ELEMAX與ELEMIN的差值，單位m。  
  (5)	海拔變化 (Standard Deviation of Elevation, ELESD)：海拔高度的變異程度，單位m。  
  (6)	坡度 (Slope)：單位degree。  
  (7)	坡向 (Aspect)：單位degree。  
  (8)	日射量 (Area Solar Radiation, ASR)：全年日照平均值，單位WH/m<sup>2</sup>。  
  * 氣候因子     
   __溫度 (Temperature)__  
   (1)	月均溫 (Monthly mean of daily mean temperature, Temp)：一至十二月每一個月之平均每日均溫，總共12個月份的月均溫圖層 (Temp01-12)，單位℃。  
   (2)	月高溫 (Monthly mean of daily maximum temperature, Tmax)：一至十二月每一個月份之平均每日最高溫，總共12個月份的平均最高溫圖層(Tmax01-12)，單位℃。  
   (3)	月低溫 (Monthly mean of daily minimum temperature, Tmin)：一至十二月每一個月份之平均每日最低溫，總共12個月份的平均最低溫圖層 (Tmin01-12)，單位℃。  
   (4)	每月平均日溫差 (Range of maximum and minimum monthly temperature, Tra)：一至十二月每一個月份之平均每日溫差，總共12個月份的平均日溫差圖層(Tra01-12)，單位℃。     
   __降水量 (Precipitation)__  
   (5)	月降水量  (Monthly precipitation sums, Prec)：一至十二月每一個月份之月降水量，總共12個月份的月降水量圖層(Prec01-12)，單位mm。   
   __生物氣候變數 (Bioclimatic variables)__  
   (6)	年均溫 (Annual Mean Temperature, Bio01)：全年12個月份月均溫之平均值，單位℃。  
   (7)	平均日溫差 (Mean Diurnal Range, Bio02)：全年12個月份平均日溫差之平均值，每月平均日溫差為當月高溫與當月低溫之差值，單位℃。  
   (8) 溫度恆定性 (Isothermality, Bio03)：平均日溫差除以年溫差 (Bio2 / Bio7)× 100，單位%。  
   (9)	溫度季節性 (Temperature Seasonality, Bio04)：全年12個月份平均月均溫之標準差，單位℃。  
   (10)	最暖月份之最高溫 (Max Temperature of Warmest Month, Bio05)：12個月份中，月高溫之最大值，單位℃。  
   (11)	最冷月份之最低溫 (Min Temperature of Coldest Month, Bio06)：12個月份中，月低溫之最小值，單位℃。  
   (12)	年溫差 (Temperature Annual Range, Bio07)：最暖月份之月高溫與最冷月份之月低溫之差值，單位℃。  
   (13)	最潮濕季節之平均溫度 (Mean Temperature of Wettest Quarter, Bio08)：連續3個月累積雨量最多月份之月均溫，單位℃。  
   (14)	最乾燥季節之平均溫度 (Mean Temperature of Driest Quarter, Bio09)：連續3個月累積雨量最少月份之月均溫，單位℃。  
   (15)	最溫暖季節之平均溫度 (Mean Temperature of Warmest Quarter, Bio10)：連續3個月之月均溫最高月份之月均溫，單位℃。  
   (16)	最寒冷季節之平均溫度 (Mean Temperature of Coldest Quarter, Bio11)：連續3個月之月均溫最低月份之月均溫，單位℃。  
   (17)	年降水量 (Annual Precipitation, Bio12)：一年的總降水量，為一至十二月每月降水量之加總值，單位mm。  
   (18)	最潮濕月份之降水量 (Precipitation of Wettest Month, Bio13)：降水量最高月份之降水量，單位mm。  
   (19)	最乾燥月份之降水量 (Precipitation of Driest Month, Bio14)：降水量最低月份之降水量，單位mm。  
   (20)	降水之季節性 (Precipitation Seasonality, Bio15)：12個月降水量之變異係數 (Coefficient of Variation) ，單位%。  
   (21)	最潮濕季節之降水量 (Precipitation of Wettest Quarter, Bio16)：連續3個月降水量累加值最多月份之雨量，單位mm/quarter。  
   (22)	最乾燥季節之降水量 (Precipitation of Driest Quarter, Bio17)：連續3個月降水量累加值最低月份之雨量，單位mm。  
   (23)	最溫暖季節之降水量 (Precipitation of Warmest Quarter, Bio18)：連續3個月均溫最高月份之降水量，單位mm。  
   (24)	最寒冷季節之降水量 (Precipitation of Coldest Quarter, Bio19)：連續3個月均溫最低月份之降水量，單位mm。  

  * 土地覆蓋因子  
  (1)	農田 (Farm field, FF)：包含倚賴降雨的農田以及部分農田與自然植被鑲嵌（樹木、灌木、草本植物）土地覆蓋類型，單位m<sup>2</sup>。  
  (2)	草本、草本作物(旱田)	(Meadow, MD)：包含草本植物覆蓋、部分農田與自然植被鑲嵌（樹木、灌木、草本植物）、部分自然植被鑲嵌（樹木、灌木與草本）、草地以及部分稀疏植被（樹木、灌木、草本植物）等土地覆蓋類型，單位m<sup>2</sup>。  
  (3)	農濕地 (Farm Wetland, FW)：灌溉或淹水的農田，單位m<sup>2</sup>。  
  (4)	森林 (Forest, FO)：闊葉林、針葉林、部分農田與自然植被鑲嵌（樹木、灌木、草本植物）、部分自然植被鑲嵌（樹木、灌木與草本）、部分稀疏植被（樹木、灌木、草本植物）以及水邊與海濱樹林等土地覆蓋類型，單位m<sup>2</sup>。  
  (5)	灌叢 (Bush, BU)：灌叢、樹木或灌木鑲嵌、部分農田與自然植被鑲嵌（樹木、灌木、草本植物）、部分自然植被鑲嵌（樹木、灌木與草本）、部分稀疏植被（樹木、灌木、草本植物）以及常綠灌叢等土地覆蓋類型，單位m<sup>2</sup>。  
  (6)	濕地 (Wetland, WL)：淡水、鹹水或微鹹水具灌木或草本覆蓋區域，單位m<sup>2</sup>。  
  (7)	都市 (Urban Area, UB)：城市區域，單位m<sup>2</sup>。  
  (8)	水體 (Waterbody, WB)：水體，單位m<sup>2</sup>。  
  (9)	裸露地 (Bare Land, BL)：裸露地與部分稀疏植被（樹木、灌木、草本植物）區域，單位m<sup>2</sup>。

  * 其他人文地理因子  
  (1)	道路長度 (Road Length, LROAD)：道路主要資料來源為交通路網數值圖（交通部 2016），道路類型包括國道、省道（含快速公路）、縣道、鄉道、都市道路（6 m以上）、產業道路及無路名道路等既有道路，並與81條林道圖（農業委員會 2016）接合，構成完整路網圖，再計算每個1 km<sup>2</sup>網格內道路長度 (m)。  
  (2)	道路有無 (Presence/absence of Roads, PROAD)：以上述路網圖層換算各1 km<sup>2</sup>網格內有無道路經過，無以0表示，1則代表網格內有道路經過。  
  (3)	最短淡水體距離 (Nearest Distance to Fresh Water, DFW)：計算每個網格中心點距離淡水體距離 (m)，淡水體資料來源為交通路網數值圖提供之河流湖泊圖層（交通部 2016）。  
  (4)	最短鹹水體距離 (Nearest Distance to Salt Water, DSW)：計算每個網格中心點距離海岸線距離 (m)，海岸線以2008年自然與人工海岸線示意圖（內政部營建署 2015）為基準。  

* 以ESRI shapefile & GeoTIFF & ASCII檔提供資料
* 詳細說明：[陳宛均、羅祈鈞、蔡富安、張安瑜。2020。運用開放資料建置臺灣陸域環境因子多時序資料集。台灣生物多樣性研究 22: 13-44。](https://www.tesri.gov.tw/A15_2/content/32207)
