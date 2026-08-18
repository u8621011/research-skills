公開的 research skills，供學習 & 參考使用。

請自行確認執行結果。

## 安裝方式

`npx skills@latest add u8621011/research-skills`

## skills 說明

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