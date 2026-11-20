# 五個 AI skill

skill 就是寫給 AI 的 SOP。診所的消毒 SOP，不管誰做、哪天做，步驟都一樣。skill 也是這樣，寫一次以後，碰到同一種事，AI 會自己拿出來照著做。

這五個 skill 教的是做事的方法，不挑是什麼事，診所的行政、法規、採購都能用，連煮一道菜也行。每個 skill 都會先想這件事該找哪一種專家，再照那個行業的做法和標準去做。

## 五個 skill

| skill | 什麼時候用 | 開口這樣說 |
| --- | --- | --- |
| 需求訪談 | 要交代一件事之前。它會先問出你沒想到的地方，再幫你把指令寫好。 | 用「需求訪談」，我要＿＿＿＿。 |
| 深入執行 | 要它照那個行業最高的標準做、從原始資料查起的時候。 | 用「深入執行」，＿＿＿＿。 |
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

Claude 正在換新畫面：左邊選單的「自訂」改叫「外掛程式」，原本分開的 Skills 和「外掛程式」兩個分頁併成同一頁，而且不管哪一種方案都看得到「外掛程式」。下面的步驟是照舊畫面寫的，如果你左邊看到的已經是「外掛程式」，就直接點它，再點「新增」，後面的步驟都一樣。

外掛程式只有付費方案才有（Pro、Max、Ultra、Team、Enterprise），用免費版的人請看這一節最後的「Claude 免費版」。Windows 和 Mac 的步驟一樣。

1. 打開 Claude 桌面版，點左下角自己的名字 →「設定」→「功能」，把「程式碼執行與檔案建立」的開關打開。這個開關沒開，skill 不會動。
2. 點左邊選單的「自訂」，再點上面的「外掛程式」分頁。沒有「外掛程式」這個分頁，就是免費版，請改看下面的「Claude 免費版」。
3. 點右上角的「新增」。

接著選一種裝法：從市集裝，或用一個 ZIP 裝。兩種擇一就好，市集加不進來的時候，就用 ZIP。

### 裝法一：從市集裝

1. 選「新增市集」。
2. 在「網址」那一格打 `david-lai-jpg/etoil-ai-workshop-skills`，再按「同步」。
3. 同步好之後，找到 Etoil ai workshop skills，按它旁邊的「＋」。

### 裝法二：用一個 ZIP 裝

1. 下載 [`etoil-ai-workshop-skills.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/etoil-ai-workshop-skills.zip)，不要解壓縮。Mac 的 Safari 如果自動解開成資料夾，在資料夾上按右鍵，選「壓縮」。
2. 回到 Claude，在「新增」裡選「上傳外掛程式」，再選剛下載的 ZIP。畫面會出現「外掛程式已上傳。」

### 裝好以後

1. 點「自訂」裡的 Skills 分頁，清單裡有五個英文名字：ask-first、go-deep、second-opinion、make-a-skill、find-a-skill，就是裝好了。
2. 開一個新對話，照最上面表格「開口這樣說」那一欄打一句，例如「用『需求訪談』，我要＿＿＿＿。」

它不會馬上回答，會先照那個 skill 的做法來，像「需求訪談」會先問你問題。

如果叫了中文名字，它卻沒反應、直接回答，就開一個新對話，打「/」，從跳出來的清單裡選，或直接打英文名字，例如 /ask-first。

想找別人做好的 skill，到「自訂」→ Skills →「＋」→「瀏覽 Skills」找。裝之前一樣照「裝之前先看這三條」做。

只用講的，例如打「用『深入執行』」，AI 會看 skill 的說明，自己判斷要不要用，所以有時候不會用到。直接點名就一定會用到：在對話框打「/」或點「＋」，會列出外掛程式裡的 skill，選它的名字，後面再打要做的事。

例如打「/」選 go-deep，後面接著打「照這份做」。

### Claude 免費版

免費版沒有外掛程式，要一個一個裝，五個都要就做五次。五個檔案點檔名就能下載：

- 需求訪談：[`ask-first.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/ask-first.zip)
- 深入執行：[`go-deep.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/go-deep.zip)
- 對立審查：[`second-opinion.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/second-opinion.zip)
- 做一個 skill：[`make-a-skill.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/make-a-skill.zip)
- 找現成的 skill：[`find-a-skill.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/find-a-skill.zip)

