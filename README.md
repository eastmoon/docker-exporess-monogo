# docker-next-express

本專案基本資訊與知識參考[分散運算研究](https://github.com/eastmoon/Research-DistributionCalculation)

此專案為 Node.js 主從應用程式，其伺服器架構如下：

+ Server : jade.js + express.js
+ Database : No-SQL MongoDB

## 執行專案

本專案設有 dockerw 作為操作 docker 介面層，並將部分系統初始、運作流程封裝其中，若無特殊需求請勿任意更改。

此介面層有 .bat ( for windows ) 與 .sh ( for mac, linux ) 請依據作業系統環境使用，後續統一使用 dockerw 作為操作說明

+ windows
```
dockerw -h
```

+ mac, linux
```
. dockerw.sh -h
```

#### 操作主機環境

+ 啟動
```
dockerw up
```
> 開啟此專案於背景模式

+ 關閉
```
dockerw down
```
> 關閉啟動中的容器
