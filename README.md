# 這不是行動逢甲

> 更好看的課表(也許。

![Flutter](https://img.shields.io/badge/Flutter-3.24+-02569B?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.0+-0175C2?logo=dart)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📱 專案簡介

整合逢甲大學校務系統的第三方 App，提供：
- **視覺化課表**：連堂自動合併、進行中高光
- **好友課表分享**：一鍵匯出 / 匯入、同堂課好友頭像標記
- **可登多帳號**：支援多帳號
---

---

## 🖼 截圖

> 📌 建議放 3~5 張截圖，分左右兩欄

| 課表頁 | 打卡頁 | 好友課表 | 打卡記錄 |
|---|---|---|---|
| ![課表](docs/screenshots/timetable.png) | ![打卡](docs/screenshots/checkin.png) | ![好友](docs/screenshots/friends.png) | ![記錄](docs/screenshots/history.png) |

---

## 🚀 快速開始

### 環境需求

| 項目 | 版本 |
|---|---|
| Flutter | 3.24+ |
| Dart | 3.0+ |
| Android SDK | API 36 (compileSdk) |
| Android minSdk | 23 |
| JDK | 17 |

### 安裝步驟

```bash
# 1. Clone 專案
git clone https://github.com/你的帳號/redomyfcu.git
cd redomyfcu

# 2. 安裝依賴
flutter pub get

# 3. 設定 Firebase（見下方說明）

# 4. 執行
flutter run
