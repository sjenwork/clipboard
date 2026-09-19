# 潭雅神綠園道周邊旅遊資訊

## Objective

在現有 OpenLayers 互動地圖中加入潭雅神綠園道周邊的美食與景點，讓使用者可以先透過地圖 tooltip 快速判斷，再開啟 modal 閱讀旅遊介紹與外部連結。

## Success criteria

- 地圖顯示美食與景點標記，並可用既有分類篩選。
- 點擊標記後顯示名稱、區域、類型與簡短描述。
- Tooltip 提供「旅遊介紹」按鈕，modal 顯示完整介紹、地址、參觀／營業提醒與 Google Maps 連結。
- modal 可由關閉按鈕、背景或 Escape 關閉，並具備基本鍵盤與 aria 支援。
- `index.html` 與 `weekend_map_openlayers_fixed.html` 維持相同內容。

## Verification

- 使用 Node `--check` 驗證內嵌 JavaScript 語法。
- 使用 Chrome 載入本地頁面，確認標記、篩選、tooltip、modal 與外部連結按鈕可操作。
- 確認瀏覽器 console 沒有由本次變更造成的 JavaScript 錯誤。

## Scope boundaries

- 本次只更新靜態地圖資料與互動介面，不引入框架、後端或新套件。
- 營業時間與活動資訊屬於出發前需再次確認的旅遊資料；介面會明確標示提醒。
