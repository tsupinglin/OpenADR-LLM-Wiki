# 作業繳交文字

## 1. LLM Wiki 主題與簡短介紹
本次主題為「OpenADR × EnergyPlus：建築需量反應入門」。
我使用 6 篇 OpenADR Alliance 與 EnergyPlus 官方資料建立 Wiki，整理 Demand Response、VTN/VEN、OpenADR profiles、EnergyPlus 與兩者的教學整合概念。

## 2. LLM Wiki 連結或成果
【GitHub Pages 網址】/wiki.html

## 3. 教學 HTML 簡報連結
【GitHub Pages 網址】/presentation.html

## 4. loop / graph
取得官方資料 → Ingest / 建 Wiki → 查詢 Wiki → 整理教學 claims → 檢查 claim 是否有 Wiki / Source 對應 → 產生 HTML 簡報 → 檢查初學者是否能理解。

資料不足時回到來源與 Wiki；claim 找不到來源時回到整理步驟；內容太技術時重新整理成「先概念、後術語」。

## 5. 一次實際執行與檢查
整理「OpenADR × EnergyPlus 整合」時，第一次內容容易讓人誤以為「VTN → VEN → EnergyPlus」是 OpenADR 官方規定流程。
重新檢查 Wiki 02、04、06 與 Source S1、S3、S5 後，確認官方資料只分別支持 VTN/VEN 訊息交換與 EnergyPlus 模擬功能。
因此改成「教學 / 研究原型的一種整合方式」，並加入邊界提醒。

## 6. 反思
最常出錯的是「整理 claims」節點。LLM 容易把合理系統設計寫成來源已證明的標準流程。
原本來源檢查放在簡報完成後，後來改成每個 claim 整理後立即檢查是否可對應 Wiki node 與 Source ID。
因此 workflow 增加了 claim → Wiki → Source 三層對照，沒有來源支持的內容先修改或刪除，再進入簡報生成。
