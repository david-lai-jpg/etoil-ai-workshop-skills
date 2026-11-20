# 五個 AI skill

skill 就是寫給 AI 的 SOP。診所的消毒 SOP，不管誰做、哪天做，步驟都一樣。skill 也是這樣，寫一次以後，碰到同一種事，AI 會自己拿出來照著做。

這五個 skill 教的是做事的方法，不挑是什麼事，診所的行政、法規、採購都能用，連煮一道菜也行。每個 skill 都會先想這件事該找哪一種專家，再照那一行的做法和標準去做。

## 五個 skill

| skill | 什麼時候用 | 開口這樣說 |
| --- | --- | --- |
| 需求訪談 | 要交代一件事之前。它會先問出你沒想到的地方，再幫你把指令寫好。 | 用「需求訪談」，我要＿＿＿＿。 |
| 深入執行 | 要它照那一行最高的標準做、從原始資料查起的時候。 | 用「深入執行」，＿＿＿＿。 |
| 對立審查 | 檢查另一個 AI 做好的回答、文件、計畫或決定。 | 先開一個新對話，再說：用「對立審查」檢查這份（貼上）。它是＿＿＿＿，要給＿＿＿＿用。 |
| 做一個 skill | 想把常做的事教給 AI。 | 用「做一個 skill」，我想教你＿＿＿＿。 |
| 找現成的 skill | 想找別人做好的 skill。 | 用「找現成的 skill」，有沒有人做過＿＿＿＿？ |

前三個可以串起來用：

1. 用「需求訪談」說出你要做的事。它會一輪一輪問，你回答，最後它把指令寫好。
2. 接著說「用『深入執行』照這份做」。
3. 另開一個新對話，用「對立審查」檢查它做出來的東西。貼的時候只貼它做出來的東西，前面的對話不要一起貼過去。

這五個 skill 只有在你叫它的名字，或明確要它這樣做的時候才會出來，例如「先問我」「做深一點」「幫我挑毛病」。平常問問題時，它們不會跑出來。

skill 的名字只能用英文，所以在 Claude 的清單上看到的是英文名字（例如 ask-first）。每個 skill 的中文名寫在「什麼時候用」那句話的開頭，所以講中文名一樣叫得到。

## 裝之前先看這三條

1. 只裝你信得過的人給的。
2. 裝之前先打開看一遍，看不懂就不要裝。
3. 病人資料和密碼都不要放進去。

五個 skill 的內容都在這個網頁的 `skills` 資料夾，每個資料夾裡只有一個 SKILL.md，裝之前可以先點開來看。

## 裝到 Claude 桌面版

Plugins（外掛）只有付費方案才有（Pro、Max、Ultra、Team、Enterprise），用免費版的人請看這一節最後的「Claude 免費版」。Windows 和 Mac 的步驟一樣。Claude 的畫面沒有中文，選單都是英文，照英文字找。

1. 打開 Claude 桌面版，點左下角自己的名字，再點 Settings（設定）→ Capabilities（功能），打開 Code execution and file creation（建立檔案）的開關。有的版本這個開關叫 Create and edit files（編輯檔案）。這個開關沒開，skill 不會動。
2. 點左邊選單的 Customize（自訂），再點上面的 Plugins 分頁。沒有 Plugins 這個分頁，就是免費版，請改看下面的「Claude 免費版」。
3. 點右上角的 Add（新增），再點 Add marketplace（新增市集）。
4. 在 URL（網址）那一格打 `david-lai-jpg/etoil-ai-workshop-skills`，再按 Sync（同步）。
5. 點 Discover（探索），找到 Etoil ai workshop skills，按 Add。
6. 點 Skills（技能）分頁，清單裡會有五個英文名字：ask-first、go-deep、second-opinion、make-a-skill、find-a-skill。
7. 開一個新對話，照最上面表格「開口這樣說」那一欄打一句，例如「用『需求訪談』，我要＿＿＿＿。」它不會馬上回答，會先照那個 skill 的做法來，像「需求訪談」會先問你問題。

