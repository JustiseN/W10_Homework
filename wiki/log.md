# 變更紀錄

> 只在末端新增，不修改舊紀錄。

## 2026-11-22 — 初始化
- 建立三層結構：`CLAUDE.md`、`raw/`（含 `assets/`）、`wiki/`
- 新增：`index.md`、`log.md`
- 備註：範圍限定為平底鍋煎牛排，讀者為新手；其他烹煮手法一律不收

## 2026-11-22 — 規則修改
- 修改：`CLAUDE.md`
  - 範圍：只收平底鍋煎；明確排除先煎後烤、逆向煎、醬汁、配菜、酒類
  - 寫作：「為什麼」必寫，2–4 句簡要說明
  - 新增來源可信度分級 A/B/C；來源以二手資訊為主，移除實驗紀錄
  - 語言：繁體中文（台灣用語），專有名詞第一次出現附英文
  - 新增食品安全章節；以人類提供的參考資料為基準
  - Ingest 改為比對 index.md「已匯入來源」，批次匯入所有新來源
  - 新增第 0 節：規則檔修改須經人類同意，同意以一次為限
- 修改：`index.md`（新增「食品安全」類別與「已匯入來源」清單）
- 備註：人類於本次對話同意上述 7 點修改

## 2026-11-22 — ingest
- 來源：raw/7-Myths-About-Cooking-Steak-That.md（提議 A）
- 新增：[[tempering-before-cooking]]、[[flipping]]、[[doneness-check]]、[[bone-in-vs-boneless]]
- 修改：[[dry-brining]]、[[maillard-reaction]]（補充迷思與實驗）
- 備註：原文以烤架示範，作者表示原則適用於平底鍋；略過範圍外內容：迷思 #2 的烤架兩段式火候、冷水舒肥、鋁鍋解凍小技巧、延伸閱讀中的烤架／舒肥／火炙食譜

## 2026-11-22 — ingest
- 來源：raw/An-Introduction-to-the-Maillard.md（提議 B）
- 新增：[[maillard-reaction]]
- 備註：略過範圍外內容：馬鈴薯、餅乾、啤酒、雞肉鬆餅等非牛排例子（僅保留與牛排對比的原理）、pH 調整（小蘇打／酸）未收錄，因來源未說明是否適用於牛排

## 2026-11-22 — ingest
- 來源：raw/Dry-Brine-Is-the-Best-Way-to-Brine.md（提議 B）
- 新增：[[dry-brining]]
- 備註：與 7 Myths、Maillard 兩篇在「最長鹽漬時間」上分歧（24 小時 vs 數天），已在頁面列出；略過範圍外內容：濕式鹽水、禽類、大塊烤肉、魚、蔬菜、泡打粉脆皮、漢堡肉

## 2026-11-22 — ingest
- 來源：raw/From-the-Archive-The-Food-Lab-on.md（提議 B）
- 新增：[[resting]]
- 修改：[[doneness-check]]（三分熟 51.7°C，與 7 Myths 的 54°C 分歧）
- 備註：文章為 2009 年，2025 年編者註記結論已修訂，頁面已加時效提醒；略過範圍外內容：大塊烤肉的靜置時間

## 2026-11-22 — ingest
- 來源：raw/Meat-and-Poultry-Roasting-Charts.md（提議 A）
- 新增：[[food-safety]]、[[quick-start]]
- 修改：[[doneness-check]]、[[resting]]（加入官方 63°C、靜置 3 分鐘）
- 備註：是否為食品安全基準資料待人類確認；與 Serious Eats 三分熟溫度衝突，依規則以官方為準；略過範圍外內容：烤箱溫度與時間表、羊、豬、小牛、火腿、禽肉、火雞解凍

## 2026-11-22 — 其他（來源確認與檔名更新）
- 人類確認：`FoodSafety-Meat-and-Poultry-Roasting-Charts.md` 為食品安全基準資料
- 修改：[[food-safety]]（移除「待基準資料確認」標註，改為基準來源說明；「為什麼」段落無來源，改標「未查證」）、`index.md`
- 人類自行將 raw 檔改名，wiki 內所有引用已同步更新（本紀錄以上的舊紀錄保留原檔名）：
  - 7-Myths-About-Cooking-Steak-That.md → seriouseats-7-Myths-About-Cooking-Steak-That.md
  - An-Introduction-to-the-Maillard.md → seriouseats-An-Introduction-to-the-Maillard.md
  - Dry-Brine-Is-the-Best-Way-to-Brine.md → seriouseats-Dry-Brine-Is-the-Best-Way-to-Brine.md
  - From-the-Archive-The-Food-Lab-on.md → seriouseats-From-the-Archive-The-Food-Lab-on.md
  - Meat-and-Poultry-Roasting-Charts.md → FoodSafety-Meat-and-Poultry-Roasting-Charts.md
