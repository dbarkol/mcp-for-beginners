<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "5dc09d7099d2f09f3e472bc8f073622d",
  "translation_date": "2025-06-23T14:20:32+00:00",
  "source_file": "README.md",
  "language_code": "tw"
}
-->
![MCP-for-beginners](../../translated_images/mcp-beginners.2ce2b317996369ff66c5b72e25eff9d4288ab2741fc70c0b4e523d1ae1e249fd.tw.png) 

[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/graphs/contributors)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/issues)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/mcp-for-beginners.svg)](https://GitHub.com/microsoft/mcp-for-beginners/pulls)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/mcp-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/mcp-for-beginners/watchers)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/mcp-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/mcp-for-beginners/fork)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners?style=social&label=Star)](https://GitHub.com/microsoft/mcp-for-beginners/stargazers)


[![Microsoft Azure AI Foundry Discord](https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.com/invite/ByRwuEEgH4)


按照以下步驟開始使用這些資源：
1. **Fork 該儲存庫**：點擊 [![GitHub forks](https://img.shields.io/github/forks/microsoft/mcp-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/mcp-for-beginners/fork)
2. **Clone 該儲存庫**：   `git clone https://github.com/microsoft/mcp-for-beginners.git`
3. [**加入 Azure AI Foundry Discord，與專家及其他開發者交流**](https://discord.com/invite/ByRwuEEgH4)


### 🌐 多語言支援

#### 透過 GitHub Action 支援（自動且持續更新）

# 🚀 Model Context Protocol (MCP) 初學者課程

## **透過 C#、Java、JavaScript、Python 和 TypeScript 的實作範例學習 MCP**

## 🧠 Model Context Protocol 課程概覽

**Model Context Protocol (MCP)** 是一個前沿框架，旨在標準化 AI 模型與客戶端應用程式之間的互動。這套開源課程提供有結構的學習路徑，包含實際的程式碼範例與真實案例，涵蓋 C#、Java、JavaScript、TypeScript 和 Python 等熱門程式語言。

無論你是 AI 開發者、系統架構師或軟體工程師，本指南都是你掌握 MCP 基礎與實作策略的完整資源。

## 🔗 官方 MCP 資源

- 📘 [MCP Documentation](https://modelcontextprotocol.io/) – 詳細教學與使用者指南  
- 📜 [MCP Specification](https://spec.modelcontextprotocol.io/) – 協議架構與技術參考  
- 🧑‍💻 [MCP GitHub Repository](https://github.com/modelcontextprotocol) – 開源 SDK、工具與程式範例  

## 🧭 MCP 課程總覽

<details>
  <summary><strong>00-03：基礎篇</strong></summary>

- **00. MCP 簡介**  
  介紹 Model Context Protocol 及其在 AI 流程中的重要性。 [閱讀更多](./00-Introduction/README.md)
- **01. 核心概念解析**  
  深入探討 MCP 的核心概念。 [閱讀更多](./01-CoreConcepts/README.md)
- **02. MCP 的安全性**  
  安全威脅與最佳實踐。 [閱讀更多](./02-Security/README.md)
- **03. MCP 入門指南**  
  環境設定、基本伺服器/客戶端與整合。 [閱讀更多](./03-GettingStarted/README.md)
</details>

<details>
  <summary><strong>03.x：實作實驗室</strong></summary>

- **3.1. 第一個伺服器** – [指南](./03-GettingStarted/01-first-server/README.md)
- **3.2. 第一個客戶端** – [指南](./03-GettingStarted/02-client/README.md)
- **3.3. 搭配 LLM 的客戶端** – [指南](./03-GettingStarted/03-llm-client/README.md)
- **3.4. 使用 Visual Studio Code 消費伺服器** – [指南](./03-GettingStarted/04-vscode/README.md)
- **3.5. 使用 SSE 建立伺服器** – [指南](./03-GettingStarted/05-sse-server/README.md)
- **3.6. HTTP 串流** – [指南](./03-GettingStarted/06-http-streaming/README.md)
- **3.7. 使用 AI 工具包** – [指南](./03-GettingStarted/07-aitk/README.md)
- **3.8. 測試你的伺服器** – [指南](./03-GettingStarted/08-testing/README.md)
- **3.9. 部署你的伺服器** – [指南](./03-GettingStarted/09-deployment/README.md)
</details>

<details>
  <summary><strong>04-05：實務與進階</strong></summary>

- **04. 實務應用**  
  SDK、除錯、測試與可重用提示模板。 [閱讀更多](./04-PracticalImplementation/README.md)
- **05. MCP 進階主題**  
  多模態 AI、擴展性、企業應用。 [閱讀更多](./05-AdvancedTopics/README.md)
- **5.1. MCP 與 Azure 整合** – [指南](./05-AdvancedTopics/mcp-integration/README.md)
- **5.2. 多模態** – [指南](./05-AdvancedTopics/mcp-multi-modality/README.md)
- **5.3. MCP OAuth2 示範** – [指南](./05-AdvancedTopics/mcp-oauth2-demo/README.md)
- **5.4. Root Contexts** – [指南](./05-AdvancedTopics/mcp-root-contexts/README.md)
- **5.5. Routing** – [指南](./05-AdvancedTopics/mcp-routing/README.md)
- **5.6. Sampling** – [指南](./05-AdvancedTopics/mcp-sampling/README.md)
- **5.7. Scaling** – [指南](./05-AdvancedTopics/mcp-scaling/README.md)
- **5.8. Security** – [指南](./05-AdvancedTopics/mcp-security/README.md)
- **5.9. Web Search MCP** – [指南](./05-AdvancedTopics/web-search-mcp/README.md)
- **5.10. Realtime Streaming** – [指南](./05-AdvancedTopics/mcp-realtimestreaming/README.md)
- **5.11. Realtime Web Search** – [指南](./05-AdvancedTopics/mcp-realtimesearch/README.md)
</details>

<details>
  <summary><strong>06-10：社群、最佳實踐與實驗室</strong></summary>

- **06. 社群貢獻** – [指南](./06-CommunityContributions/README.md)
- **07. 早期採用的洞察** – [指南](./07-LessonsFromEarlyAdoption/README.md)
- **08. MCP 最佳實踐** – [指南](./08-BestPractices/README.md)
- **09. MCP 案例研究** – [指南](./09-CaseStudy/README.md)
- **10. 精簡 AI 工作流程：使用 AI Toolkit 建立 MCP 伺服器** – [實作實驗室](./10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/README.md)
</details>

## 範例專案

### 🧮 MCP 計算器範例專案：
<details>
  <summary><strong>依語言探索程式碼實作</strong></summary>

  - [C# MCP 伺服器範例](./03-GettingStarted/samples/csharp/README.md)
  - [Java MCP 計算器](./03-GettingStarted/samples/java/calculator/README.md)
  - [JavaScript MCP 示範](./03-GettingStarted/samples/javascript/README.md)
  - [Python MCP 伺服器](../../03-GettingStarted/samples/python/mcp_calculator_server.py)
  - [TypeScript MCP 範例](./03-GettingStarted/samples/typescript/README.md)

</details>

### 💡 MCP 進階計算器專案：
<details>
  <summary><strong>探索進階範例</strong></summary>

  - [進階 C# 範例](./04-PracticalImplementation/samples/csharp/README.md)
  - [Java 容器應用程式範例](./04-PracticalImplementation/samples/java/containerapp/README.md)
  - [JavaScript 進階範例](./04-PracticalImplementation/samples/javascript/README.md)
  - [Python 複雜實作](../../04-PracticalImplementation/samples/python/mcp_sample.py)
  - [TypeScript 容器範例](./04-PracticalImplementation/samples/typescript/README.md)

</details>


## 🎯 學習 MCP 的先決條件

為了充分利用這份課程內容，你應該具備：

- 基本的 C#、Java 或 Python 知識
- 了解客戶端-伺服器模型與 API
- （選擇性）熟悉機器學習相關概念

## 📚 學習指南

我們提供了一份完整的 [學習指南](./study_guide.md)，協助你有效瀏覽此資源庫。指南內容包括：

- 一張視覺化課程地圖，展示所有涵蓋主題
- 各資源庫區塊的詳細解析
- 如何使用範例專案的說明
- 針對不同技能層級的推薦學習路徑
- 補充學習資源，助你學習更完整

## 🛠️ 如何有效使用本課程

本指南中的每堂課都包含：

1. 清楚易懂的 MCP 概念說明  
2. 多種語言的即時程式碼範例  
3. 實作練習，打造真實的 MCP 應用程式  
4. 進階學習者的額外資源  

## 📜 授權資訊

本內容採用 **MIT 授權條款**。詳細條款請參閱 [LICENSE](../../LICENSE)。

## 🤝 貢獻指南

本專案歡迎貢獻與建議。大部分貢獻需同意一份貢獻者授權協議（CLA），聲明你有權利並確實授予我們使用你貢獻內容的權利。詳情請見 <https://cla.opensource.microsoft.com>。

當你提交 pull request 時，CLA 機器人會自動判斷是否需要你提供 CLA，並在 PR 上做出相應標記（例如狀態檢查、留言）。請依照機器人指示操作。你只需在所有使用我們 CLA 的資源庫中完成一次此流程。

本專案採用 [Microsoft 開放原始碼行為準則](https://opensource.microsoft.com/codeofconduct/)。更多資訊請參閱 [行為準則常見問題](https://opensource.microsoft.com/codeofconduct/faq/) 或透過電子郵件聯絡 [opencode@microsoft.com](mailto:opencode@microsoft.com) 以獲得進一步協助。

## 🎒 其他課程
我們團隊還有其他課程！歡迎參考：

- [AI Agents For Beginners](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)
- [Generative AI for Beginners using .NET](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
- [Generative AI for Beginners using JavaScript](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)
- [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
- [ML for Beginners](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
- [Data Science for Beginners](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
- [AI for Beginners](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
- [Cybersecurity for Beginners](https://github.com/microsoft/Security-101??WT.mc_id=academic-96948-sayoung)
- [Web Dev for Beginners](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
- [IoT for Beginners](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
- [XR Development for Beginners](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)
- [精通 GitHub Copilot 以進行 AI 配對程式設計](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
- [精通 GitHub Copilot 以協助 C#/.NET 開發者](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
- [選擇你自己的 Copilot 冒險之旅](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)


## ™️ 商標聲明

此專案可能包含專案、產品或服務的商標或標誌。對 Microsoft 商標或標誌的授權使用必須遵守並依據
[Microsoft 的商標與品牌指南](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general)。
在此專案的修改版本中使用 Microsoft 商標或標誌，不得引起混淆或暗示 Microsoft 的贊助。
任何第三方商標或標誌的使用均須遵守該第三方的相關政策。

**免責聲明**：  
本文件係使用 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。雖然我們力求準確，但請注意自動翻譯可能包含錯誤或不準確之處。原始文件的母語版本應視為權威來源。對於重要資訊，建議採用專業人工翻譯。對於因使用本翻譯而產生的任何誤解或誤譯，我們概不負責。