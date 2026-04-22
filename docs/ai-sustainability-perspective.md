[[觀點日記]] [[有時效性]] [[AI應用]] [[風險或成本評估]]

# AI 這麼浪費算力，到底永不永續？

整理日期：2026-04-18  
用途：寫文章前的觀點整理與論證骨架，主軸是「AI 的耗能是否會被更大的系統性減浪費抵銷」。

---

## 先講結論

- `AI 耗電變高` 這件事是真的，不是假議題。
- 但判斷 AI 永不永續，不能只看「單次推論吃多少電」，而要看它有沒有減少更大的系統性浪費，例如研究時間、試錯成本、過量生產、食物浪費、交通與調度浪費。
- 所以最穩的說法不是「AI 一定永續」，也不是「AI 天生不永續」，而是：`AI 的永續性高度取決於應用場景與治理方式。`
- 如果 AI 被用在高浪費系統的優化，它可能帶來淨減排；如果只是把算力拿去放大低價值輸出，它也可能只是新增耗能。

---

## 一、可以確定的事：AI 真的會增加用電

### 1. 全球資料中心用電正在快速上升

- IEA 2025 指出，資料中心在 2024 年約用掉 `415 TWh` 電力，約占全球用電 `1.5%`。
- IEA 的 Base Case 預估，到 2030 年資料中心用電會成長到約 `945 TWh`，接近翻倍，約占全球用電 `3%`。
- IEA 也指出，這波成長主要由 AI 帶動的 accelerated servers 推升。

這條線可以支撐你文章裡的第一個誠實前提：  
`AI 不是零成本魔法，它背後確實有越來越大的電力與基礎設施需求。`

### 2. 美國的壓力更明顯

- Berkeley Lab 指出，美國資料中心在 2023 年用了約 `176 TWh` 電力。
- 到 2028 年，依情境不同，可能升到 `325-580 TWh`。
- 這代表資料中心用電占美國總用電比重，可能從 `4.4%` 升到 `6.7%-12%`。

這可以拿來補一句：  
`AI 耗能爭議之所以變大，不只是理論問題，而是很多地區的電網與資料中心建設真的已經感受到壓力。`

---

## 二、但不能只看資料中心：要看 AI 有沒有減掉更大的浪費

### 1. IEA 的關鍵判斷：AI 可能帶來比資料中心排放更大的減排

- IEA 在 `AI and climate change` 章節指出，資料中心目前約造成 `180 Mt` 的間接 CO2 排放，約占全球燃燒排放的 `0.5%`。
- 但 IEA 也估算，如果既有 AI 應用在終端用能部門廣泛採用，到 2035 年可能帶來約 `1,400 Mt CO2` 的減排。
- 這個數字約是資料中心 Lift-Off Case 排放的 `3 倍`，也是 Base Case 的 `4 倍`。

這是你整篇文章最重要的骨幹之一：  
`不能只看 AI 本身吃掉多少電，也要看它有沒有讓整個系統少浪費更多能源與資源。`

### 2. IEA 也給了幾個具體方向

- 既有輸電線若用 AI 優化，可能釋出最多 `175 GW` 額外傳輸容量。
- 輕工業若廣泛採用 AI 優化，到 2035 年可能有約 `8%` 節能空間。
- 建築管理系統若搭配 AI 最佳化 HVAC，約可省下 `10%` 左右能耗。
- 運輸調度與路徑優化則可能帶來 `5-10%` 效率改善。

也就是說，AI 的能源問題不能只停在「ChatGPT 問一句要多少電」，而是要往上看：  
`它有沒有減少整個電網、工廠、建築、運輸系統的更大浪費。`

---

## 三、你剛剛那句「人類研究十年，AI 半年」怎麼寫比較穩

### 先說判斷

我目前還沒找到一條足夠漂亮、又足夠硬的官方資料，可以直接支持「原本人類要研究十年，現在 AI 半年就完成」這種整句寫法。

比較穩的寫法應該是：

`傳統科學與藥物研發前段常是多年級距的試錯流程，而 AI 已在部分關鍵階段，把原本需要數月到數年的工作壓縮到秒級、或把原本數年的早期發現流程壓到 12-18 個月。`

### 1. AlphaFold 是一個很強的例子

