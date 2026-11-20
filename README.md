research skills，供學習 & 參考使用。

請自行確認執行結果。

## 安裝方式

有兩種安裝方式：

- 以 public github repo 安裝，步驟：
	- 先在命令列切換到你的工作目錄（也就是要安裝 agent skill 的 專案目錄）
	- 執行指令：
	  `npx skills add u8621011/research-skills`
- 下載 research skills 壓縮檔後，在本地解壓縮後再安裝，步驟：
	- 將壓縮檔解壓縮到某個目錄內。例如： research_skills_folder
	- 切換到你的工作目錄（也就是要安裝 agent skill 的 專案目錄）
	- 執行指令：
		- npx skills add {research_skills_unzipped_folder 的完整路徑}

## skills 說明

### 免費公開

- general-reader-simulator： 一般讀者模擬
	- 用途：
		- 模擬無特殊知識背景的讀者來閱讀指定的文章，並且可進一步要求產生【作者意圖-讀者理解對齊報告】
	- skill 設計背景：
	  [研究者的知識詛咒：Agent 能不能幫我們看見自己看不見的論文問題？ | Ted 的 AI 學術顧問所](https://www.research-ai.cc/blog/curse-of-knowledge-research-agent)
	- 用法範例：
		- 方法一：
			- prompt1：
				- /general-reader-simulator 幫我分析我這篇文章： {文章檔名}
			- prompt2：
				- 讀者與我的意圖對齊狀況如何？
		- 方法二：
			- prompt1：/general-reader-simulator 幫我分析我這篇文章： {文章檔名}。我文章撰寫的目標為：{文章意圖說明文件檔名}
	- 備註
		- 文章意圖說明文件，可參考 skill 內： author-intent-card.md
- thesis-topic-navigator： 論文選題輔導
	- 用途：
		- 論文選題輔導（Thesis Topic Navigator）——協助碩博士生從興趣、工作或生活痛點出發，逐步收斂出一句清晰、可檢證、範圍合理的研究題目，並完成初步可行性評估。用於「還沒有題目」「只有模糊方向」「題目可不可行」「範圍會不會太大」這類選題階段的請求。
	- 用法範例：
		- 你可以這麽使用，假設你有一個存放研究題目、草稿的目錄： {thesis_draft_folder}
		- 一個最簡單的起始句例如：
		  `/thesis-topic-navigator @{thesis_draft_folder/論文參考_indexfile} 是我目前想做研究的 entry ，不知道你有什麼想法？`
- clarifying-research-needs： 研究需求釐清訪談
	- 用途：
		- 以半結構化訪談協助研究者釐清模糊、矛盾或發散的研究想法：釘清關鍵定義、把敘述改寫成可檢驗的研究問題與主張、用引導反問處理前後矛盾、收斂到期限內做得完的範圍；結束時先做小總結對帳，使用者確認後產出可交給指導教授或共同研究者的正式會議記錄。當使用者說研究方向很亂、題目太大、說法前後矛盾、想在見指導教授或寫計畫書前把研究想法理清，或要求「研究需求釐清訪談」「幫我釐清研究問題」「訪談我一下」，或貼出研究構想草稿、討論逐字稿想整理成研究共識與會議記錄時，都應使用此 skill，即使沒有明說「訪談」。不用於完全沒有方向的從零選題、代寫論文段落、系統性文獻缺口分析或問卷題項設計。
	- 用法範例
		- /clarifying-research-needs {研究草稿/計劃書 內容 or 檔名}