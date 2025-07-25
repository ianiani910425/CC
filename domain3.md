# 📚 CC(domain3)
## 🛡️ 控制措施與風險對應表（Controls vs Risks）

資訊安全控制措施的設計，是為了應對特定類型的威脅或資安風險。本表對照**實體安全（Physical Security）**與**邏輯存取控制（Logical Access Control）**，及其所緩解的風險類型。

---

### 🧱 實體控制（Physical Controls）

| 控制措施               | 對應風險/威脅                       |
|------------------------|-------------------------------------|
| 門禁卡、門鎖           | 未經授權進入辦公區、機房             |
| 監視系統（CCTV）       | 事後無法追蹤入侵者行動               |
| 識別證、訪客登記       | 對人員身分缺乏驗證                   |
| 警報系統               | 無法即時察覺物理入侵事件             |
| UPS、發電機            | 斷電導致系統中斷、資料遺失           |
| 環境控制（空調、滅火） | 設備過熱、火災造成業務與資料中斷     |
| 保全巡邏               | 當場無人發現可疑行為                 |

---

### 🧠 邏輯控制（Logical Controls）

| 控制措施                     | 對應風險/威脅                           |
|------------------------------|-----------------------------------------|
| 使用者帳號與密碼             | 未授權存取系統                         |
| 多因素認證（MFA）            | 密碼洩漏導致帳號被盜用                 |
| 權限控管（RBAC、ABAC）       | 權限過高造成濫用或資料誤存取           |
| 加密（傳輸/儲存）             | 資料在傳輸或遺失裝置中被攔截或竊取     |
| 防火牆 / IDS / IPS           | 外部網路攻擊、惡意軟體入侵             |
| 系統日誌 / 稽核              | 無法追蹤帳號活動、內部濫用行為         |
| 自動鎖定機制（Idle Timeout） | 離開座位時裝置被他人操作               |
| 單一登入（SSO）              | 多系統密碼重複使用、管理複雜性         |

---

### 📌 小結（設計原則對應）

| 控制類別     | 主要目標             | 對應原則（CIA）     |
|--------------|----------------------|----------------------|
| 實體控制     | 防止實體存取與環境破壞 | 可用性（A）、機密性（C） |
| 邏輯控制     | 管理帳號與數位資源     | 機密性（C）、完整性（I） |

---

### 🧠 CC 考試補充提示

- ✅ 考試常出現「給你一種風險，請問應該採取哪一類控制措施？」
- ✅ 生物辨識、門禁、加密、MFA 常被混淆為同一類控制，要判斷**控制場域**。
- ✅ 控制措施的設計目的可能涵蓋多個 CIA 原則，例如：加密同時保護**機密性與完整性**。

---
