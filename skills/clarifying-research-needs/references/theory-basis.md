# 方法論依據

只在使用者問「為什麼這樣問」「這個流程的依據是什麼」，或要把訪談方法寫進研究方法章節時讀。訪談進行中不需要讀。

下表的「對應程度」是設計者的詮釋：強＝概念與做法直接相符；中＝做法相近但領域不同；類比＝只借用思路。

## 目錄

1. 對應總表
2. 各模組說明
3. 使用限制
4. 參考文獻

## 1. 對應總表

| 流程元件 | 對應的既有框架 | 對應程度 |
|---|---|---|
| 整體訪談骨架 | 半結構化訪談指南（Kallio et al., 2016）；需求工程的需求引出訪談（Ferrari & Gnesi, 2016, 2018）；任務導向對話的框架與欄位、對話狀態追蹤（Jurafsky & Martin；Jacqmin et al., 2022） | 中 |
| 背景蒐集 | 欄位填充；Heilmeier 問題集；Booth 等人的三段式 | 中 |
| M1 定義釐清 | 概念化與操作化（SAGE encyclopedia）；需求品質屬性「無歧義、可驗證」（ISO/IEC/IEEE 29148） | 強 |
| M2 邏輯澄清 | PICO、PCC（JBI）、FINER（Hulley et al.）；Toulmin 論證模型；中介與調節的區分（Baron & Kenny, 1986） | 強 |
| M3 矛盾處理 | 蘇格拉底式提問（Paul & Elder, 2006）與反詰法 elenchus；目標導向需求工程的衝突分析（van Lamsweerde et al., 1998；Carvalho et al., 2023） | 強 |
| M4 收斂聚焦 | MoSCoW 的「這次不做」；FINER 的可行性；Swales 的 CARS 研究空間模型 | 強＋中；「最小可行研究問題」無既有命名框架，屬本流程自創 |
| 鏡像重述與小總結 | 動機式晤談 OARS 中的反映式傾聽與摘要；Clark & Brennan（1991）的共同基礎（grounding） | 中（領域不同） |
| 引導而非代答 | 動機式晤談精神（合作、喚起）；AI Socratic Tutor 研究方案（2025） | 中 |
| 訪談筆記外部化 | 對話狀態追蹤；context engineering 的結構化筆記策略（Anthropic） | 強 |
| 會議記錄 | 會議記錄實務：聚焦決策與有負責人、期限的行動項目 | 強＋為研究情境擴充 |

## 2. 各模組說明

**整體骨架。** 半結構化訪談有預先擬定的指南，但允許依回答追問。本流程就是一份寫好的訪談指南。需求工程研究指出，訪談是最常用的需求引出方式；訪談中的歧義除了是溝通障礙，也能揭露隱性知識，可作為追問的觸發點。任務導向對話系統用「框架」規定要取得哪些欄位，並每一輪更新對使用者需求的表徵；背景蒐集的五項就是必填欄位，訪談筆記就是對話狀態。

**M1。** 概念要先賦予理論意義（概念化），再推到經驗層的變項與指標（操作化）。工作定義句型「指的是＿＿（可觀察指標：＿＿），不包含＿＿」同時涵蓋定義、指標、邊界。需求工程研究也發現，歧義與不可驗證是需求文件中最嚴重的問題類型。

**M2。** 不同問題類型適用不同框架：PICO 適合介入成效類問題；PCC 由 JBI 建議用於範圍型回顧與較寬的探索性問題；FINER 用於檢查已成形的問題是否可行、有趣、新穎、合乎倫理、相關。Toulmin 把論證拆成主張、依據、保證、限定、反駁、支持，「推論跳躍」多半是保證缺失。Baron 與 Kenny 強調不可混用中介與調節。

