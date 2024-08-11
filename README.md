# MySpotViewer - 我的景點地圖

[English version below](#myspotviewer---my-spot-map)

## 專案概述

MySpotViewer 是一個網頁應用程式，專為喜愛收藏和探索台灣各地景點的用戶設計。這個工具允許用戶載入、查看和探索他們個人收藏的地點，並在台灣地圖上直觀地呈現這些地點的相對位置。

立即使用 MySpotViewer：[https://benfzc.github.io/MySpotViewer/](https://benfzc.github.io/MySpotViewer/)

## 主要功能

- 在台灣地圖上視覺化顯示個人收藏的景點
- 通過上傳 JSON 文件輕鬆添加自定義景點
- 互動式地圖，支持縮放和平移
- 顯示景點名稱和可選的描述信息
- 簡潔直觀的用戶界面

## 如何使用

1. 訪問 MySpotViewer 應用程式網頁：[https://benfzc.github.io/MySpotViewer/](https://benfzc.github.io/MySpotViewer/)
2. 準備一個包含您想標記景點的 JSON 文件。文件格式應為：
   ```json
   [
     {"name": "恆春縣城西門", "lat": 22.00570023264387, "lon": 120.74358407686096, "description": "屏東景點"},
     {"name": "日月潭", "lat": 23.8496, "lon": 120.9131, "description": "南投景點"},
     {"name": "望幽谷", "lat": 25.145908850060298, "lon": 121.79833285218314, "description": "基隆景點"},
     {"name": "三仙台", "lat": 23.1259512664231, "lon": 121.413101560135, "description": "台東景點"}
   ]
   ```
3. 點擊 "選擇 JSON 文件上傳我的景點" 按鈕。
4. 選擇您準備好的 JSON 文件。
5. 上傳成功後，地圖將自動更新顯示您的景點位置。

---

# MySpotViewer - My Spot Map

## Project Overview

MySpotViewer is a web application designed for users who love to collect and explore various locations across Taiwan. This tool allows users to load, view, and explore their personal collection of spots, visualizing their relative positions on a map of Taiwan.

Use MySpotViewer now: [https://benfzc.github.io/MySpotViewer/](https://benfzc.github.io/MySpotViewer/)

## Key Features

- Visualize personal collection of spots on a Taiwan map
- Easily add custom locations by uploading a JSON file
- Interactive map with zoom and pan capabilities
- Display spot names and optional descriptions
- Clean and intuitive user interface

## How to Use

1. Access the MySpotViewer application webpage: [https://benfzc.github.io/MySpotViewer/](https://benfzc.github.io/MySpotViewer/)
2. Prepare a JSON file containing the spots you want to mark. The file format should be:
   ```json
   [
     {"name": "Hengchun County West Gate", "lat": 22.00570023264387, "lon": 120.74358407686096, "description": "Pingtung attraction"},
     {"name": "Sun Moon Lake", "lat": 23.8496, "lon": 120.9131, "description": "Nantou attraction"},
     {"name": "Wangyou Valley", "lat": 25.145908850060298, "lon": 121.79833285218314, "description": "Keelung attraction"},
     {"name": "Sanxiantai", "lat": 23.1259512664231, "lon": 121.413101560135, "description": "Taitung attraction"}
   ]
   ```
3. Click the "Choose JSON File to Upload My Spots" button.
4. Select your prepared JSON file.
5. After successful upload, the map will automatically update to display your spot locations.