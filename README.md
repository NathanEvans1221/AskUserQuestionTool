# AskUserQuestionTool
AskUserQuestionTool 是 Claude Code（Anthropic 推出的命令列 AI 開發工具）中的一個互動工具。  

簡單來說，它是 Claude 的**「發問麥克風」**。  

- 核心功能
當 Claude 在執行任務（例如寫代碼、重構或除錯）遇到不確定的情況時，它會調用這個工具來暫停自動化流程，並直接向你提問。  

---

這個專案就是利用 AskUserQuestionTool 的機制，讓 AI 訪談我，在 AI 提問與我的回答過程中，建立規格說明(spec)。  

---

## PROMPT
```bash
請使用 AskUserQuestionTool 對我進行詳盡的訪談，訪談內容可以透過任何方式: 技術實現、UI與UX、潛在疑慮、權衡取捨等,但請確保提出的問題具有深度，而非淺顯易見。

請保持深度並持續提問，直到訪談完全結束，最後完善的規格說明(spec)寫入項目目錄中。
```