- 備註：人類同意矛盾處理方式（三分熟 52–54°C 並列、食品安全以基準為準、鹽漬新手建議 45 分鐘～24 小時）

## 2026-11-22 — ingest
- 來源：raw/FoodSafety-Safe-Minimum-Internal-Temperature.md（提議 A）
- 修改：[[food-safety]]（新增清潔／分開／煮熟／冷藏四原則、「離火前達到最低溫度」、起鍋時機分歧）
- 備註：存檔內容只有前言，**溫度表未被擷取**；檔名前綴為 FoodSafety，但實際來源為 fsis.usda.gov

## 2026-11-22 — ingest
- 來源：raw/seriouseats-Perfect-Pan.md（提議 A）
- 新增：[[pan-searing-method]]、[[oil-and-butter]]
- 修改：[[dry-brining]]（撒鹽時間軸實驗、3–40 分鐘最糟、過夜最佳；最短時間 40 vs 45 分鐘分歧）、[[flipping]]（每 15–30 秒、叉子重量實驗）、[[doneness-check]]（切開看會誤判較生）、[[tempering-before-cooking]]（前言建議回溫，與 7 Myths 分歧，採 7 Myths）、[[maillard-reaction]]、[[quick-start]]
- 備註：略過範圍外內容：逆向煎肋排、舒肥、冷水舒肥、漢堡翻面、香腸；「逆紋切」僅為連結提及，未收錄具體內容

## 2026-11-22 — ingest
- 來源：raw/seriouseats-This-Major-Rule-About-Cooking-Meat.md（提議 A）
- 修改：[[resting]]（全面改寫：靜置是溫度控制、不是保住肉汁；採用 2025 版本，取代 2009 年舊結論）、[[doneness-check]]、[[pan-searing-method]]、[[flipping]]、[[food-safety]]
- 備註：實驗對象為豬排，非牛排，頁面已註明；略過範圍外內容：大型烤肉的靜置建議、烤箱

## 2026-11-22 — ingest
- 來源：raw/fsis.usda-Safe-Minimum-Internal-Temperature.md（提議 A）
- 修改：[[food-safety]]（新增原塊肉 62.8°C＋3 分鐘與基準一致、絞肉 71.1°C、剩菜重新加熱 73.9°C、最低標準可依偏好提高；移除「溫度表未擷取」待補項）
- 備註：人類重新存檔，取代先前只有前言的 FoodSafety-Safe-Minimum-Internal-Temperature.md（已刪除）；wiki 內引用與 index.md 已改為新檔名；略過範圍外內容：禽肉、蛋、魚貝、火腿、砂鍋菜

## 2026-11-22 — 其他（可信度等級確認）
- 人類確認全部 8 份來源採用 LLM 提議的等級：
  - A：seriouseats-7-Myths-About-Cooking-Steak-That.md、seriouseats-Perfect-Pan.md、seriouseats-This-Major-Rule-About-Cooking-Meat.md、FoodSafety-Meat-and-Poultry-Roasting-Charts.md、fsis.usda-Safe-Minimum-Internal-Temperature.md
  - B：seriouseats-An-Introduction-to-the-Maillard.md、seriouseats-Dry-Brine-Is-the-Best-Way-to-Brine.md、seriouseats-From-the-Archive-The-Food-Lab-on.md
- 修改：`index.md`（移除「待確認」）
- 備註：wiki 頁面內的來源等級標示原本即為提議等級，無需修改

## 2026-11-22 — lint
- 修改：[[dry-brining]]（「40–45 分鐘」統一為「45 分鐘」；加註「室溫放置的安全上限待補，見 food-safety」）
- 修改：[[food-safety]]（加註「63°C 是 62.8°C 四捨五入，本 wiki 統一寫 63°C」）
- 修改：[[doneness-check]]（「餘溫加熱」補上英文 carryover cooking）
- 修改：[[bone-in-vs-boneless]]（刪除未查證的「避開骨頭量溫」推論）
- 備註：人類逐項同意以上修正

## 2026-11-22 — 規則修改
- 修改：`CLAUDE.md` 第 2 節 raw/ 規則，新增「允許欄位記在 index.md」：raw 檔至少要有 source，其餘欄位缺漏時記入 index.md 來源表，不修改 raw，不視為嚴重缺漏；兩者不一致時以 index.md 為準
- 備註：人類於本次對話同意此修改（lint 第 2 項）；此次同意已使用，下次修改規則檔須重新取得同意