- Google DeepMind 在 AlphaFold 的官方文章中引用 Eric Topol 的話：
  `蛋白質 3D 結構過去往往要花數月甚至數年才能確定，現在可以縮到秒級。`
- IEA 在 `AI for energy optimisation and innovation` 章節甚至直接寫到：  
  `AI led to a 45,000-fold acceleration in the scientific rate of discovery of the three-dimensional structures of proteins.`

這條線很適合拿來支撐你的大方向：  
`AI 在某些高知識密度領域，確實有可能把研究速度拉到傳統方法很難做到的等級。`

### 2. 藥物研發可以用「早期流程被大幅壓縮」來寫，不要直接寫成整條管線都變半年

- Insilico 的官方案例寫到：他們有專案把 `preclinical candidate` 的提名壓到 `18 個月內`。
- 同一案例把這個速度對比成業界平均約 `4.5 年`。

這裡的重點不是說「整個新藥上市流程都從十年變半年」，而是：  
`AI 已經在前段候選藥物發現與篩選，大幅減少試錯時間、合成測試量與前期探索成本。`

### 這段你文章可以怎麼寫

- 不要寫：`AI 把十年研究直接變半年。`
- 比較穩的寫法：`更精確地說，AI 已在蛋白質結構預測、候選藥物搜尋與前期篩選等環節，明顯壓縮原本需要數月、數年甚至更多試錯成本的流程。`

---

## 四、食物浪費這條線很值得寫

### 1. 食物浪費本身就是巨大的永續問題

- UNEP 2024 指出，全球在 2022 年浪費了約 `10.5 億噸`食物。
- 這相當於消費端可取得食物的 `五分之一`。
- 其經濟損失估計超過 `1 兆美元`。
- 家戶層級每天就浪費超過 `10 億餐`。
- UNEP 同時指出，食物損失與浪費約占全球溫室氣體排放的 `8-10%`，並浪費了全球 `28%` 農業土地與約 `1/4` 的農業淡水。

所以如果 AI 能有效減少食物浪費，它的永續意義不只是「省食物」，而是同時碰到：

- 碳排
- 甲烷
- 土地利用
- 水資源
- 供應鏈成本

### 2. 已經有 AI 減少食物浪費的實證案例

2025 年 `Waste Management` 的研究指出：

- 在 HORECA（飯店、餐飲、餐廳）場域中，
- 使用 AI waste-tracking device 後，
- 食物浪費下降了 `23%-51%`，
- 每餐浪費食物成本最多下降 `39%`。

研究也指出，這類系統的效益不只來自辨識廚餘本身，而是因為它提升了員工對過量生產、備料、剩食組成的可見度，進而改變決策。

### 3. Yale 的案例可以當較容易理解的敘事案例

- Yale Hospitality 在 2024 年導入 AI 系統分析 14 個宿舍餐廳廚房中的廚餘。
- 目的不是只把食物丟去堆肥，而是進一步找出 `備料浪費、腐敗、過量生產` 的來源。

這條很適合接到你的文章主張：

`如果 AI 能讓組織少煮、少丟、少買錯、少預估錯，那它雖然耗能，卻可能是在替更大的食物系統浪費止血。`

---

## 五、這篇文章最適合採用的主張

### 版本一：最穩

`AI 的永續性，不能只看它吃多少電，而要看它有沒有減少更大的系統性浪費。`

### 版本二：帶對比感

`如果 AI 只是多生成一堆沒人需要的內容，它可能不永續；但如果 AI 幫一個高浪費系統少走幾年冤枉路、少丟幾噸食物、少做幾輪錯誤試驗，它可能反而更永續。`

### 版本三：適合你會議脈絡

`AI 本身當然有耗能，但永續從來不是只看局部耗電，而是看整體資源效率。如果 AI 能把十次試錯縮成三次，把多年研究壓縮成可用的早期突破，把大量過量生產改成更準的調度，它未必比較浪費，反而可能更符合永續。`

---

## 六、反方提醒：這篇不能寫太滿的地方

### 1. 不要把 AI 寫成「天然永續」

更穩的說法是：

- `AI 有永續風險`
- `AI 也有減浪費潛力`
- `最後取決於場景、電力結構、硬體效率、治理方式與使用目的`

### 2. 不要把單一成功案例當成全產業已經證明

- AlphaFold、Insilico、食物浪費追蹤，都屬於「有力案例」，
- 但不代表所有 AI 專案都會有同等的淨效益。

