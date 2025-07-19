## 研究假设模型图 (Research Hypothesis Model)

这是一个用于研究社交媒体心理学科普内容对受众影响的实验模型。

```mermaid
graph TD
    subgraph 自变量 (Independent Variable)
        IV[科普内容类型<br>Type of Content<br>1. 泛心理学 (Pop Psych)<br>2. 专业心理学 (Pro Psych)<br>3. 中性 (Neutral)]
    end

    subgraph 因变量 (Dependent Variables)
        DV1[状态焦虑<br>State Anxiety]
        DV2[专业心理求助意愿<br>Help-Seeking Intentions]
    end

    subgraph 调节变量 (Moderator)
        MOD[认知需求<br>Need for Cognition (NFC)]
    end

    subgraph 控制变量/协变量 (Covariates)
        COV1[前测状态焦虑<br>Pre-test State Anxiety]
        COV2[特质焦虑<br>Trait Anxiety]
    end

    IV -- H1 & H2 --> DV1
    IV -- H4 --> DV2
    MOD -- H3 --> IV--H1 & H2--DV1

    COV1 -.-> DV1
    COV2 -.-> DV1
    COV2 -.-> DV2

    style IV fill:#cce5ff,stroke:#333,stroke-width:2px
    style DV1 fill:#d5e8d4,stroke:#333,stroke-width:2px
    style DV2 fill:#d5e8d4,stroke:#333,stroke-width:2px
    style MOD fill:#fff2cc,stroke:#333,stroke-width:2px
    style COV1 fill:#f5f5f5,stroke:#666,stroke-width:1px,stroke-dasharray: 5 5
    style COV2 fill:#f5f5f5,stroke:#666,stroke-width:1px,stroke-dasharray: 5 5
