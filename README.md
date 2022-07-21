# 材料
- LilyTiny ATTINY85 微型單片機開發板 10g
- 402025 / 042025 額定容量150mAh 3.7V鋰聚合物電池
- 鋰電池充電開發模組
- 608ZZ 軸承 8*22*7mm
- 洞洞板
- 鱷魚夾
- 焊接工具
- 3D列印(網路上找尋圖檔並購買代印)

# 建置開發板
- 安裝驅動:Digistump Drivers/DPinst64
- Arduino IDE 設定
    - 偏好設定
        - 額外開發版管理員網址:http://digistump.com/package_digistump_index.json
    - 安裝套件
        - 工具->開發版->開發版管理員->安裝Digistump AVR Boards by Digistump
->開發版選擇Digispark(Defult - 16.5mhz)

# *燒錄程式
- 拔掉在電腦上的開發版
- Arduino IDE案上傳會顯示Plug in device now... (will timeout in 60 seconds)
- 插上開發版
- 出現>> Micronucleus done. Thank you!代表燒錄成功

**先燒錄程式必須把GND斷掉電腦才能正常辨識開發板**

# *過程發生問題
- 設定P5輸出並連接LED會有問題，導致電腦無法辨識裝置
- 使用鱷魚夾接一顆燈，不明原因導致開發版差點燒壞 判斷應該是鱷魚夾沒有夾準，*碰到兩個pin腳(危險)* 被燙到不能開玩笑
- 開發板很看心情，很常電腦無法辨識裝置

# Demo
![spinner](./spinner.gif)