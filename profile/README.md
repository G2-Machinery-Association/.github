# 歡迎來到 臺中市機械業二代協進會 (G2) 

## 🌱「傳承製造底蘊，驅動數位創新」

自 2009 年創立以來，臺中市機械業二代協進會（G2）從最初五位同業二代的聯誼相聚，一路成長為台灣最大、最活躍的機械業二代接班組織，目前匯聚了超過 190 位中部精密機械產業的新世代領袖。

面對全球化挑戰與世代交替，我們秉持著創會以來的核心精神——**「平等、開放、透明、互信、合作」**，在危機中互相扶持，在競爭中攜手「打群架」，共同追求企業經營與精神面的雙重韌性。

## 🚀 從工廠打群架，到雲端大共創：我們的數位轉型之路

隨著工業 4.0 與全球供應鏈的快速變遷，「數位轉型」已成為 G2 家族傳承與企業永續的關鍵命題。我們深知，未來的精密機械不再只是純硬體設備，而是結合軟體大腦的「智慧解決方案」。

這也是為什麼我們選擇 GitHub 作為推動產業數位化的雲端基地：
* **延續互信協作傳統**：將我們線下「同儕共學」的優良傳統，完美轉移至線上的軟體與平台開發，打破單一企業的技術邊界。
* **軟硬整合的價值躍升**：透過高效率的開發工具與協作平台，我們引入軟體工程思維，加速設備附加價值的創新週期。
* **厚實產業韌性**：建立透明、開放的技術文件庫與開發規範，共同建構更具全球競爭力的台灣機械生態系。

## 🤝 協作規範與開源精神

我們期盼透過軟體界的開源精神，加速各成員企業的轉型步伐。如果您是我們的合作夥伴或開發團隊，請遵循以下規範：
1. 所有的開發請務必遵循 **Fork & Pull Request** 流程。
2. 秉持 G2 的「透明與互信」原則，任何合併請求 (PR) 均須經過團隊 Review 審查後才能生效。

## 🛠️ 分支命名規範

請依照此格式命名：`Category/Scope/Description`

#### 1. 第一段：Category (做什麼？)
- `feat` : 增加新功能
- `fix`  : 修復 Bug 錯誤
- `docs` : 修改文件說明
- `refactor` : 整理程式碼 (功能不變)
- `chore` : 改設定、換套件等雜事

#### 2. 第二段：Scope (給誰看？)
- `g2` : **要分享**。準備送回 G2 的通用更新 (要發送 Pull Request)。
- `my` : **不分享**。G2 夥伴公司內部專用的客製化內容 (**嚴禁發送 PR**)。

#### 3. 第三段：Description (具體內容)
- 用簡單英文說明。例如：`login-page` 或 `api-update`

*範例：*
- `fix/g2/login-bug` (修復 G2 的 Bug，要分享)
- `feat/my/special-logo` (公司自用 Logo，不分享)

- ## ⚠️ 核心協作禁令 (Critical Collaboration Rule)

為了確保各成員公司能順利同步 G2 總部的最新更新，並保護各公司的客製化機密，請所有開發人員嚴格遵守以下分支管理規則：

> ### **「保持 main 分支的純淨」**
> 
> 1. **禁止合併私有分支**：嚴禁將 `scope` 為 `my` (私有客製化) 的分支合併進 `main` 分支。
> 2. **main 分支定位**：`main` 僅作為與 G2 總部 (Upstream) 同步之用，必須隨時保持與總部代碼 100% 一致。
> 3. **客製化部署流程**：所有公司專屬的客製化功能（包含 `feat/my/...`），請統一合併至公司專屬的部署分支（建議命名為 **`prod`** 或 **`production`**）。

#### 💡 為什麼要這樣做？
* **無痛更新**：當 `main` 保持純淨時，您可以隨時一鍵點擊 `Sync Fork` 獲取總部功能，而不會產生任何代碼衝突。
* **部署隔離**：您的 Render 或生產環境應對接 `prod` 分支，確保測試完成的客製化功能能安全上線，而不影響核心代碼結構。

## 🔗 了解更多
* **G2 官方網站**：[https://www.g2.org.tw/](https://www.g2.org.tw/)

---
*「以技術連結世代，用軟體升級機械。」*
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
