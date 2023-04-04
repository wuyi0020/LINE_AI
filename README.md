# 前言
## 推薦把下面提到的影片看完，理解小工具使用方式後再進行閱讀。不熟悉使用撰寫心得，排版糟糕請見諒

## 這個方法不是我原創的，我只是稍加改進，讓AI生成的圖片人物風格不會差太多，小程式可以自行製作或是使用這個頻道 [小礦工挖挖礦](https://www.youtube.com/@tiny_miner/featured)  的這部[影片](https://www.youtube.com/watch?v=neK1W0suvvA) 提到的IG[貼文](https://www.instagram.com/p/CpfxPY9vv6w/)中的[下載連結](https://reurl.cc/LNNj89)下載即可，也可以直接看他的影片使用他的方法

## 由於手邊電腦壞了所以就沒有測試stable diffusion可否使用或哪個 Model可以使用

## 此教學包含 
1. midjourney生成類似風格 
2. 生成類似角色 
3. 生成貼紙類型圖片

# 前置工作
---

# I.註冊midjourney 並將其帶至自己的頻道
## 1.下載並註冊一個discord帳號  [discord](https://discord.com/)
## 2.打開midjourney官網 [midjourney](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F) 點擊Join the Beta 或是點擊這個[連結](https://discord.gg/midjourney)並加入頻道
## 3.新增一個伺服器，之後回到Midjourney頻道，點擊右邊Midjourney Bot#9282 點擊藍色的新增至伺服器
## 4.下方選擇伺服器 選剛剛新增的頻道
## 5.回到剛剛新增的頻道，這樣就能在沒有其他人打擾的情況下開始製作貼圖了


# II.註冊並登入 CHAT GPT
## 1.打開[CHAT GPT](https://chat.openai.com/chat)   !注意 有時網站流量過大會進入維修 如無法進入請過幾個小時或幾天再來看看
## 2.下方可以選擇Google註冊 或 點擊Sign up註冊
## 3.註冊完成後就能看到可以輸入文字的畫面了，這樣就準備完成了

# III.下載小工具
## 1.[下載連結](https://reurl.cc/LNNj89)
## 2.在GOOGLE安裝此[插件](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf)


# 開始生成

---
# 1. 打開剛才下載並解壓縮的小工具資料夾，"咒語合成工具"的資料夾

---
# 2. 修改內容以符合生成需求
## 打開後段.txt 將內容改成
```
 digital drawing cartoon sticker, Ghibli, image black border Color, full body, flat texture cartoon style, pure white background, 2D --niji --v 5 --q 5
```
## 這個提示可以讓你生成貼紙類型的圖像 後面
```
2D --niji --v 5 --q 5
```
## 這個提示詞是midjourney的參數

---
# 3.固定角色的特徵及服飾
## 打開CHAT GPT 按下新對話 
## 輸入以下內容
```
請按以下格式提示生成5個不同的回答： 請使用以下格式：'Attire: [服裝描述], is a [種族][boy/girl][身體特徵描述]，（種族：[種族名稱]；性別：[boy/girl]；種族特徵：[種族特徵描述]；髮色：[髮色]；瞳色：[使用pupil來描述瞳孔顏色]；衣服：[衣服描述]）'服裝設定請簡單明瞭。特徵設定請不要出現面部花紋或紋身。請生成5個使用数字清單的句子，并以逗号结尾。

例如：
1. Attire: a white sundress with a floral pattern, is a half-elf girl with pointed ears and long blonde hair, （種族：半精靈；性別：女；種族特徵：尖耳朵；髮色：金色；瞳色：翠綠色的pupil；衣服：簡單的白色夏日裙）
2. Attire: a black leather jacket and ripped jeans, is a werewolf boy with shaggy brown hair and sharp claws, （種族：狼人；性別：男；種族特徵：銳利的爪子；髮色：棕色；瞳色：金色的pupil；衣服：黑色皮夾克和破爛的牛仔褲）
3.  Attire: a red cocktail dress with a sweetheart neckline, is a succubus girl with horns and a tail, （種族：魅魔；性別：女；種族特徵：角和尾巴；髮色：黑色；瞳色：紅色的pupil；衣服：紅色雞尾酒裙）
4.  Attire: a navy blue suit with a white dress shirt, is a mermaid girl with shimmering scales and long flowing hair, （種族：人魚；性別：女；種族特徵：閃亮的鱗片；髮色：深藍色；瞳色：深紫色的pupil；衣服：深藍色西裝和白色襯衫）
5.  Attire: a green tunic and brown trousers, is a hobbit boy with curly brown hair and bare, hairy feet, （種族：哈比人；性別：男；種族特徵：毛茸茸的腳；髮色：棕色；瞳色：棕色的pupil；衣服：綠色束褶和棕色長褲）
```
## 這些是用來生成角色的特徵及服飾的提示

## 選一個你喜歡的角色的英文描述複製到"後段.txt"最前面
!注意:逗號也要複製到喔，否則AI偶爾會讀不到後面的提示
## 貼上後整個提示複製並保存，晚點還會用到這個檔案

