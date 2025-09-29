
# 資深系統級安全與底層開發工程師 (17 年經驗)

| 姓名 / 聯絡資訊 |
| :--- |
| 徐碩君 / nnbsxel7478@gmail.com |

---

## 專業摘要 (Professional Summary)

一位具備 **17 年**軟體研發經驗的資深工程師，專精於**Windows 系統級安全開發 (11 年經驗)** 與**嵌入式 Linux 韌體/驅動程式**。

* **核心安全專長：** 精通 **Windows 核心模式 (Kernel Mode)** 與**使用者模式 (User Mode)** 開發，具備設計與實作 **Exploit 防護、高效能行為監控框架**及惡意程式防禦機制的實戰經驗。
* **底層系統與網路：** 熟悉 **Linux Driver** 開發、**Bootloader (RedBoot)** 移植、**網路協定 (IPv6, Modbus TCP, EtherNet/IP)** 實作與系統效能優化。
* **工程卓越：** 具備 x64/ARM64 跨平台移植能力、**CI/CD 自動化建置**、**單元測試導入**及創新的系統穩定性優化經驗。

---

## 核心技術專長 (Core Technical Skills)

| 類別 | 技術細節 |
| :--- | :--- |
| **程式語言** | C, C++, Python |
| **作業系統與平台** | **Windows Kernel/User Mode (Minifilter, API Hook)**, Embedded Linux, eCos, ARM64/x64 |
| **資安與系統** | Exploit Shield, BSoD Prevention Logic, Fileless Attack Detection, GitHub Actions (CI/CD), Unit Testing |
| **網路與通訊** | IPv6, IGMP, Modbus TCP, EtherNet/IP (ODVA Certified), Ethernet/Wireless Bridge, Linux Networking |

---

## 工作經歷 (Professional Experience)

### 1. Windows 安全軟體工程師 (Windows Security Software Engineer)
**趨勢科技 (Trend Micro)** $\mid$ **期間：** 11 年 (約 2014 年 3 月 - 至今)

#### 【資安核心機制與系統可靠性】

* **Exploit Shield 開發：** 設計並實作**使用者模式 API Hook 模組**，建立 **Exploit Shield 機制**，有效偵測並攔截多種**新型態 Exploit 攻擊**，顯著強化端點防護能力。
* **系統級穩定性創新 (BSoD 預防)：** 開發並實作**BSoD 迴圈預防機制**，透過**紀錄與分析系統崩潰 (BSoD) 狀態**，主動避免因自家或其他廠商驅動程式的**相容性問題**導致的系統癱瘓，大幅提升產品穩定性。
* **跨平台移植：** 成功將**核心 API Hook 機制**與使用者模式模組完整移植至 **Windows on ARM64** 平台，大幅擴展產品的相容性與市場覆蓋。
* **硬體整合優化：** 領導整合 **Intel® Threat Detection Technology (TDT)**，利用硬體級加速功能，**提升產品的惡意程式偵測效率與效能**。

#### 【架構、DevOps 與品質優化】

* **高效能監控框架：** 設計並實作**同步/非同步**事件處理流程，建立具備高度彈性的**動態配置管理**與**外掛系統**，確保高吞吐量下的行為監控效率。
* **DevOps 與品質：** **主導**建立基於 **GitHub Actions** 的完整 **CI/CD 自動化流程**。**導入單元測試 (Unit Test)** 至核心模組，並建立**數據自動化分析流程**，以**取代人工處理**，加速問題發現與解決，有效提升程式碼品質與產品穩定性。
* **技術合作：** 參與 **Microsoft 新一代 Windows Endpoint Security Platform** 的設計討論，提供關鍵性回饋與錯誤報告，確保產品與 OS 平台的深度整合。

### 2. 軟體研發工程師 (Software R&D Engineer)
**四零四科技股份有限公司 (Moxa)** $\mid$ **期間：** 6 年 (約 2007 年中 - 2013 年 12 月)

#### 【嵌入式系統韌體與網路協定開發】

* **工業網路協定領導：** **獨立**實作 **EtherNet/IP 協定棧**並**成功取得 ODVA 國際認證**；**獨立**於 Linux 平台上完成 **Modbus TCP 協定堆疊**實作。
* **系統效能優化：** **大幅優化** eCos 上的 Serial-to-TCP 傳輸路徑，將極限傳輸效率**提升超過 120% (從 40kbit/s 提升至 89kbit/s)**。深入優化 **無線網路漫遊 (Roaming) 邏輯**，將斷線時間從 **3 秒以上**降低至 **400ms 以下**。
* **跨平台移植與成本優化：** 主導**硬體平台遷移**專案，將舊有 x86 平台成功移植至 RDC 1610C 平台，**提升系統效率並達成專案成本目標**。

#### 【新平台與驅動程式開發】

* **新平台底層移植：** 成功將 **Linux Kernel** 與 **RedBoot (Bootloader)** 移植到基於 **Freescale i.MX25** 的新硬體平台。
* **底層驅動開發：** 開發 **MU150 晶片 Serial Driver**；修改 Ethernet Switch Driver (DSA Driver)，關閉 Kernel 轉發邏輯，改由 Switch 晶片**硬體自行處理**，**有效降低網路流量對 CPU 的資源佔用**。

---

## 教育背景 (Education)

**國立台灣科技大學 (National Taiwan University of Science and Technology)**
* 電機工程學系 (Electrical Engineering) $\mid$ 畢業於 2008 年

