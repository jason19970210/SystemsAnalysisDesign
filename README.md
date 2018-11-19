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
        - **UML Unified Modeling Language**：by Jacobson, 1997
        - 基本特性：封裝、繼承、多型
### 1-2 軟體發展程序
- 規範式程序 Prescriptive Process / 計畫驅動程序 Plan-Driven Process
    - 事先定義好「階段」
    - 上一階段完成才能進行下一階段
    - 每一階段完成後需得到使用者確認
- 敏捷式程序 Agile Process / 適應式程序 Adaptive Process
    - 反覆與漸層式
    - 強調專案的快速回應能力
        - 增量發行 Incremental Planning：客戶需求是以一個個增量模組開發
        - 小版本發行 Small Releases：首要功能先開發，陸續發布更新增加功能
        - 測試驅動 Test-First Driven：先依據規格撰寫測試個案，不斷以這些測試個案測試直到通過
        - 重構 Refactoring：改善程式結構但維持原有功能
        - 配對程式發展 Pair Programming：兩人一組開發，一人撰寫程式，一人負責測試
- 瀑布式軟體發展程序 Waterfall Software Development Process
    - 五個階段：需求
                |- 分析  
                    |- 設計  
                        |- 製作  
                            |- 維護  
    - 階段工作完成才能繼續發展下一階段
    - 某階段工作完成後 **凍結**，不允許更改 
### 1-3 系統分析師與系統分析設計之工作