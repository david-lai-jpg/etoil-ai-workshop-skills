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

下面每一步的粗體字是要做的動作。底下寫「在哪裡」和「會看到」，有常見狀況的步驟再加一行「沒看到的話」。

### 先做這件事：打開建立檔案的開關

付費方案和免費版都要先做這件事。這個開關沒開，skill 不會動。

1. **打開 Claude 桌面版。**
   - 在哪裡：電腦上裝好的 Claude 桌面版（裝在電腦裡的程式，不是用瀏覽器開的網頁）。
   - 會看到：左邊有一排選單。

2. **點自己的名字。**
   - 在哪裡：左下角。
   - 會看到：出現 Settings（設定）這個選項。

3. **點 Settings。**
   - 在哪裡：剛剛出現的選項裡。
   - 會看到：Settings 的畫面。

4. **點 Capabilities（功能）。**
   - 在哪裡：Settings 的畫面裡。
   - 會看到：Code execution and file creation（建立檔案）的開關。有的版本這個開關叫 Create and edit files（編輯檔案）。

5. **打開 Code execution and file creation 的開關。**
   - 在哪裡：Capabilities 的畫面裡。如果你的畫面上寫的是 Create and edit files，就打開這一個。
   - 會看到：開關變成打開的顏色。

### 付費方案：一次裝五個（我們還沒試過）

這條路用的是 Plugins（外掛）。外掛是一包可以裝進 Claude 的東西，這門課的外掛裡包了五個 skill。Plugins 這一頁只有付費方案才有（Pro、Max、Ultra、Team、Enterprise），免費版看不到。

1. **打開下載網址。**
   - 在哪裡：上面「到哪裡下載」那一節，`etoil-ai-workshop-skills.zip` 底下那一行網址。在這個網頁上直接點它，瀏覽器（上網用的程式）就會打開它。
   - 會看到：瀏覽器開始下載 `etoil-ai-workshop-skills.zip`。

2. **找到下載好的檔案。**
   - 在哪裡：Mac 在「下載項目」資料夾，Windows 在「下載」資料夾。
   - 會看到：一個叫 `etoil-ai-workshop-skills.zip` 的檔案。ZIP 是壓縮檔，把好幾個檔案包成一個。
   - 沒看到的話：
     - Mac：Safari 有時會自動把它解開，變成一個叫 `etoil-ai-workshop-skills` 的資料夾。這時在那個資料夾上按右鍵（觸控板用兩根手指一起按），選「壓縮」，就會再得到一個 ZIP。
     - Windows：不要按「解壓縮」，檔案保持原樣就好。

3. **點 Customize（自訂）。**
   - 在哪裡：回到 Claude，在左邊的選單裡。
   - 會看到：上面有 Skills（技能）、Connectors（連接器）、Plugins 三個分頁（畫面上方的標籤，點一個就換一頁）。

4. **點 Plugins。**
   - 在哪裡：上面那三個分頁裡。
   - 會看到：Plugins 的畫面，右上角有 Add（新增）。
   - 沒看到的話：沒有 Plugins 這個分頁，代表你用的是免費版，請改做下面的「免費版：一次裝一個」。

5. **點 Add。**
   - 在哪裡：右上角。
   - 會看到：跳出一個小選單，裡面有 Add marketplace（新增市集）、Upload plugin（上傳外掛）等等。

6. **點 Upload plugin。**
   - 在哪裡：剛剛跳出來的小選單裡。
   - 會看到：一個視窗，上面寫 Drag and drop your plugin file here, or browse（意思是：把外掛檔案拖到這裡，或點 browse 去選）。

7. **把 `etoil-ai-workshop-skills.zip` 拖進這個視窗。**
   - 在哪裡：檔案在第 2 步找到的資料夾裡。用滑鼠按住檔案不放，移到視窗上再放開。不想用拖的，可以點視窗裡的 browse（瀏覽），到那個資料夾選它。
   - 會看到：Plugin uploaded.（外掛已上傳）
   - 沒看到的話：出現 Not a plugin file（不是外掛檔案），代表選到的不是那個 ZIP，請回第 2 步重新確認。

8. **點 Skills 分頁。**
   - 在哪裡：同一個 Customize 畫面上面的分頁。
   - 會看到：清單裡有五個英文名字：ask-first、go-deep、second-opinion、make-a-skill、find-a-skill。

9. **開一個新對話。**
   - 在哪裡：跟你平常在 Claude 開新對話的方法一樣。
   - 會看到：一個空白的新對話。

