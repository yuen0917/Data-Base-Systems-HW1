# 通訊錄管理系統

這是一個簡單的通訊錄管理系統，使用Python開發，支援基本的CRUD操作（創建、讀取、更新、刪除）以及搜尋功能。

## 功能特點

- 新增聯絡人資料（姓名、電話、電子郵件、地址）
- 瀏覽所有聯絡人資料
- 更新現有聯絡人資料
- 刪除聯絡人資料
- 依姓名搜尋聯絡人

## 資料欄位限制

- 姓名：最多10個字元
- 電話：最多15個字元
- 電子郵件：最多20個字元
- 地址：最多50個字元

## 系統需求

- Python 3.6 或更高版本
- 必要的Python套件：
  - tkinter (通常包含在Python標準庫中)
  - ttkbootstrap==1.10.1
  - pillow==10.2.0

## 安裝步驟

1. 安裝Python套件：

```bash
pip install ttkbootstrap==1.10.1 pillow==10.2.0
```

## 使用方式

1. 執行程式：

```bash
python address_book.py
```

1. 依照選單指示進行操作：
   - 輸入數字1-5選擇對應功能
   - 輸入0退出程式

## 資料儲存

- 所有聯絡人資料會自動儲存在 `contacts.json` 檔案中
- 程式啟動時會自動載入既有的聯絡人資料
- 每次新增、更新或刪除操作後都會自動儲存
