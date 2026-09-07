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