1. 先照這一節最前面的第 1 步，把「程式碼執行與檔案建立」的開關打開。
2. 點要裝的檔名，下載 ZIP，不要解壓縮。Mac 的 Safari 如果自動解開成資料夾，在資料夾上按右鍵，選「壓縮」。
3. 在 Claude 點「自訂」→ Skills →「＋」→「建立 Skill」→「上傳 Skill」，選剛下載的 ZIP。
4. 清單上出現那個 skill 的英文名字後，把它的開關打開。

## 裝到 ChatGPT 桌面版

ChatGPT 的一般對話，只有公司方案（Business、Enterprise、Edu、Healthcare）才有 skill，其他方案的一般對話都沒有。想在 ChatGPT 用 skill，就在桌面版切到 Codex。切到 Codex 之後，每一種方案都能用 skill，免費版也可以。ChatGPT 桌面版在 Windows 和 Mac 上都有。

1. 打開 ChatGPT 桌面版（電腦上裝的 app，不是瀏覽器裡的網頁），在左邊的側邊欄點 Codex。
2. 在左邊點「外掛程式」。
3. 點右上角的「新增」。

接著選一種裝法：從市集裝，或用一個 ZIP 裝。兩種擇一就好，市集加不進來的時候，就用 ZIP。

### 裝法一：從市集裝

1. 選「新增市集」。
2. 在「來源」那一格打 `david-lai-jpg/etoil-ai-workshop-skills`，另外兩格留空白，再按「新增市集」。

### 裝法二：用一個 ZIP 裝

1. 下載 [`etoil-ai-workshop-skills.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/etoil-ai-workshop-skills.zip)，跟 Claude 用的是同一個檔案，不要解壓縮。Mac 的 Safari 如果自動解開成資料夾，在資料夾上按右鍵，選「壓縮」。
2. 回到 ChatGPT，在「新增」裡選「上傳外掛程式封存檔」，把 ZIP 拖進去，或點選上傳。

### 加進來以後

1. 在「外掛程式」這一頁找到「五個 AI skill」，也可以用上面的「搜尋外掛程式」找。
2. 點進「五個 AI skill」，按「安裝外掛程式」。
3. 在左邊點「技能」，會看到五個英文名字：ask-first、go-deep、second-opinion、make-a-skill、find-a-skill。
4. 回到 Codex，開一個新對話，照最上面表格「開口這樣說」那一欄打一句。

Codex 能開資料夾、改檔案、執行指令，所以它要你允許的時候，看懂了再按。

在 Codex 裡也一樣，只用講的有時候不會用到。要一定用到，就在對話框打「$」，選 skill 的名字。

### 沒有桌面版的時候

只用手機或網頁版、沒有桌面版的人，用不到 Codex 裡的 skill，可以改用「專案」當備案：

1. 一個 skill 開一個專案，專案名稱用 skill 的中文名，例如「需求訪談」。
2. 點專案名稱旁邊的「⋯」→「專案設定」，找到「指示」。
3. 打開 `ChatGPT` 資料夾裡同名的 .txt，全部複製後貼進去，再按儲存。
4. 要用的時候，到那個專案裡開新對話就好，不用叫名字。

同一個專案裡的每個對話都會照這份做法做，所以一個專案只放一個 skill。

走專案這條路的話，「做一個 skill」做出來的內容，請貼進另一個專案的「指示」。「找現成的 skill」找到的 skill，則要裝在 Claude 或 Codex 裡。