---
# 4.生成基底圖
## 4-1. 回到Discord的剛剛開好的頻道
## 4-2. 輸入 /
## 4-3.選擇 /image 那個選項![[Pasted image 20230404184528.png]]
## 4-4.貼上剛剛複製下來的角色提示
![[Pasted image 20230404184728.png]]
## 4-5.等待生成完成後選一個你喜歡的圖
![[Pasted image 20230404184854.png]]
### 排序方式是左到右 上到下
```
1 2
3 4
```
### 有看到感覺不錯的就按下 U(號碼)的按鈕
![[Pasted image 20230404185319.png]]
### 沒有的話就按藍色那個刷新鈕
![[Pasted image 20230404185309.png]]
### 比如我覺得1不錯就按下 U1
### 按下後AI就會放大圖片 這張圖就可以當作基底圖了
![[Pasted image 20230404185436.png]]
## 4-6.取得圖片網址
## 點擊圖片
![[Pasted image 20230405054116.png]]
## 左下有個 在瀏覽器開啟 給他按下去
## 複製網址列內容
## 我的圖片網址如下
```
https://cdn.discordapp.com/attachments/1092709906185986061/1092764084233064499/BUG_Attire_a_blue_button-up_shirt_and_khaki_pants_with_Olive_Sk_296a9792-f1dd-4429-90ed-e32fa0a410e3.png
```
## 除了midjourney提供的短網址外 其餘圖片連結 請找到以.png 或.jpg做結尾的連結

## 4-7.以這張圖片的連結為提示 得到圖片短網址
![[Pasted image 20230405054923.png]]
```
[你的網址] digital drawing cartoon sticker, Ghibli, image black border Color, flat texture cartoon style, pure white background, 2D --niji --v 5 --q 5
```
![[Pasted image 20230405055055.png]]
## 生成完成後 會將原本的圖片連結變成較短的網址
## 也可以上傳到其他圖片網站來取得較短的網址 如[imgur](https://imgur.com/)

## 4-8.複製短網址並打開 前段.txt 將裡面的網址替換掉 如果有一個以上基底圖 網址與網址中間需輸入一個空白鍵座分隔 不建議使用超過3張圖片作為基底圖
![[Pasted image 20230405061018.png]]


## !!!關於基底圖需要注意的點
1. 基底角色手上如果有拿東西 那會導致生成時會參考手上的東西並將其生成出來 生成後的物品通常會與手部沾黏 還有生成後的物品會很不像原本的物品 請盡量不要讓基底角色圖拿物品
2. 生成時基底角色的動作會大幅度的影響生成出來的圖片 解決方式是多生成幾張不同動作的基底圖並一起使用
3. 基底圖的服裝會一定程度影響後續生成的圖 但主要採用哪個服裝取決於提示
4. 並不是越多基底圖越好 每張基底圖的動作盡量不同 否則容易動作固定。

---
# 5.生成帶有表情及動作的LINE貼圖原型

## 5-1.打開CHAT GPT再開一個新對話
## 輸入以下內容
```
請按照以下格式進行生成五個回答：

"Expression: 表情描述, Action: 手部動作描述 "

其中，表情描述可以是各種情緒，手部動作需要與表情相配合，用以表達更生動的場景。需要注意的是，請盡量避免使用「或是」等邏輯詞，以及避免重複。另外，請注意以下幾點格式要求：

生成表情和手部動作的清單時，請使用數字清單格式。
清單內容需使用英文進行描述。
動作要有手部的描述。
清單內容不使用句號。
```
# 5-2.確認內容並糾正
如果回答有逗號 或是後面有句號
此時需要糾正他

正確格式如下
![[Pasted image 20230405052515.png]]

糾正他 輸入
```
你的格式不正確 清單內容不使用句號。
Expression: A big smile, Action: Clapping hands excitedly
Expression: A frown, Action: Arms crossed in front of the chest
Expression: Raised eyebrows, Action: Pointing with index finger
Expression: Surprise, Action: Hands covering mouth
Expression: Confusion, Action: Shrugging shoulders with palms facing upwards
```
## 5-3.確認格式正確後複製內容並生成提示
## 確認格式正確後將內容直接複製貼上到 中段.txt
![[Pasted image 20230405062100.png]]
## 5-4.雙擊打開 組合.exe
## 5-5.組合完成的模樣 ![[Pasted image 20230405062243.png]]
## 5-6.複製其中一條 到Discord貼上 並送出 然後等待生成完成
![[Pasted image 20230405062630.png]]
## 5-7.後續將圖片下載下來 並放在與切割.exe同級資料夾![[Pasted image 20230405063303.png]]
## 連點兩下 切割.exe 跑出 finish 
![[Pasted image 20230405063402.png]]
## 就是切割完畢了 接下來就自行挑選 修改圖片 並上架LINE貼圖吧

# 推薦把