如果叫了中文名字，它卻沒反應、直接回答，就開一個新對話，打「/」，從跳出來的清單裡選，或直接打英文名字，例如 /ask-first。

想找別人做好的 skill，到 Customize → Skills → ＋ → Browse skills（瀏覽技能）找。裝之前一樣照「裝之前先看這三條」做。

### Claude 免費版

免費版沒有 Plugins，要一個一個裝，五個都要就做五次。五個檔案點檔名就能下載：

- 需求訪談：[`ask-first.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/ask-first.zip)
- 深入執行：[`go-deep.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/go-deep.zip)
- 對立審查：[`second-opinion.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/second-opinion.zip)
- 做一個 skill：[`make-a-skill.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/make-a-skill.zip)
- 找現成的 skill：[`find-a-skill.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/find-a-skill.zip)

1. 先做上面的第 1 步，把開關打開。
2. 點要裝的檔名，下載 ZIP，不要解壓縮。Mac 的 Safari 如果自動解開成資料夾，在資料夾上按右鍵，選「壓縮」。
3. 在 Claude 點 Customize → Skills → ＋ → Create skill（建立技能）→ Upload a skill（上傳技能），選剛下載的 ZIP。
4. 清單上出現英文名字後，確認旁邊的開關是打開的。

## 裝到 ChatGPT 桌面版

ChatGPT 的一般對話，只有公司方案（Business、Enterprise、Edu、Healthcare）才有 skill，其他方案的一般對話都沒有。想在 ChatGPT 用 skill，就在桌面版切到 Codex。切到 Codex 之後，每一種方案都能用 skill，免費版也可以。ChatGPT 桌面版在 Windows 和 Mac 上都有。

下面的選單名稱照 ChatGPT 繁體中文介面上的字寫，介面是英文的人，括號裡的英文就是你畫面上的字。

1. 打開 ChatGPT 桌面版（電腦上裝的 app，不是瀏覽器裡的網頁），在左邊的側邊欄點 Codex。
2. 點左下角自己的名字或頭像，點「設定」（Settings），再點左邊那一排「整合」底下的「外掛程式」（Plugins）。
3. 點右上角的「新增」（Add），再點「新增市集」（Add a marketplace）。
4. 在「來源」（Source）那一格打 `david-lai-jpg/etoil-ai-workshop-skills`，另外兩格留空白，再按「新增市集」。
5. 點「市集」（Marketplace）分頁，點 etoil-ai-workshop-skills，再點「五個 AI skill」，按「安裝外掛程式」。
6. 點「技能」（Skills）分頁，會看到五個英文名字：ask-first、go-deep、second-opinion、make-a-skill、find-a-skill。
7. 回到左邊側邊欄的 Codex，開一個新對話，照最上面表格「開口這樣說」那一欄打一句。

Codex 能開資料夾、改檔案、執行指令，所以它要你允許的時候，看懂了再按。

### 沒有桌面版的時候

只用手機或網頁版、沒有桌面版的人，用不到 Codex 裡的 skill，可以改用「專案」（Projects）當備案：

1. 一個 skill 開一個專案，專案名稱用 skill 的中文名，例如「需求訪談」。
2. 點專案名稱旁邊的「⋯」→「專案設定」（Project settings），找到「指示」（Instructions）。
3. 打開 `ChatGPT` 資料夾裡同名的 .txt，全部複製後貼進去，再按儲存。
4. 要用的時候，到那個專案裡開新對話就好，不用叫名字。

同一個專案裡的每個對話都會照這份做法做，所以一個專案只放一個 skill。

走專案這條路的話，「做一個 skill」做出來的內容，請貼進另一個專案的「指示」。「找現成的 skill」找到的 skill，則要裝在 Claude 或 Codex 裡。
