# 1st 2026 年 4 月 8 日（香港時間）
# 📰 AI 週報 · 2026 年 4 月 8 日（香港時間）

**本週焦點**：Anthropic、Google、Microsoft 同期出招，OpenAI GPT-6 也在倒數計時。

---

## 📌 目錄
- [🔥 重大發布](#-重大發布)
- [💰 行業動態](#-行業動態)
- [🛠️ 工具＆開發者影響](#️-工具開發者影響)
- [⚠️ 政策＆隱私警示](#️-政策隱私警示)
- [🎯 本週三條關鍵趨勢](#-本週三條關鍵趨勢)

---

## 🔥 重大發布

### 1. Anthropic 推出 Claude Mythos Preview（限定網絡安全防禦）

**發生了什麼**  
Anthropic 發布旗下迄今最強模型 **Claude Mythos Preview**，但不對外公開——僅限「Project Glasswing」計畫的 40+ 合作夥伴使用（包括 Amazon、Apple、Google、Microsoft、NVIDIA、CrowdStrike 等）。  

模型在 SWE-bench Verified 達到 **93.9%**，能自主發現主流作業系統與瀏覽器中的大量零日漏洞。Anthropic 同時投入 1 億美元使用點數及 400 萬美元捐贈給開源安全組織。

**為什麼重要**  
這是業界首次主動限制頂級模型發布，明確表示「太強了，怕被惡用」。反映 AI 能力已觸及監管紅線，並開創「**受控發布**」的新範例。

**可能影響**  
- 企業安全團隊、滲透測試商、政府機構將是主要受益者  
- 攻防博弈加速，AI 自動找漏洞 → AI 即時修補  
- 長遠可能走向「模型能力分級許可」制度

**來源**： [Anthropic Glasswing](https://www.anthropic.com) · [TechCrunch](https://techcrunch.com) · [CNBC](https://cnbc.com)

---

### 2. Google 開源 Gemma 4，邊緣 AI 全面提速

**發生了什麼**  
Google DeepMind 於 4 月 2 日發布 **Gemma 4** 開源模型家族（E2B、E4B、26B MoE、31B Dense）。31B 版本在 Arena AI 榜單位居開源模型第 3。  

採用 Apache 2.0 授權，可在 Android 手機、筆電 GPU 等本地運行。同步推出 **AI Edge Gallery** iOS App，讓 iPhone 可本地執行 Gemma 4。

**為什麼重要**  
把 Gemini 3 的研究成果以開源形式下放，開發者能以極低成本獲得接近旗艦的能力。邊緣 AI 真正走向實用（隱私保護、離線使用、零 API 費用）。

**可能影響**  
企業可微調垂直領域模型；移動端 AI 應用（健康、教育、即時翻譯）大幅提升；進一步壓縮開源與閉源模型差距。

**來源**： [Google Blog](https://blog.google) · [Developers Blog](https://developers.googleblog.com)

---

### 3. Microsoft 自研三款 MAI 多模態基礎模型上線

**發生了什麼**  
Microsoft MAI 團隊（Mustafa Suleiman 領導）發布：  
- **MAI-Transcribe-1**：支援 25 語言語音轉文字，速度為 Azure Fast 的 2.5 倍  
- **MAI-Voice-1**：1 秒生成 60 秒音頻，支援自訂聲線  
- **MAI-Image-2**：文字生成圖片/影片模型  

三款均上架 Microsoft Foundry，定價低於 Google 與 OpenAI。

**為什麼重要**  
Microsoft 正式建立獨立多模態模型棧，不再只依賴 OpenAI，形成技術護城河。

**可能影響**  
企業擁有原生 Microsoft 音訊、語音、圖像解決方案；Azure 從「轉售平台」轉向自有產品；可能施壓 OpenAI 在定價與授權上讓步。

**來源**： [TechCrunch](https://techcrunch.com)

---

## 💰 行業動態

### 4. Anthropic 年化收入突破 300 億美元，擴大 Google TPU 布局

**發生了什麼**  
Anthropic 年化收入（run-rate）已超過 **300 億美元**（兩個月前僅約 90 億）。每年消費超過 100 萬美元的企業客戶超過 1,000 家。  

與 Google Cloud 及 Broadcom 簽署協議，鎖定 3.5GW 下一代 TPU 算力（2027 年起上線）。

**為什麼重要**  
增長速度驚人，顯示企業採購進入爆發期。算力鎖定成為未來模型能力的關鍵護城河。

**可能影響**  
Anthropic 有望拉開與其他 AI 公司的收入差距；為潛在 IPO 提升估值；加速市場集中化。

**來源**： Anthropic 官方

### 5. OpenAI 代號「Spud」的 GPT-6 預計 4 月中旬發布

**發生了什麼**  
多方消息指出，OpenAI 下一代旗艦模型（內部代號 **Spud** / GPT-6）已完成預訓練，預計 **4 月 14 日前後** 發布。傳聞將把 ChatGPT、Codex、Atlas 合併為「超級 App」。

**為什麼重要**  
需快速回應 Anthropic 的 Mythos 發布；兩家公司均傳出 IPO 計畫，旗艦模型是重要說服工具。

**可能影響**  
短期內最受關注的 AI 事件；GPT 系列 vs. Claude 系列對比將再次成為焦點；市場格局可能快速變化。

> ⚠️ 注意：此消息仍屬爆料，尚未獲 OpenAI 官方確認。

---

## 🛠️ 工具＆開發者影響

### 6. Cursor 3 發布：IDE 降格，AI Agent 升主角

**發生了什麼**  
Cursor 推出 3.0 版（代號 Glass）：傳統程式碼編輯器降為「備用介面」，主介面改為 **Agent 管理主控台**。新增 Cloud Handoff、多 repo 工作區等功能。

**為什麼重要**  
明確宣告 AI 編程工具從「輔助寫碼」轉向「管理 AI Agent」。

**可能影響**  
開發工作流 Agent 化；人的角色轉向審核與方向指導；其他 IDE 預計跟進。

**來源**： [The New Stack](https://thenewstack.io)

---

## ⚠️ 政策＆隱私警示

### 7. GitHub Copilot 即將用你的程式碼訓練模型（4 月 24 日生效）

**發生了什麼**  
4 月 24 日起，Copilot Free/Pro/Pro+ 用戶的互動資料（輸入、輸出、程式碼片段）**預設** 用於模型訓練。私有倉庫原始碼不受影響。  

可在 **Settings → Copilot → Privacy** 提前退出。

**為什麼重要**  
影響全球數千萬開發者，是近年最大規模的 AI 訓練資料政策調整。

**實際影響**  
若程式碼含商業邏輯、API 金鑰等敏感資訊，請立即退出。建議企業考慮本地部署方案（如 Gemma 4）。

**來源**： [GitHub Blog](https://github.blog)

---

## 🎯 本週三條關鍵趨勢

1. **「強模型 ≠ 公開模型」正成新常態**  
   Mythos 的受控發布標誌 AI 安全治理進入實際操作階段。

2. **開源陣營全面上攻**  
   Google Gemma 4 等發布，讓「免費本地跑旗艦級能力」成為現實，企業採購邏輯正在重塑。

3. **開發者主權受壓**  
   GitHub Copilot 資料政策提醒大家：免費工具的隱性成本，可能就是你的程式碼與思維模式成為訓練資料。

---

**如需更深入分析**（開發者角度 / 企業採購角度 / 投資角度），歡迎在 repo Issues 或 Discussions 提出！

---

*最後更新：2026 年 4 月 8 日*
