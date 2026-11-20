# 五個 AI skill

這份是 2026-11-20 的版本。標了（我們還沒試過）的步驟，都還沒有實際跑過。

skill 就是寫給 AI 的 SOP。診所的消毒 SOP，不管誰做、哪天做，步驟都一樣。skill 也是這樣，寫一次以後，碰到同一種事，AI 會自己拿出來照著做。

這五個 skill 教的是做事的方法，不挑是什麼事，診所的行政、法規、採購都能用，連煮一道菜也行。每個 skill 都會先想這件事該找哪一種專家，再照那一行的做法和標準去做。

## 五個 skill

| skill | 什麼時候用 | 開口這樣說 | Claude 要裝的檔案 |
| --- | --- | --- | --- |
| 需求訪談 | 要交代一件事之前。它會先問出你沒想到的地方，再幫你把指令寫好。 | 用「需求訪談」，我要＿＿＿＿。 | [`ask-first.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/ask-first.zip) |
| 深入執行 | 要它照那一行最高的標準做、從原始資料查起的時候。 | 用「深入執行」，＿＿＿＿。 | [`go-deep.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/go-deep.zip) |
| 對立審查 | 檢查另一個 AI 做好的回答、文件、計畫或決定。 | 先開一個新對話，再說：用「對立審查」檢查這份（貼上）。它是＿＿＿＿，要給＿＿＿＿用。 | [`second-opinion.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/second-opinion.zip) |
| 做一個 skill | 想把常做的事教給 AI。 | 用「做一個 skill」，我想教你＿＿＿＿。 | [`make-a-skill.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/make-a-skill.zip) |
| 找現成的 skill | 想找別人做好的 skill。 | 用「找現成的 skill」，有沒有人做過＿＿＿＿？ | [`find-a-skill.zip`](https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/find-a-skill.zip) |

前三個可以串起來用：

1. 用「需求訪談」說出你要做的事。它會一輪一輪問，你回答，最後它把指令寫好。
2. 接著說「用『深入執行』照這份做」。
3. 另開一個新對話，用「對立審查」檢查它做出來的東西。貼的時候只貼它做出來的東西，前面的對話不要一起貼過去。

這五個 skill 只有在你叫它的名字，或明確要它這樣做的時候才會出來，例如「先問我」「做深一點」「幫我挑毛病」。平常問問題時，它們不會跑出來。

skill 的名字只能用英文，所以在 Claude 的清單上看到的是英文名字（例如 ask-first）。每個 skill 的中文名寫在「什麼時候用」那句話的開頭，所以講中文名一樣叫得到。

## 到哪裡下載

要下載的東西都在這個網頁上：https://github.com/david-lai-jpg/etoil-ai-workshop-skills

- 要一次裝五個，用的是 `etoil-ai-workshop-skills.zip`，從這個網址下載：

  https://github.com/david-lai-jpg/etoil-ai-workshop-skills/releases/latest/download/etoil-ai-workshop-skills.zip

- 要一次裝一個，用的是上面表格裡的五個 ZIP，點檔名就能下載。
- `ChatGPT` 資料夾：五個 .txt 檔，沒有桌面版的時候，內容要貼到 ChatGPT 的專案裡。
- `skills` 資料夾：五個 skill 的內容。每個資料夾裡只有一個 SKILL.md，裝之前可以先點開來看。

## 裝之前先看這三條

1. 只裝你信得過的人給的。
2. 裝之前先打開看一遍，看不懂就不要裝。
3. 病人資料和密碼都不要放進去。

## Claude 桌面版

付費方案（Pro、Max、Ultra、Team、Enterprise）可以一次裝五個。免費版要一次裝一個，五個都要就做五次。Windows 和 Mac 的步驟一樣。Claude 的畫面目前沒有中文，選單都是英文，照下面的英文字找就對了。

### 付費方案：一次裝五個（我們還沒試過）

1. 下載 `etoil-ai-workshop-skills.zip`，網址在「到哪裡下載」那一節。
2. 到 Customize（自訂）→ Plugins（外掛）→ Add（新增）→ Upload plugin（上傳外掛）。
3. 選剛下載的 `etoil-ai-workshop-skills.zip`。
4. 裝好之後，五個 skill 就都有了。

Plugins 這一頁只有付費方案才有，免費版看不到。

### 免費版：一次裝一個

