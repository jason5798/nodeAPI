## NodeAPI

#### RESTful API server application for IOT.

- Maintained by jason_huang@gemteks.com

## 介面概述

  - HTTP狀態碼
    * 401 許可權不足
    * 403 許可權不足
    * 404 項目中不存在
    * 405 無此方法
    * 500 伺服器掛了
    * 200 正常


## 資料結構

  - 各種 CRUD 重要欄位
    * name         - 名稱
    * _id          - mongodb生成的id，一般用於後臺執行CRUD操作
    * id           - 外掛程式生成的自增數位id，類似mysql中的id，具有唯一性，用於前臺獲取資料
    * pid          - 父級ID，用於建立資料表關係，與id欄位映射
    •••

  - 資料組成的三種可能
    * 資料庫真實存在資料
    * mongoose支援的virtual虛擬資料
    * 計算資料


## 文件目录

  - 入口文件

    ```
    index.js -> 主程式

## Todos & Issues



## 開發命令

cd nodeAPI
npm install

# 啟動開發模式（需全域安裝nodemon）

npm run dev

# 生產模式

npm start


