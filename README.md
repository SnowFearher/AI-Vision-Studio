# AI Vision Studio

## 專題介紹

本專題以 Python 為主要開發語言，結合 Gradio、OpenCV、NumPy、Pillow 與 Matplotlib，開發一套互動式影像處理與人臉分析系統，並使用 ChatGPT 輔助程式開發、除錯及功能整合。

## 核心功能

1. **影像載入與解析**：支援 PNG、JPG/JPEG、BMP，顯示解析度、色彩模式、通道數及檔案大小。
2. **RGB/YUV 色彩分析**：提供 Original、R、G、B、Y、U、V 通道檢視，並同步產生像素強度直方圖。
3. **自訂 Kernel 與 PSNR**：支援自訂卷積矩陣、Normalization、邊界處理、濾波前後比較及 PSNR 計算。
4. **人臉偵測**：整合 OpenCV DNN SSD 與 YuNet 雙模型，顯示人臉邊界框、數量、座標及 Confidence Score。

## 開發技術

- Python
- Google Colab
- Gradio
- OpenCV
- NumPy
- Pillow
- Matplotlib
- ChatGPT（AI 協作）

## 執行方式

1. 開啟 Google Colab。
2. 載入本儲存庫的 `.ipynb` 程式。
3. 依照筆記本中的步驟安裝套件並載入模型。
4. 執行所有必要的程式區塊。
5. 開啟 Gradio 介面，開始使用 AI Vision Studio。

## 線上程式

Google Colab：
https://colab.research.google.com/drive/1gh93FrV58SegCam6Irz1cWg0NObdKiRc?usp=sharing

Gradio Live Demo（暫時連結）：
https://fb070a69147ac6306c.gradio.live/

## 專題成果

本系統已完成 RGB/YUV 色彩分析、自訂卷積核濾波與 PSNR 計算，並透過 SSD + YuNet 雙模型改善多人臉偵測表現。在六人合照測試中，成功偵測六張人臉。

## 注意事項

Gradio Live Demo 為暫時分享連結，可能因 Google Colab 執行階段結束而失效。建議透過 Colab 筆記本重新執行系統。