10. **打一句話試試。**
    - 在哪裡：新對話的輸入框（打字的那一格）。句子照最上面表格「開口這樣說」那一欄，例如「用『需求訪談』，我要＿＿＿＿。」，空白的地方換成你要做的事。
    - 會看到：它不會馬上回答，會先照那個 skill 的做法來，例如「需求訪談」會先問你問題。
    - 沒看到的話：看這一節最後面「如果叫了中文名字，它卻沒反應」那一段。

### 免費版：一次裝一個

1. **點表格裡要裝的那個 ZIP 檔名。**
   - 在哪裡：這個網頁最上面的表格，最右邊「Claude 要裝的檔案」那一欄，例如 `ask-first.zip`。
   - 會看到：瀏覽器（上網用的程式）開始下載。

2. **找到下載好的檔案。**
   - 在哪裡：Mac 在「下載項目」資料夾，Windows 在「下載」資料夾。
   - 會看到：剛剛點的那個檔案，例如 `ask-first.zip`。ZIP 是壓縮檔，把好幾個檔案包成一個。
   - 沒看到的話：Mac 的 Safari 自動把它解開成資料夾時，處理方式同上面付費方案的第 2 步。Windows 一樣不要按「解壓縮」。

3. **點 Customize（自訂）。**
   - 在哪裡：回到 Claude，在左邊的選單裡。
   - 會看到：上面有 Skills（技能）這個分頁（畫面上方的標籤，點一個就換一頁）。

4. **點 Skills。**
   - 在哪裡：Customize 畫面上面的分頁。
   - 會看到：Skills 的畫面，裡面有「＋」。
   - 沒看到的話：有的版本 Skills 不在 Customize，而是在 Settings（設定）→ Capabilities（功能）裡。照前面「先做這件事」的第 2 到 4 步，走到 Capabilities 的畫面去找。

5. **點「＋」。**
   - 在哪裡：Skills 的畫面裡。
   - 會看到：出現 Create skill（建立技能）。

6. **點 Create skill。**
   - 在哪裡：點「＋」之後出現的選項裡。
   - 會看到：出現 Upload a skill（上傳技能）。

7. **點 Upload a skill。**
   - 在哪裡：點 Create skill 之後出現的選項裡。
   - 會看到：一個視窗，上面寫 Drag and drop your skill file here, or browse（意思是：把 skill 檔案拖到這裡，或點 browse 去選）。

8. **把剛下載的 ZIP 拖進這個視窗。**
   - 在哪裡：檔案在第 2 步找到的資料夾裡。用滑鼠按住檔案不放，移到視窗上再放開。不想用拖的，可以點視窗裡的 browse（瀏覽），到那個資料夾選它。
   - 會看到：清單上出現它的英文名字，例如 ask-first。

9. **確認它旁邊的開關是打開的。**
   - 在哪裡：清單上那個英文名字的旁邊。
   - 會看到：開關是打開的顏色。
   - 沒看到的話：開關是關著的，點一下把它打開。

10. **開一個新對話。**
    - 在哪裡：跟你平常在 Claude 開新對話的方法一樣。
    - 會看到：一個空白的新對話。

11. **打一句話試試。**
    - 在哪裡：新對話的輸入框（打字的那一格）。句子照最上面表格「開口這樣說」那一欄。
    - 會看到：它不會馬上回答，會先照那個 skill 的做法來，例如「需求訪談」會先問你問題。
    - 沒看到的話：看這一節最後面「如果叫了中文名字，它卻沒反應」那一段。

12. **再裝其他四個。**
    - 在哪裡：回到最上面的表格，點下一個 ZIP 檔名，照第 1 到 9 步再做一次。五個都要的話，總共做五次。
    - 會看到：每裝好一個，Skills 的清單上就多一個英文名字。

要用的時候，在句子開頭叫它的名字，例如「用『需求訪談』，我要交代這禮拜的事。」

如果叫了中文名字，它卻沒反應、直接回答，就開一個新對話，在句子開頭改打英文名字，例如 /ask-first。一次裝五個的人，就打「/」，再從跳出來的清單裡選（我們還沒試過）。

想找別人做好的 skill，可以到 Customize → Skills → ＋ → Browse skills（瀏覽技能）找。裝之前，一樣照「裝之前先看這三條」做。

## ChatGPT 桌面版