### 3. 要提醒反彈效應

IEA 也提醒，AI 帶來的減排可能會被 rebound effects 抵銷。  
例如效率提升後，反而促進更多生產、更多移動、更多生成、更多消費。

所以真正關鍵不是只有 AI 強不強，而是：  
`AI 被拿去放大什麼行為。`

### 4. 不要把焦點只放在「每次問一句 AI 要多少電」

這種寫法很吸睛，但容易讓問題失焦。  
你真正想寫深的，應該是：

- 這個 AI 應用替代掉什麼舊浪費？
- 它縮短了哪些高成本流程？
- 它是否減少了材料、運輸、庫存、試錯、食物、人工重工？
- 它的治理與目標是否清楚？

---

## 七、我建議你文章的骨架

### 開場

先承認：AI 的算力成長、資料中心用電上升，這是真的。

### 第二段

提出問題：永續不能只看局部耗能，而要看總體資源效率。

### 第三段

舉 `研究加速` 的例子：

- AlphaFold
- 早期藥物發現

### 第四段

舉 `食物浪費` 的例子：

- UNEP 的大盤數據
- HORECA 研究
- Yale 案例

### 第五段

拉回結論：  
`AI 不會自動永續，也不會自動不永續。它到底是浪費算力，還是幫社會減少更大的浪費，要看它被用在哪裡。`

---

## 八、來源清單

### 官方與研究機構

1. IEA, `Energy demand from AI`  
   [https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai](https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai)

2. IEA, `AI and climate change`  
   [https://www.iea.org/reports/energy-and-ai/ai-and-climate-change](https://www.iea.org/reports/energy-and-ai/ai-and-climate-change)

3. IEA, `AI for energy optimisation and innovation`  
   [https://www.iea.org/reports/energy-and-ai/ai-for-energy-optimisation-and-innovation](https://www.iea.org/reports/energy-and-ai/ai-for-energy-optimisation-and-innovation)

4. Berkeley Lab, `Berkeley Lab Report Evaluates Increase in Electricity Demand from Data Centers`  
   [https://newscenter.lbl.gov/2025/01/15/berkeley-lab-report-evaluates-increase-in-electricity-demand-from-data-centers/](https://newscenter.lbl.gov/2025/01/15/berkeley-lab-report-evaluates-increase-in-electricity-demand-from-data-centers/)

5. UNEP, `Towards Zero-Waste and Circular Cities: Key Findings of the Food Waste Index Report 2024`  
   [https://www.unep.org/events/unep-event/towards-zero-waste-and-circular-cities-key-findings-food-waste-index-report-2024](https://www.unep.org/events/unep-event/towards-zero-waste-and-circular-cities-key-findings-food-waste-index-report-2024)

### 學術與案例

6. Waste Management (2025), `Reducing food waste in the HORECA sector using AI-based waste-tracking devices`  
   [https://www.sciencedirect.com/science/article/pii/S0956053X25001072](https://www.sciencedirect.com/science/article/pii/S0956053X25001072)

7. Yale News, `Waste watchers: Using AI to minimize food waste in dining halls`  
   [https://news.yale.edu/2024/08/05/waste-watchers-using-ai-minimize-food-waste-yales-dining-halls](https://news.yale.edu/2024/08/05/waste-watchers-using-ai-minimize-food-waste-yales-dining-halls)

8. Google DeepMind, `AlphaFold reveals the structure of the protein universe`  
   [https://deepmind.google/blog/alphafold-reveals-the-structure-of-the-protein-universe/](https://deepmind.google/blog/alphafold-reveals-the-structure-of-the-protein-universe/)

9. Insilico Medicine, `Case Study: Insilico's Transformation`  
   [https://insilico.com/casestudy](https://insilico.com/casestudy)

---

## 九、後續可再補的方向

- 如果你要把這篇寫成更硬的長文，可以再補：
  - `晶片製造與水資源` 這一段
  - `模型訓練 vs 推論` 的差異
  - `哪些 AI 應用其實只是高耗能的低價值內容工廠`
  - `哪些 AI 應用是在替高浪費系統止血`

- 如果你要寫成比較有立場的文章，我建議主軸不要是「AI 到底好還是壞」，而是：  
  `什麼樣的 AI 使用方式，才算真的符合永續。`
