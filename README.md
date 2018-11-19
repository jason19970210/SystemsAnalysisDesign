# SystemsAnalysis-Design 系統分析與設計(1) 

+ ftp://163.25.117.117/sywan/System Analysis/undergrad
> No more Update

## Ch1 系統分析設計概觀
### 1-1 認識系統分析與其重要性
- 軟體系統的普遍性
    - 手機及汽車之嵌入式軟體
    - 企業內部的各種管理資訊系統
    - 高速公路收費系統、悠遊卡系統、通關系統
- 軟體系統可能遇到的問題
    - 使用者對於需求無法明確說明
    - 環境變動過於快速
    - 專案管理不良
- 系統分析：分析師去了解和明確敘述出資訊系統應該完成之工作的一組活動
- 系統設計：分析師定義和描述系統解決需求細節的一組活動
- 系統分析設計 **方法論**
    - **結構化方法 Structured Methodology**
        - 結構化分析、結構化設計、結構化程式設計
        - 簡化設計，也亦於未來維護工作
    - **物件導向方法 Objected-Oriented Methology**
        - **統一程序 UP, Unified Process**：by Booch & Rumbaugh, 1994
            - 基本特性：反覆式發展、反覆並漸增式發展、接受改變並調整與適應、時間區間概念
            - 統一程序階段：
                - 起始階段 Inception：
                - 詳細闡述階段 Elaboration：
                - 建構階段 Construction：
                - 轉換階段 Transition：
        - **UML Unified Modeling Language**：by Jacobson, 1997
        - 基本特性：封裝、繼承、多型
### 1-2 軟體發展程序
- 規範式程序 Prescriptive Process / 計畫驅動程序 Plan-Driven Process
    - 事先定義好「階段」
    - 上一階段完成才能進行下一階段
    - 每一階段完成後需得到使用者確認
- 敏捷式程序 Agile Process / 適應性程序 Adaptive Process
    - 反覆與漸層式
    - 強調專案的快速回應能力
        - 增量發行 Incremental Planning：客戶需求是以一個個增量模組開發
            - 增量模組：因應需求不確定與環境變化
        - 小版本發行 Small Releases：首要功能先開發，陸續發布更新增加功能
        - 測試驅動 Test-First Driven：先依據規格撰寫測試個案，不斷以這些測試個案測試直到通過
        - 重構 Refactoring：改善程式結構但維持原有功能
        - 配對程式發展 Pair Programming：兩人一組開發，一人撰寫程式，一人負責測試
- 瀑布式軟體發展程序 Waterfall Software Development Process
    - 五個階段：  
        - 需求：了解使用者之目標與需求
            - 功能性需求 Functional Requirement
            - 分功能性需求 Non-functional Requirement
        - 分析：使用 **系統規格書** 紀錄使用者需求與限制
        - 設計：建立系統架構與細部模組，並對每個模組進行描述，稱為 **系統設計書**
        - 製作
            - 程式撰寫：將系統設計書轉為程式模組
            - 測試：進行單元測試、整合測試、功能測試、系統測試
            - 上線：將測試完成的系統放置實際環境中運行
        - 維護：上線後所進行的工作
            - 正確性維護：修改系統錯誤
            - 適應性維護：因應環境變化
            - 完美性維護：提升系統效能
            - 預防性維護：預防未來環境改變
    - 階段工作完成才能繼續發展下一階段
    - 某階段工作完成後 **凍結**，不允許更改 
### 1-3 系統分析師與系統分析設計之工作
- 應具備能力
    - 資訊技術能力
    - 邏輯分析能力
    - 企業領域知識
    - 人際溝通技能
- 系統分析工作
    - 需求調查
    - 可行性研究
    - 定義需求
    - 撰寫規格書
    - 擬定可行方案
    - 管理者確認
- 系統設計工作
    - 系統架構設計
    - 系統功能設計
    - 系統介面設計
    - 資料庫設計
- 系統分析書：
    - 系統架構描述
    - 子系統功能描述
    - 個別類別或模組敘述
    - 介面設計
    - 報表設計
    - 實作與測試計畫
    - 實際運行環境說明