ChatGPT 的一般對話，只有公司方案（Business、Enterprise、Edu、Healthcare）才有 skill，其他方案的一般對話都沒有。想在 ChatGPT 用 skill，就在桌面版切到 Codex。切到 Codex 之後，每一種方案都能用 skill，免費版也可以。ChatGPT 桌面版在 Windows 和 Mac 上都有。

下面的選單名稱照 ChatGPT 繁體中文介面上的字寫，放在「」裡，第一次出現時後面附英文。如果你的 ChatGPT 是英文介面，括號裡的英文就是你畫面上看到的字。每一步的寫法跟上面 Claude 那一節一樣。

### 第一步：切到 Codex

1. **打開 ChatGPT 桌面版。**
   - 在哪裡：電腦上裝好的 ChatGPT app（裝在電腦裡的程式），不是瀏覽器裡的網頁。Windows 和 Mac 都有。
   - 會看到：畫面左邊有側邊欄（左邊那一長條選單）。

2. **點 Codex。**
   - 在哪裡：左邊的側邊欄。
   - 會看到：輸入框（打字的那一格）裡的提示字，變成跟 Codex 有關的字。

### 第二步：加入這門課的市集（我們還沒試過）

「市集」是放外掛的地方，加進來之後才看得到裡面的外掛。外掛是一包可以裝進來的東西，這門課的外掛裡包了五個 skill。

1. **點自己的名字或頭像。**
   - 在哪裡：左下角。頭像就是你的大頭貼。
   - 會看到：出現「設定」（Settings）這個選項。

2. **點「設定」。**
   - 在哪裡：剛剛出現的選項裡。
   - 會看到：設定的畫面，左邊有一排項目。

3. **點「外掛程式」（Plugins）。**
   - 在哪裡：設定畫面左邊那一排，在「整合」底下。
   - 會看到：右邊的標題是「外掛程式」，右上角有「新增」（Add）。

4. **點「新增」。**
   - 在哪裡：右上角。
   - 會看到：跳出一個小選單。

5. **點「新增市集」（Add a marketplace）。**
   - 在哪裡：剛剛跳出來的小選單裡。
   - 會看到：一個視窗，裡面有「來源」「Git 參照」「稀疏路徑」三格。

6. **輸入 `david-lai-jpg/etoil-ai-workshop-skills`。**
   - 在哪裡：視窗裡「來源」那一格。可以從這裡複製再貼上，比較不會打錯。另外兩格不用填，留空白。
   - 會看到：「來源」那一格裡是 `david-lai-jpg/etoil-ai-workshop-skills`，另外兩格是空白的。

7. **點「新增市集」。**
   - 在哪裡：同一個視窗裡。
   - 會看到：畫面出現「etoil-ai-workshop-skills 市集已新增」。
   - 沒看到的話：
     - 出現「無法新增市集」：先檢查「來源」那一格有沒有打錯字或多打空格，再試一次。
     - 訊息說需要 Git（一套工程師常用的免費工具）：到 https://git-scm.com 下載安裝，再把 ChatGPT 關掉重開。這一點我們還沒確認，可能不會遇到。

### 第三步：安裝外掛（我們還沒試過）

1. **點「市集」分頁。**
   - 在哪裡：「外掛程式」那一頁的上面。
   - 會看到：清單裡有 etoil-ai-workshop-skills。

2. **點 etoil-ai-workshop-skills。**
   - 在哪裡：剛剛那個清單裡。
   - 會看到：裡面有「五個 AI skill」。

3. **點「五個 AI skill」。**
   - 在哪裡：etoil-ai-workshop-skills 裡面。
   - 會看到：這個外掛的介紹。

4. **點「安裝外掛程式」。**
   - 在哪裡：這個外掛的介紹畫面裡。
   - 會看到：這一步做完的畫面我們還沒確認，第 5 步會檢查有沒有裝好。

5. **點「技能」（Skills）分頁。**
   - 在哪裡：「外掛程式」那一頁上面的分頁。
   - 會看到：五個英文名字：ask-first、go-deep、second-opinion、make-a-skill、find-a-skill。

6. **開一個新對話。**
   - 在哪裡：回到左邊側邊欄的 Codex，在 Codex 裡開新對話。
   - 會看到：一個空白的新對話。

7. **打一句話試試。**
   - 在哪裡：新對話的輸入框。句子照最上面表格「開口這樣說」那一欄。
   - 會看到：它不會馬上回答，會先照那個 skill 的做法來，例如「需求訪談」會先問你問題。
   - 沒看到的話：叫了名字沒反應，就打「@」，再從跳出來的清單裡選。

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
