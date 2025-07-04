
# 金融創新與資料科學 — 期末專案演講稿

## 🎤 主題：運用資料科學技術預測股價 / 基金報酬  
報告人：D1288066 賴冠蓁、D1376432 劉妍詩

---

## 📍 開場白

各位老師、各位同學大家好，我們是金融創新與資料科學課程的小組報告代表。
我是劉妍詩，這是我的組員賴冠蓁。
我們今天要分享的專案主題是：「運用資料科學技術預測股價與基金報酬」。

---

## ① 研究動機、目的與問題

### 研究動機：
1. 傳統技術分析容易受到人為主觀干擾。
2. 資料科學與AI技術提供了新的可能性。

### 研究目的：
- 探討資料科學是否能有效預測報酬。
- 找出影響報酬的關鍵因子。

### 研究問題：
1. 能否用技術指標準確預測短期報酬？
2. 哪些指標對預測效果最顯著？
3. LSTM是否優於傳統模型？
4. 不同市場情境下，模型是否穩定？

---

## ② 資料來源與前處理流程

### 資料來源：
- Yahoo Finance 歷史股價
- 技術指標（MA、MACD、RSI）
- 社群情緒資料：PTT、新聞

### 前處理流程：
- 缺值補齊與標準化
- 滑動視窗生成訓練樣本
- 整合技術指標與情緒資料

---

## ③ 模型方法介紹

1. **傳統統計模型**：ARIMA、Prophet（本次實作）
2. **機器學習模型**：Random Forest、XGBoost（未實作）
3. **深度學習模型**：LSTM（未實作）

---

## ④ 實驗設計與評估指標

- 時間序列資料切割：80%訓練、20%測試
- 使用滑動視窗觀察趨勢
- 交代超參數設定與訓練次數

### 評估指標：
- 回歸問題：MAE、RMSE
- 分類問題：Accuracy、F1-score

---

## ⑤ 實驗結果分析

- Prophet表現穩定，預測結果平滑貼近實際走勢。
- 對重大消息反應較弱，但整體準確性良好。
- 可視化清楚，適合新手與實務應用。

---

## ⑥ 研究發現與貢獻

### 研究發現：
- 能夠預測台股短期趨勢
- 視覺化清晰，預測區間具參考價值
- 訓練快速，模型易上手

### 研究貢獻：
- 建立預測流程範本
- 將Prophet實作於台股
- 非程式背景者也能理解並使用

---

## ⑦ 結論與未來展望

### 結論：
- Prophet預測台積電股價30日趨勢
- 預測具參考價值與風險評估能力

### 未來展望：
1. 納入更多資料來源（情緒、量能）
2. 比較LSTM與XGBoost模型
3. 開發投資小工具

---

## 💬 結語

以上是我們的報告內容，感謝各位聆聽，也希望未來能將資料科學更多應用於金融實務。

