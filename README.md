# Neo_Seasons

## 專案簡介
Neo_Seasons 是一個互動式裝置，使用聲音感測器和按鈕來控制 LED 燈光效果。這個專案結合了聲音感測、按鈕控制和可變電阻調光功能。

## 版本資訊
- 當前版本：1.0.0
- 更新日期：2025/04/28

## 硬體需求
- Arduino 開發板
- 聲音感測器
- 兩個按鈕開關
- 可變電阻
- LED 燈
- 連接線

## 接線說明
- 左按鈕：D2
- 右按鈕：D4
- 可變電阻：A1
- 聲音感測器：A0
- LED：D3

## 功能說明
1. 可變電阻控制 LED 亮度
2. 按鈕控制聲音感測功能
3. 聲音感測器可偵測環境音量
4. 序列埠監控視窗可顯示各感測器數值

## 使用說明
1. 上傳程式碼到 Arduino 開發板
2. 開啟序列埠監控視窗（鮑率 9600）
3. 旋轉可變電阻調整 LED 亮度
4. 按住按鈕可啟動聲音感測功能

## 注意事項
- 請確保所有接線正確
- 聲音感測器需要適當的環境光線
- 建議使用 5V 電源供應 