**M3。** 蘇格拉底式提問重視精神勝於形式，分為澄清、探究假設、探究理由與證據、觀點、含意與後果、關於問題的問題等類。反詰法只能顯示信念之間不一致，無法證明哪一個為假，因此修正方向必須由當事人決定。目標導向需求工程把衝突分析分為識別、評估、解決三階段，識別時以「邊界條件」刻畫衝突；本流程的「指出衝突條件」與此相近，「第 0 步分流」對應評估階段。與古典反詰法不同，本流程刻意避免令對方難堪，立場更接近動機式晤談的合作取向。

**M4。** MoSCoW 的「Won't have this time」是對本期明確約定不做，而非永久否決，對應「排除（暫不做）」。FINER 的可行性涵蓋樣本、技術、時間、金錢與範圍可管理性。CARS 模型把研究引言分為建立領域、建立缺口、佔據缺口，貢獻句閘門即在問「佔哪個缺口」。

**鏡像與小總結。** 動機式晤談的反映式傾聽是用自己的話重述對方所說，讓對方有機會澄清；摘要則串起資訊，並讓對方聽見自己的矛盾。共同基礎理論指出溝通雙方必須透過 grounding 確立「已被理解」；小總結的 ✅／❓標記就是一本共同基礎的帳本。

**先問再答。** 研究指出，先進的 LLM 面對含糊請求時，傾向直接假設意圖作答而不提問。每輪限題、先改寫再確認等規則，是為了抵銷這個傾向。

## 3. 使用限制

- 動機式晤談、PICO、FINER 源自臨床與醫學領域；用於一般研究需求釐清時，借用的是微技巧與思維，不是整套方法。
- 蘇格拉底式提問分類屬教育實務框架，實證檢驗有限；AI Socratic Tutor 是尚無成效資料的研究方案，只能當設計先例。
- 多項來源（Toulmin、MoSCoW、Booth、Heilmeier、CARS、ISO 29148）為二手教材轉述。

## 4. 參考文獻

- Baron, R. M., & Kenny, D. A. (1986). The moderator-mediator variable distinction in social psychological research. *Journal of Personality and Social Psychology, 51*(6), 1173–1182.
- Booth, W. C., Colomb, G. G., Williams, J. M., Bizup, J., & FitzGerald, W. T. *The craft of research*. University of Chicago Press.
- Carvalho, L., et al. (2023). ACoRe: Automated goal-conflict resolution. arXiv:2303.05213.
- Clark, H. H., & Brennan, S. E. (1991). Grounding in communication. In *Perspectives on socially shared cognition*. APA.
- Ferrari, A., & Gnesi, S. (2016). Ambiguity and tacit knowledge in requirements elicitation interviews.
- Ferrari, A., & Gnesi, S. (2018). Interview review: An empirical study on detecting ambiguities in requirements elicitation interviews.
- Hulley, S. B., et al. (2007). *Designing clinical research* (3rd ed.). Lippincott Williams & Wilkins.（FINER）
- Jacqmin, L., Rojas-Barahona, L. M., & Favre, B. (2022). "Do you follow me?": A survey of recent approaches in dialogue state tracking. arXiv:2207.14627.
- Jurafsky, D., & Martin, J. H. *Speech and language processing* (3rd ed. draft), Appendix K: Frame-based dialogue systems.
- Kallio, H., Pietilä, A.-M., Johnson, M., & Kangasniemi, M. (2016). Systematic methodological review: Developing a framework for a qualitative semi-structured interview guide. *Journal of Advanced Nursing, 72*(12), 2954–2965.
- Paul, R., & Elder, L. (2006). *The thinker's guide to the art of Socratic questioning*. Foundation for Critical Thinking.
- Swales, J. M. (1990). *Genre analysis*. Cambridge University Press.（CARS）
- van Lamsweerde, A., Darimont, R., & Letier, E. (1998). Managing conflicts in goal-driven requirements engineering. *IEEE Transactions on Software Engineering, 24*(11), 908–926.
- Zhang, M. J. Q., et al. (2024). Modeling future conversation turns to teach LLMs to ask clarifying questions. arXiv:2410.13788.

完整調查與網址見知識庫報告 `00006_research-needs-interview-skill-migration.md`。
