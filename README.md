# Taiwan-environmental-dataset

## 臺灣陸域環境因子多時序資料集 (A terrestrially and multi-temporally environmental dataset of Taiwan)
* 盤點國內外環境資料集，篩選其中高解析度且訊息最完整之臺灣範圍內資料，運用GIS空間分析建構1km^2網格解析度的「臺灣陸域環境因子多時序資料集」
* 資料集時間橫跨1970~2010年，以每10年為時間分點，共分成5個年代
* 資料範圍含括臺灣整體陸域，並依地理位置分別建立兩個子資料集
  * TWD97/TM2 Zone 121，包含臺灣本島、琉球嶼、北方三島、龜山島、綠島與蘭嶼
  * TWD97/TM2 Zone 119，包含馬祖列島、金門群島、澎湖群島與東沙群島
* 資料集內的環境因子包含8個地形因子、79個氣候因子、9個土地覆蓋因子與4個其他人文地理因子等共100項變數
  * 地形因子  
  (1)	平均海拔 (Mean of Elevation, ELE)：海拔高度的平均值，單位m。  
  (2)	最高海拔 (Maximum Elevation, ELEMAX)：海拔高度的最大值，單位m。  
  (3)	最低海拔 (Minimum Elevation, ELEMIN)：海拔高度的最小值，單位m。  
  (4)	海拔跨幅 (Elevation Range, ELERA)：海拔高度的跨幅，ELEMAX與ELEMIN的差值，單位m。  
  (5)	海拔變化 (Standard Deviation of Elevation, ELESD)：海拔高度的變異程度，單位m。  
  (6)	坡度 (Slope)：單位degree。  
  (7)	坡向 (Aspect)：單位degree。  
  (8)	日射量 (Area Solar Radiation, ASR)：全年日照平均值，單位WH/m2。  
  * 氣候因子
  溫度 (Temperature)：  
   (1)	月均溫 (Monthly mean of daily mean temperature, Temp)：一至十二月每一個月之平均每日均溫，總共12個月份的月均溫圖層 (Temp01-12)，單位℃。  
   (2)	月高溫 (Monthly mean of daily maximum temperature, Tmax)：一至十二月每一個月份之平均每日最高溫，總共12個月份的平均最高溫圖層(Tmax01-12)，單位℃。  
   (3)	月低溫 (Monthly mean of daily minimum temperature, Tmin)：一至十二月每一個月份之平均每日最低溫，總共12個月份的平均最低溫圖層 (Tmin01-12)，單位℃。  
   (4)	每月平均日溫差 (Range of maximum and minimum monthly temperature, Tra)：一至十二月每一個月份之平均每日溫差，總共12個月份的平均日溫差圖層(Tra01-12)，單位℃。  
  降水量 (Precipitation)：  
   (5)	月降水量  (Monthly precipitation sums, Prec)：一至十二月每一個月份之月降水量，總共12個月份的月降水量圖層(Prec01-12)，單位mm。   
  生物氣候變數 (Bioclimatic variables)：  
   (6)	年均溫 (Annual Mean Temperature, Bio01)：全年12個月份月均溫之平均值，單位℃。  
   (7)	平均日溫差 (Mean Diurnal Range, Bio02)：全年12個月份平均日溫差之平均值，每月平均日溫差為當月高溫與當月低溫之差值，單位℃。  
   

  * 土地覆蓋因子  
  (1)	農田 (Farm field, FF)：包含倚賴降雨的農田以及部分農田與自然植被鑲嵌（樹木、灌木、草本植物）土地覆蓋類型，單位m2。  
  (2)	草本、草本作物(旱田)	(Meadow, MD)：包含草本植物覆蓋、部分農田與自然植被鑲嵌（樹木、灌木、草本植物）、部分自然植被鑲嵌（樹木、灌木與草本）、草地以及部分稀疏植被（樹木、灌木、草本植物）等土地覆蓋類型，單位m2。  
  (3)	農濕地 (Farm Wetland, FW)：灌溉或淹水的農田，單位m2。  
  (4)	森林 (Forest, FO)：闊葉林、針葉林、部分農田與自然植被鑲嵌（樹木、灌木、草本植物）、部分自然植被鑲嵌（樹木、灌木與草本）、部分稀疏植被（樹木、灌木、草本植物）以及水邊與海濱樹林等土地覆蓋類型，單位m2。  
  (5)	灌叢 (Bush, BU)：灌叢、樹木或灌木鑲嵌、部分農田與自然植被鑲嵌（樹木、灌木、草本植物）、部分自然植被鑲嵌（樹木、灌木與草本）、部分稀疏植被（樹木、灌木、草本植物）以及常綠灌叢等土地覆蓋類型，單位m2。  
  (6)	濕地 (Wetland, WL)：淡水、鹹水或微鹹水具灌木或草本覆蓋區域，單位m2。  
  (7)	都市 (Urban, UB)：城市區域，單位m2。  
  (8)	水體 (Waterbody, WB)：水體，單位m2。  
  (9)	裸露地 (Bare Land, BL)：裸露地與部分稀疏植被（樹木、灌木、草本植物）區域，單位m2。

  * 其他人文地理因子
* 以ESRI shapefile ＆ ASCII檔提供資料