1. 先從上面的表格下載要裝的 ZIP。
2. 到 Settings（設定）→ Capabilities（功能），把 Code execution and file creation（建立檔案）打開。有的版本這個開關叫 Create and edit files（編輯檔案），看到哪一個就打開哪一個。
3. 找到 Skills（技能）。依版本不同，它可能在 Customize（自訂）裡，也可能在 Settings → Capabilities 裡。
4. 按「＋」→ Create skill（建立技能），點 Upload a skill（上傳技能），選剛下載的 ZIP（例如 `ask-first.zip`）。
5. 清單上出現它的英文名字後，把開關打開。
6. 一次裝一個，五個都要就做五次。

要用的時候，在句子開頭叫它的名字，例如「用『需求訪談』，我要交代這禮拜的事。」

如果叫了中文名字，它卻沒反應、直接回答，就開一個新對話，在句子開頭改打英文名字，例如 /ask-first。一次裝五個的人，就打「/」，再從跳出來的清單裡選（我們還沒試過）。

想找別人做好的 skill，可以到 Customize → Skills → ＋ → Browse skills（瀏覽技能）找。裝之前，一樣照「裝之前先看這三條」做。

## ChatGPT 桌面版

ChatGPT 的一般對話，只有公司方案（Business、Enterprise、Edu、Healthcare）才有 skill，其他方案的一般對話都沒有。想在 ChatGPT 用 skill，就在桌面版切到 Codex。切到 Codex 之後，每一種方案都能用 skill，免費版也可以。ChatGPT 桌面版在 Windows 和 Mac 上都有。

### 第一步：切到 Codex

打開 ChatGPT 桌面版，在左邊的側邊欄選 Codex。

### 第二步：加入這門課的市集（我們還沒試過）

「市集」是放外掛的地方，加進來之後才看得到裡面的外掛。

1. 打開「設定」（Settings），點左邊的「外掛程式」（Plugins）。
2. 按右上角的「新增」（Add），選「新增市集」（Add a marketplace）。
3. 在「來源」那一格輸入 `david-lai-jpg/etoil-ai-workshop-skills`。
4. 按「新增市集」。

### 第三步：安裝外掛（我們還沒試過）

1. 在「外掛程式」那一頁找到「五個 AI skill」。
2. 點進去，按「安裝外掛程式」。
3. 到「技能」（Skills）那一頁，看得到五個 skill 就是裝好了。
4. 開一個新對話，叫其中一個 skill 的名字試一次。

如果叫了名字沒反應，就打「@」，再從跳出來的清單裡選。

如果第二步跳出訊息，說需要 Git，就到 https://git-scm.com 下載安裝，再把 ChatGPT 關掉重開。這一點我們還沒確認，可能不會遇到。

Codex 能開資料夾、改檔案、執行指令，所以它要你允許的時候，看懂了再按。

### 沒有桌面版的時候

只用手機或網頁版、沒有桌面版的人，用不到 Codex 裡的 skill，可以改用「專案」（Projects）當備案：

1. 一個 skill 開一個專案，專案名稱用 skill 的中文名，例如「需求訪談」。
2. 點專案名稱旁邊的「⋯」→「專案設定」（Project settings），找到「指示」（Instructions）。
3. 打開 `ChatGPT` 資料夾裡同名的 .txt，全部複製後貼進去，再按儲存。
4. 要用的時候，到那個專案裡開新對話就好，不用叫名字。

同一個專案裡的每個對話都會照這份做法做，所以一個專案只放一個 skill。

走專案這條路的話，「做一個 skill」做出來的內容，請貼進另一個專案的「指示」。「找現成的 skill」找到的 skill，則要裝在 Claude 或 Codex 裡。

## 來源

這五個 skill 是 2026 年 11 月寫成的中文版，底稿是工程師常用的英文 skill，寫程式的部分已經拿掉：

| 中文 | 改寫自 |
| --- | --- |
| 需求訪談 | grill-me（Matt Pocock，MIT 授權）和 prompt-engineer 合併而成 |
| 深入執行 | deepen-task |
| 對立審查 | stress-test，再加上這門課自己寫的檢查提示詞 |
| 做一個 skill | create-skill（skill-forge），拿掉測試的部分，文字重寫過 |
| 找現成的 skill | find-skills（Vercel Labs，MIT 授權） |
