# 🦓 網絡安全懶人包

## 🎯 前言

### 🤔 誰適合使用這份指南

- 你每天都上網——為了工作，刷社交媒體，使用網上銀行等等。
- 你覺得你需要更注重保護自己的網絡安全和隱私，但你不面臨立刻的危險（如果你認為你現在就面臨危險，請尋找一對一的專家咨詢）。
- 你認為自己對科技有一定的熟悉程度。例如，在你自己的手機或電腦上修改設定你覺得沒有難度。

### 🌱 應該怎樣使用這份指南

- 安全建議按難度從低到高排列。建議從第一級別開始往難度高的進發。
- 任何人都應該參考級別一和級別二中提到的所有建議。這些建議能幫助你免受常見的網絡攻擊。完成級別一和級別二中提到的步驟的需時應該在一到兩個小時。
- 級別三覆蓋的建議需要花費更多的時間和金錢投入，這些建議並不是所有人都需要。不過如果你有相關顧慮，而且可以投入相應的金錢和時間，我們建議你也自檢這個列表中的所有建議。視你的數字安全自檢需求，這可能會需要你額外花上一個小時甚至一整個下午。
- 級別一二三以後所列出的場景應用針對的是高危情況下的安全需求，你可以略讀，看其中是否有適用於你的情景。（因為這些情景可能造成的後果比較嚴重，情景設計假設你已經完成了級別一二三中提到的所有步驟。）
- 這份指南不斷更新。歡迎發起pull要求，或者把這份指南保存到你自己的Github頁面上。

### 🕒 最後一次更新時間

- 2020年8月1日，基於2020年7月7日的英文原文。

---

## 🧐 理論和科學

### 🎯 威脅模型分析

- 你正在面臨哪種威脅？一些比較常見的威脅：信用卡被盜，商業間諜，網絡暴力等。
- 你需要保護哪些文件？常見的例子包括機密文件，私人圖片等。
- 我們每一個人都面臨一定的風險（不然的話我們也不會給我們的電腦和手機設置密碼），但我們需要瞭解清楚自己的風險，以免疏忽或者多疑恐慌。

### 🔗 最薄弱的環節/短板

- 記住，最薄弱的環節往往才是最重要的！舉個例子，如果你獲取忘記密碼的方式是你的電子郵箱，那麼黑客要做的只是黑進你的郵箱。

### 🔡 不同加密程度

1. 不加密：任何入侵帳號的第三方都可以閱讀數據。
2. 一般加密：第三方無法閱讀加密了的數據。但你所使用的平台（如Google和Facebook）仍然擁有閱讀數據的權限，它們有可能會根據法院要求把你的屬於與執法人員共享。
3. 端對端加密：數據只可以被發送方和接收方閱讀。這意味著就算是平台公司也沒有閱讀數據的權限。即使法院要求查看數據，服務商也沒有辦法提供任何信息。

### 🧩 元數據

- 是指關於你的數據的數據，比如你給什麼號碼打了電話，通話持續了多久（但不包括通話內容）。有了足夠的元數據，黑客可以拼湊出一副相對完整的關於你的信息畫像，比如你是誰，你認識哪些人，你的下一趟旅程去哪裡等等。目前，法律針對元數據的規定存在較多灰色地帶。

---

## 💦 第一級建議

### ✅ 行動清單

#### 電子郵件

- 如果你正在使用網頁版郵件服務，請確認你使用的鏈接含有`https://` 。如果沒有，請更換電郵服務商。      
- 請為你的電郵開啓二步驗證（如[Gmail](https://support.google.com/accounts/answer/185839?hl=en), [Protonmail](https://protonmail.com/support/knowledge-base/two-factor-authentication/)的設置），使用驗證軟件進行二步驗證（如[Authy](https://authy.com/), [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en))。不要使用短信驗證，已經它已不再安全
- 開啓二步驗證後，瞭解你的電郵是否支持備份碼（這是當你遺失你的設備時使用的驗證碼）。你可以在這裡瞭解如果在[Gmail進行設置](https://support.google.com/accounts/answer/1187538?hl=en)。

#### 強密碼

- 所有少於10位的密碼都是弱密碼，你可以通過使用”-“連字符號來設計由無關聯的單詞組成的長串密碼(比如strong-password-has-many-words)。
- 再三確認你重要賬號的密保問題（電郵，銀行，Facebook等）的答案不會輕易被你的朋友或者通過網上搜索有關你的資料猜到。
- 為你的各項賬號設置不一樣的密碼，因為密碼洩漏的事件經常發生。為了使你能記住不同賬號的不同密碼，你可以使用密碼管家 （[Lifehacker不同管家的測評](https://lifehacker.com/5529133/five-best-password-managers)）來儲存、自動填充及生成密碼。切記為你的重要賬號（電郵，社交媒體，銀行，雲儲存）設置唯一的不同的密碼。
- 為你的手機設置位數至少是8位，不容易被猜到的解鎖密碼。
- 如果你正在使用iPhone，關閉USB Accessories（Settings > Face ID & Passcode > Allow Access When Locked）。

#### 加密你的設備

- 加密你的手機儲存文件：[Android](http://www.networkworld.com/article/2689371/opensource-subnet/how-to-encrypt-an-android-device-in-5-steps.html)，[蘋果](https://ssd.eff.org/en/module/how-encrypt-your-iphone)（很多手機現在已經默認加密，但你不妨再次確認）。
- 加密你的手提電腦及桌面電腦的硬盤：[Windows](https://uit.stanford.edu/service/encryption/wholedisk/bitlocker), [Windows 如果沒有 BitLocker](https://veracrypt.codeplex.com/), [Mac OSX](https://support.apple.com/en-us/HT204837).
- 確保你的備份文件也是安全的！加密你的備份硬盤，同時確保你的在線備份儲存支持端對端加密（注意，iCloud和谷歌雲盤均不支持端對端加密）。
- 謹記加密只有在你的設備關閉時才完全有效。

#### 其他

- 為你的電話卡設置密碼： [iPhone](https://support.apple.com/en-hk/HT201529), [Android](https://www.digitalcitizen.life/how-change-or-remove-sim-pin-android-2-steps). 搜索你電話服務商的網站，瞭解它們的初始密碼是什麼（初始密碼會根據運營商改變）。
- 取消對那些不使用二步驗證的軟件的授權 (比如[Gmail的設置](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)).
- 關閉[Google日曆中自動接收日程邀請](https://calendar.google.com/calendar/r/settings)的设定（[瞭解為什麼](https://www.forbes.com/sites/daveywinder/2019/06/11/new-security-warning-issued-for-googles-1-5-billion-gmail-and-calendar-users/#3605ff0565e5)）。
- 開啓Facebook的[異常登錄警告](https://www.facebook.com/settings?tab=security)。
- [在Microsoft Office軟件中關閉macros](https://support.office.com/en-us/article/enable-or-disable-macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6)

### 💪🏽 養成良好習慣

#### 電子郵件

- 謹防釣魚郵件：盡可能確認郵件發件人的地址以及郵件中所有鏈接的指向地址。
- 不要打開不必要的郵件附件。如果允許的話，用在線文件系統打開/預覽文件，或者讓你的同事使用文件共享服務來傳輸文件（Dropbox, Google Drive, SpiderOak, Tresorit），這些服務會比較難破解。
- 你可以把可疑文件上傳到 [VirusTotal](http://www.virustotal.com) 進行檢測（要注意的是上傳到VirusTotal 的文檔能被安全研究者閱讀，所以不要上傳敏感信息）。

#### 更新以下這些

- 當你收到提示要更新你的操作系統（手機或電腦），馬上進行更新。
- 同樣的，及時更新手機和電腦上的軟件。
- 偶爾查看你的路由器的固體軟件以及其他與互聯網連接的設備是否需要更新。

#### 其他

- 每一兩年更改你的重要密碼（如電郵，電腦登陸，密碼管家登陸密碼）。
- 在你捐獻或者送出你的設備前清除設備上的所有資料：[手機](http://lifehacker.com/5808280/what-should-i-do-with-my-phone-before-i-sell-it)，[電腦](http://lifehacker.com/5835369/how-do-i-securely-wipe-a-computer-before-donating-it-to-charity)。
- 不要在公共充電站為你的手機充電，它們有可能在盜取你手機中的數據。你可以選擇為你的移動電池充電。

---

**👍 太棒了！現在你已經掌握了關於安全的基本信息。  
👍 獎勵自己一杯茶或者伸展一下吧。  
👍 好了， 準備好挑戰下一個級別了嗎？**  

---

## 💦💦 第二級建議

### ✅ 行動清單

#### 增強你的隱私保護

- 查看你經常使用的社交網絡的隱私設定：誰可以查看你的內容，誰可以評論你的內容，以及誰可能看到你的定位。
  - 限制Facebook對你的追蹤，關閉“Facebook站外活動”的追蹤選項（你可以閱讀[這份指南](https://www.eff.org/deeplinks/2020/01/how-change-your-facebook-activity-settings)）
- 查看你常用的聊天軟件上的隱私設定：閱讀回執，顯示你“最後一次在線”的時間戳，以及你的手機號碼和帳號頭像是否公開可見。
- 安裝這些瀏覽器擴展軟件來保護你的隱私，並保證它們在隱私瀏覽狀態下也是開啓的：
  - 廣告攔截（如 [uBlock Origin](https://github.com/gorhill/uBlock/), [Ghostery](https://www.ghostery.com/)）。
  - 跟蹤攔截 （[Privacy Badger](https://www.eff.org/privacybadger)）。
  - [HTTPS Everywhere](https://www.eff.org/https-everywhere)。
- 查看你智能手機上的哪些軟件能獲取你的地理位置信息。如果該軟件並不需要地理位置信息，關閉權限。盡可能僅少一直追蹤地理位置信息的軟件數量。
  - iOS：設定→私隱→定位服務
  - 安卓：設定→應用程式及提示→應用程式權限
- 如果你擁有智能音響，關閉它的錄音功能：[Google Home](https://myaccount.google.com/activitycontrols/audio) 和 [Amazon Alexa](https://twitter.com/geminiimatt/status/1125611726773334017) 的關閉指南。

#### 其他

- 給你的設備設置可以讓你遠程跟蹤，清除和加密設備的第三方應用（如 [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/)）。
- 查閱你主要的電子郵件和社交媒體賬號上的“第三方應用”或者“綁定應用”。這些應用有可能可以獲取你的Facebook數據，甚至主動為你發佈信息。（[這篇文章介紹了如何在Facebook和谷歌郵箱中查看授權信息](https://www.online-tech-tips.com/computer-tips/check-google-facebook-connected-apps/)）
- 查閱你電腦的瀏覽器都由哪些擴展應用，刪除那些你在一段時間內沒有使用過或者不記得安裝過的應用。
- 下載 [Stethoscope](https://ragtag.org/stethoscope) 並在你的電腦上運行，它可以幫助實現你的基本安全設置（比如加密，防火牆，屏幕鎖等）。

### 💪🏾 養成良好習慣

#### 增強的你隱私保護

- 少在網上發佈個人信息，特別是那些可以被用於驗證，跟蹤你或者實現釣魚的信息（地址，手機號碼，生日等）。
- 如果你擁有域名，開啓WHOIS隱私服務並持續使用它，這個服務的花費是值得的。但要注意的是WHOIS有歷史查詢工具，如果你曾經提供過你的真實地址，你很難完全清除那些記錄。

#### 在線上群組中謹言慎行

不要在“私人”Slack群組，Facebook頁面，WhatApp群组，或Telegram上發表任何你之後會後悔的言論，因為：

- 群組裡的任何人都可以洩漏所有數據
- 群組管理員通常有權限查看群裡的所有內容，包括群裡成員之間的私人對話，甚至可以刪除私人聊天信息。
- 即使你沒有使用你的真實姓名或者照片，你所說的話通常能夠追溯到你用於註冊該帳號的手機號碼或郵箱。
  - 防止在Telegram上洩露你的信息，在 Settings → Privacy and Security → Phone Number，更改一下設置：
    Who can see my phone number 改為 Nobody
    Who can find me by my number 改為 My Contacts



#### 其他

- 在下載新的手機應用程式時，再三確認它是否你想要的應用——市面上有很多山寨應用程式通過稍微更換流行軟件的名字或圖標來欺騙用戶。
- 每隔一段時間查看你的手機上安裝了哪些軟件，刪除那些你不再使用的軟件。
- 如果你需要給某人發送一個密碼，把它分成兩個部分用不同的途經發送（如電子郵件加語音童話）。
- 給你手提電腦的攝像貼上貼紙，或者其他可以遮擋攝像頭的配件。
- 不要用Google、Twitter、或者Facebook帳號登陸其他網站，每個網站和服務應該有自己的獨立的帳號。

---

**🎉 恭喜！你对網絡安全的掌握已经到一定程度了！休息一下吧，明天再回來進行級別三的安全檢查。**

---

## 💦💦💦 第三級建議

### ✅ 行動清單

#### 為敏感文件上鎖

- 列出你不想被其他人接觸到的文件（如私人照片，護照文件等）。
- 用 [Cryptomator](https://cryptomator.org/) 或 [Veracrypt](https://www.veracrypt.fr/en/Home.html) 建立加密，密碼保護的空間來保護這些文件。
- 在你的電腦和手機上到進行這樣的設置。
- 把文件移動到這些空間裡面。保證敏感文件不再存在於你手機或其他舊的文件夾中。

#### 升級你的裝備
- 使用公共網絡（如咖啡館的wifi網絡）時使用付費VPN，甚至當你使用家庭網絡但是不希望你的網絡運營商獲取你的訪問數據時也應該使用付費VPN。免費VPN是一個壞的選擇，因為其運營者並沒有足夠的動力保護你及你的數據。有關VPN的推薦，查看[Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/)或[Freedom of the Press](https://freedom.press/training/choosing-a-vpn/)。
- 為你的手提電腦及手機購買防窺屏（這可以防止旁人偷看你的屏幕，你可以查看比如[3M的產品介紹](https://www.3m.com.hk/3M/zh_HK/company-hk/all-3m-products/~/%E6%89%80%E6%9C%89-3M-%E7%94%A2%E5%93%81/%E8%BE%A6%E5%85%AC%E5%AE%A4%E5%8F%8A%E5%AD%B8%E6%A0%A1%E6%96%87%E5%84%80/%E7%86%92%E5%B9%95%E9%98%B2%E7%AA%BA%E7%89%87%E8%88%87%E4%BF%9D%E8%AD%B7%E8%86%9C/?N=5002385+8710660+8710873+8711017+3293746351&rt=r3)）

#### 看看你的旧密码

- 把你的在線賬號的密碼都存儲在密碼管家中。如果你正確安裝了瀏覽器擴展，它會自動在你的登陸過程中把相關的賬號信息都抓取。
- 借助你的密碼管家的分析工具，看看哪些賬號使用了弱密碼，更新那些你認為含有任何個人信息或者你不想遺失的網絡賬號的密碼。

### 💪🏾 養成良好習慣

- 使用[Signal](https://whispersystems.org/)。這是一款支持端對端加密的手機聊天軟件，一般被認為是安全的聊天軟件。除了Signal以外，很少有對安全聊天軟件的共識，人們通常會感性地選擇自己認為最安全的軟件。
- 閱讀這篇對比[安全聊天軟件](https://www.securemessagingapps.com/)的文章，瞭解除端對端加密以外的更多安全考量，以及你能接受哪些性能或安全上的妥協。
- 在打語音或視頻通話時，使用端對端加密的軟件（比如Signal, Jitsi, Wire）。
- 買一部難破解的手提電話（$$$），這種電話通常比較昂貴。一般來說，蘋果手機以及使用Google版本Android系統的安卓手機相對安全。

---

**😲 哇，你把最難的網絡安全步驟都走完了，好樣的。接下來你可以快速閱讀以下場景設定，看是否有適合你的情境。**

---

## 💦❗️ 基於特定情境

---

### 👩🏿‍💻 在視訊平台（如Zoom）上組織公開活動

- 為你遠程會議設置會議密碼，防止不相關人員通過工具通過隨機尋找會議ID加入你的回憶。考慮提前設立活動註冊系統，這樣一來你就不需要公開你的會議鏈接或密碼。
- 熟悉你要使用的平台，最大限度減少非會議主持人所需要的控制權限（如屏幕共享等，比如[在Zoom上的設置](https://blog.zoom.us/zh-tw/%e5%a6%82%e4%bd%95%e9%98%b2%e6%ad%a2%e4%b8%8d%e9%80%9f%e4%b9%8b%e5%ae%a2%e5%b9%b2%e6%93%be%e6%82%a8%e7%9a%84-zoom-%e6%b4%bb%e5%8b%95/)）。
- 創建一套方案來應對干擾你活動的不速之客。
- 不要在平台上說那些你不會在公共場合說的話，並且建議參與會議人員謹言。大部分商業平台都有權限讀取你的音視頻數據，並且會通過挖掘你的元數據來創建消費者檔案。

---

### 🛫 當你需要跨境

- 關閉你的設備，因為：
  - 存儲和硬盤僅僅在關閉狀態下才是加密的，睡眠模式下並非處於加密狀態。
  - 這能保證你的移動設備在開啓時需要密碼才可能登陸，在一些地區你的密碼受言論自由等法律的保護。
- 在你的設備上存儲盡可能少的信息。如果你的設備被扣留了，其他人無法獲取你沒有存儲的信息。
- 謹慎選擇你在設備上貼的貼紙，海關人員可能會認為這些貼紙代表可疑信息和行動。
- 把你的航班信息和事件告訴你的朋友。在你的旅途中定期與你的朋友聯繫。如果你在指定時間沒有出現的話讓他們聯繫律師及有關機構。
- 如果你面臨的是極端高風險的情況（以下這些措施有可能會引起懷疑，讓你的情況更糟）：
  - 另外建立一個相冊，郵件地址，和社交媒體賬號，這些賬號里都是沒有可疑的內容。
  - “忘記” 你的密碼：為你的設備和賬號上密碼鎖，只有你信賴的朋友有另一半密碼。
  - 登出你所有的重要賬號（或者直接把你的設備放在家中）。
- 如果想瞭解更多信息，看以下這兩篇有關如何在美國邊境要求律師協助的文章：Wired's [Guide to Getting Past Customs With Your Digital Privacy Intact](https://www.wired.com/2017/02/guide-getting-past-customs-digital-privacy-intact/) 和 [BoingBoing's addendum](http://boingboing.net/2017/02/12/how-to-cross-a-us-or-other-b.html) 。

---

### 😭 有人拿走了我的手機/電腦！

- 遠程清除你手機上的所有信息：[Android](https://support.google.com/accounts/answer/6160491?hl=en), [iOS](https://support.apple.com/kb/PH2701?locale=en_US)的教程。
- 用其他設備登出你所有的重要賬號。
- 如果這發生在跨過邊境：要求對方提供扣留收據（僅在某些國家有效，如[加拿大](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf)）。
- 獲取新的電話卡。
- 如果你重新獲得你的設備，恢復出廠設置。使用反病毒和反間諜軟件確保你的設備沒有可疑軟件。

---

### 👾 我覺得我的電腦被入侵了！

- 下載一個能在你的數據被發送到其他設備時提示你的軟件，如 [Little Snitch for Mac](https://www.obdev.at/products/littlesnitch/index.html).
- 蘋果電腦上運行 “活動監視器“（Activity Monitor）或者Windows系統上的 ”進程瀏覽“ （Process Explorer），查看有那些進程正在運行。搜索那些看起來可疑的名字。
- 登陸重要的網絡賬號，查看是有其他可疑登陸，詳細教程在這裡閱讀：[Motherboard:  How to Tell if Your Account Has Been Hacked](https://vice.com/en_us/article/bjeznz/how-do-you-know-when-youve-been-hacked-gmail-facebook)。
- 使用一部閒置的智能手機運行[Haven](https://guardianproject.github.io/haven/) ，這個軟件可以幫助你偵測入室行為。

---

### 🍆 性短信及無共識的照片分享

- 查看 [The Motherboard Guide to Sexting Securely](https://vice.com/en_us/article/mb3nd4/how-to-sext-securely-safely-what-apps-to-use-sexting).

---

### ✊🏾 如果你要參與遊行

#### 如果出現緊急狀況

- 前把求助信息和收件人放在草稿箱，收件人應該是你信賴的並且不再遊行現場的朋友或者是法律熱線。在你被捕或者有緊急情況時及時發出。
- 以防萬一，在你的手臂上用不易擦去的油性筆寫上可信好友或求助熱線的電話。
- 隨身攜帶你手機的後備電池。
- 如果你使用指紋或者面部解鎖，請暫時關閉這項功能。在某些國家和地區，[執法人員可以強制你提供你的指紋但不能強制你提供密碼](https://www.theatlantic.com/technology/archive/2016/05/iphone-fingerprint-search-warrant/480861/)。
- 被捕後要馬上關閉你的手機（硬盤加密功能在手機關閉狀態下更安全）。
- 考慮使用一次性手機。

#### 分享少之又少的信息

- 存儲盡可能少的個人信息或者對你不利的信息，你永遠不知道你的設備會落在誰的手上。
- 如果你的聊天軟件支持閱後即焚，請開啓這個設置。
- 如果你需要分享照片，用[這些軟件](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/)清除所有元數據。

#### 最少化地理位置追蹤

- 關閉定位歷史：
  - iPhone: Settings > Privacy > Location Services > System Services > Significant Locations
  - Android: Settings > Google > Google Account > Data & personalization > Location History > Manage setting > Your account & all your devices > turn off Use Location History Off
  - Google 地圖: Settings > Maps history > Web & App Activity
- 刪除過去的定位歷史：
  - iPhone: Settings > Privacy > Location Services > System Services > Significant Locations > Clear History
  - [Android](https://support.google.com/accounts/answer/3118687?hl=en#delete)
  - [Google 地圖](https://support.google.com/maps/answer/3137804?hl=en)
- 考慮臨時關閉所有地理位置追蹤功能：
  - iPhone: Setting > Privacy > Location Services > Location Services Off
  - Android: Setting & location > Location > Use location Off
  
#### 其他

- 再三確認你的聊天軟件的隱私設置。
- 關閉信息預覽功能：
  - iOS: Settings > Notifications > Show Previews: When Unlocked
  - Android: Settings > Apps & notifications > Notifications > On lock screen: Hide sensitive content
- 記得使用如[Signal](https://signal.org/)和Whatsapp等端對端加密軟件進行語音通話。
  
---

### 📰 我是報道敏感議題的記者

以下是一些所有記者都要考慮實踐的基本安全設置。如果你報道的是特別敏感的議題或地區（如「吹哨人」報道），你和你的團隊需要按需向專家咨詢。

#### 時刻做好以下準備

- 通過跟蹤軟件遠程清除你設備上的內容（如蘋果上的 [Find My](https://www.apple.com/icloud/find-my/) ，Android [Find My Device](https://support.google.com/accounts/answer/6160491?hl=en)， [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/)）。
- 成為釣魚郵件的接收者（記者本來就比其他人收到更多的郵件）。

#### 保護自己

- 如果你正在旅途中，閱讀上述`當你需要跨境`情境的安全建議。
- 如果你要報道一場示威運動，閱讀上述`如果你要參與遊行`情境的安全建議，自行判定你需要作出哪些安全措施以及哪些記者權利適用於你。
- 果你在辦公室上網，使用VPN。網管通常可以看到你來自哪裡，舉個例子，他們可以看到你來自紐約時報的網絡。

#### 保護你的信源

- 用 [Signal](https://www.signal.org/) 或 [Jitsi](https://jitsi.org/) 進行端對端加密的視頻和音頻通話。
- 讓你的機構設置 [SecureDrop](https://securedrop.org/)。如果沒有設置或無法設置的話，鼓勵人們使用[OnionShare](https://onionshare.org/)或 [Firefox Send](https://send.firefox.com/)。
- 模糊處理照片和視頻中的人臉 (如Android [ObscuraCam](https://guardianproject.info/apps/obscuracam/), Youtube [教程](https://technology.witness.org/2016/02/how-to-use-youtubes-new-blurring-feature-to-protect-identities/))。
- 用[這些軟件](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/)刪除多媒體的元數據。
- 閱讀Ted Han 和 Quinn Norton的 [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/).
- 閱讀Martin Shelton的 [Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/).

#### 保護你的數據

- 確保你正在使用的郵件和存儲空間服務商的所有人不是你正在報道的國家或者機構，也不存在與這些國家和機構的任何聯繫。
- 盡可能把所有敏感數據存放在帶密碼的雲盤或者移動設備上。有關如何加密敏感文件的教程可以看上文`為敏感文件上鎖`。
- 不要忘記從你的電腦上永久刪除敏感文件，可以選擇使用 [Eraser for Windows](https://eraser.heidi.ie/) 或 [File Shredder for Mac](https://apps.apple.com/us/app/fileshredder/id418094085?mt=12)。

#### 更多信息

- 如果你處於非常規的國家，地區或面臨不一樣的情境，閱讀Grégoire Pouget of Nothing2Hide's 的這篇指南： [Digital Security for Journalists Requires an Adaptable Toolkit](https://gijn.org/2019/07/16/digital-security-for-journalists-requires-an-adaptable-toolkit/)。
- 如果你運營一個新聞編輯團隊，閱讀 Ontheline Newsrooms 的 [Measures for Newsrooms and Journalists to Address Online Harassment](https://newsrooms-ontheline.ipi.media/).

---

### 🕵🏼‍♂️ 人肉搜索/起底和網絡暴力

根據你的攻擊者，人肉搜索/起底和網絡暴力可以是非常具體和複雜，它可以包含你的工作等與你相關的所有信息。雖然我們提供了以下這些一般建議，但我們強烈建議你判定你的情況有沒有升級到需要與專家進行一對一咨詢。

#### 找一個你信任的朋友

- 不要自己把自己困起來，獨自面對這些情況。
  - 最基本的，找一個你信任的朋友作你的支撐，並分析情況有多糟糕。
  - 同時，我們建議你找一個你信任的朋友幫你調查，記錄，舉報和屏蔽騷擾者。你可以閱讀 Take Back The Tech's [Hey Friend!](https://www.takebackthetech.net/know-more/heyfriend) 這篇指南。有時候，交出你的手機和社交媒體帳號或許對你更有用，因為你的創傷不會總是被刺激。
- 另外，你可以向你所身處的網絡社群尋去幫助。閱讀PEN America的這篇文章：[Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/cyber-safety/deploying-your-supportive-cyber-communities/).
- 如果沒有人能馬上幫助你，Heartmob提供了一份[支援機構的清單](https://iheartmob.org/resources/supportive_organizations)，其中一些提供24小時服務。

#### 跟蹤任何更新，收集清單

- 設置 [Talkwalker](https://www.talkwalker.com/alerts) 和 [Google Alerts](https://www.google.com/alerts)追蹤你的名字和暱稱。
- 用你認為最簡單的軟件清楚記錄每一起網絡暴力（日期，時間，描述，截屏）。

#### 從互聯網上移除關於你的信息

- 给[PrivacyDuck](https://www.privacyduck.com/) 付費，清除你在網上的信息。如果你是運動家，你可以聯繫[Equity Labs](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c)，獲取折扣價。
- 给[Reputation.com](https://www.reputation.com/) 付費， 從付費網站上移除你的信息，並後續跟蹤這些網站，確保信息保持移除。
- 你也可以用 [PrivacyDuck](https://www.privacyduck.com/resources/) 和 [Motherboard](https://vice.com/en_us/article/ne9b3z/how-to-get-off-data-broker-and-people-search-sites-pipl-spokeo) 的免費資源幫助你移除相關信息。

#### 隱藏你的個人信息

- 使用 [Burner](http://www.burnerapp.com/)獲取一次性號碼來打電話或發短信。
- 用[Traveling Mailbox](https://travelingmailbox.com/) 隱藏你的真實郵編。
- 刪除所有老舊網絡帳號。用[Justdelete.me](http://justdelete.me) 幫助你實現這個過程。
- 檢閱你的社交媒體帳號，刪除所有過多個人信息的帖子，比如那些涉及你的住址，你去哪裡，和誰去等信息。
- 如果你是Twitter用戶：
  - 求助於你的社區，建立一個[屏蔽清單](https://help.twitter.com/en/using-twitter/advanced-twitter-block-options)，屏蔽那些為人熟知的攻擊者。
  - 用[Semiphemeral](https://micahflee.com/2019/06/semiphemeral-automatically-delete-your-old-tweets-except-for-the-ones-you-want-to-keep/) 刪除你不想要的推文（需要使用命令列介面）。
- 閱讀接下來的安全建議。

#### 忽視/回應/舉報/屏蔽對你網絡暴力的攻擊者

- 基於你對網絡暴力事件的記錄，以及你朋友的支持，確定你想要採取的應對策略（這些策略並非惟一的）：
  - 忽視：如果得不到任何注意，有時施暴者會自然而然地離開。
  - 降級：有時你可以使用冷靜的語言在事件變得更壞前降溫。
  - 舉報：向平台或者有關的執法部門舉報實施網絡暴力的人。
  - 在社交媒體靜音（mute）你的攻擊者：讓你自己可以有個清淨。
  - 在社交媒體封鎖/屏蔽（block）你的攻擊者：你的攻擊者將無法看到你的帖子。但注意，你的攻擊者可以知道你封鎖/屏蔽了它們，並認為這是在升級事件。
  - 公開事件：有可能帶來危險，但有時候公開譴責他們的行為並獲取公眾支持能使他們停止暴力。

- 推特Twitter用戶：
  - 求助於你的社區，建立一個[屏蔽清單](https://help.twitter.com/en/using-twitter/advanced-twitter-block-options)，屏蔽那些為人熟知的攻擊者。
  - 用[Bot Sentinel](https://botsentinel.com/)屏蔽機器人水軍。
  - 大批屏蔽某類型的追蹤者以減少水軍攻擊，你可以使用[Twitter Block Chain](https://github.com/satsukitv/twitter-block-chain)。
  - 查看你的帳號被添加到了哪些追蹤列表中（Profile > Lists > ... > Lists you're one）。如果你覺得這些列表中有可疑的列表或者列表創建者，點擊右上角的三個點可以舉報該列表，以及屏蔽列表創建者並退出列表。

#### 更多信息

- Feminist Frequency: [Speak Up & Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/).
- TrollBusters: [What to Do? Where to Go? Infographic](https://yoursosteam.wordpress.com/what-to-do-infographic/).
- Equity Labs: [Anti-Doxing Guide for Activists Facing Attacks from the Alt-Right](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c).
- HeartMob/Hollaback: [Technical Safety Guide](https://iheartmob.org/resources/tech).
- Crash Override (RIP): [So You've Been Doxed](http://www.crashoverridenetwork.com/soyouvebeendoxed.html), [Preventing Doxing](http://www.crashoverridenetwork.com/preventingdoxing.html).

---

### 👀 在互聯網上移除和你相關的信息

如果你即將成為公眾人物，或者正在經歷網絡暴力，考慮進行採取以下建議。

#### 清理你的社交媒體偏好設置

你或許不需要完全刪除你的帳號，你可以考慮刪除那些久遠的或者暴露了太多個人信息，比如你在哪裡居住，經常出入哪裡，和誰一起的帖子（或者改為盡個人可見）。

- Facebook：
  - 查看你的公開主頁，移除或者限制相關信息。
    - 在網頁版上，到你的個人檔案 Profile 頁面，點擊編輯個人檔案 Edit Profile 按鈕右邊的 👁 圖案。
    - 在手機版上，進入你的個人檔案 Profile 頁面，點擊 Add Story 右邊的三個點，並點擊 View As。
  - 更改設置，使只有你的朋友可以查看你的歷史貼文。
    - 在網頁版上，進入Setting > Privacy > Limit Past Post。
    - 在手機版上，進入Setting & Privacy > Settings > Privacy Settings > Limit who can see past posts。
  - 如果需要批量刪除貼文，查看[PC Magzine的這篇文章](https://www.pcmag.com/how-to/how-to-quickly-delete-old-facebook-posts)。
- Whatsapp：
  - 滑動刪除個人對話紀錄。
  - 刪除所有對話，但保留群組：Setting > Chats > Clear All Chats.
  - 刪除所有對話，並刪除所有群組：Setting > Chats > Delete All Chats.
  - 關閉對話備份（Setting > Chats > Chat backup）並刪除歷史備份（[iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)）。
 - Instagram：
  - 瀏覽你的個人主頁，並手動刪除貼文（點擊圖片右上角的三個點）。
  - 如果有需要，可以通過[第三方軟件](https://upleap.com/blog/how-to-delete-an-instagram-post/)批量刪除貼文。
 - Twitter：
  - 使用第三方服務選擇你希望保留的推文，並刪除剩下的推文。我們推薦[Semipheral](https://semiphemeral.com/)（免費且開源，但僅有測試版），[TweetDelete](https://tweetdelete.net/)（有免費或付費的選擇），或者[Twitter Archive Eraser](https://martani.github.io/Twitter-Archive-Eraser/)（有免費或付費的選擇）。
 - Reddit或其他論壇：
  - 通常沒有一步到位的簡單方法。有些時候你需要完全刪除你的帳號。對於Reddit，你需要使用[第三方腳本](https://social.techjunkie.com/how-to-delete-all-reddit-posts/)，因為即使你刪除了你的帳號你的貼文也都還在。

#### 從別人網站上刪除你的信息

  - 付費使用[PrivacyDuck](https://www.privacyduck.com/)或者[Reputation Defender](https://www.reputationdefender.com/)移除英文公開和付費網頁上關於你的信息。PrivacyDuck針對不同人群的[優惠計劃](https://www.privacyduck.com/discount-programs/)，查看你是否適用。
  - 如果你希望自己刪除，你可以使用[PrivacyDuck的指南](https://www.privacyduck.com/resources/)，和Yael Grauer的[Big Ass Data Broker Opt-Out List](https://docs.google.com/document/d/1ElB7VXmr5JEkFaLJpO7YLGrAuasedmq-rZC-8TUMxTM/)。（為了保證100%的刪除相關信息，在使用付費服務的基礎上再使用這些指南）。

#### 隱藏你的個人信息

  - 使用[Burner](http://www.burnerapp.com/)或者[Hushed](https://hushed.com/)來獲取打電話和發信息所用的一次性號碼。
  - 使用PO box郵寄地址，或者用[Traveling Maibox](https://travelingmailbox.com/)（僅限美國）來隱藏你的家庭住址。
  - 刪除舊的網絡帳號來清楚你在互聯網上留下的痕跡。用[JustDeleteMe](https://justdeleteme.xyz/)幫助你刪除這些信息。

---

### 💔 我感覺我的伴侶在監視我的手機（跟蹤監視軟件 Stalkerware）

**如果你對此不確定，且你與伴侶的關系還不算太糟糕：**

- 用紙筆記錄可疑事件，把這份記錄藏起來。
- 確保你的伴侶沒有通過此前共享的帳號或者你的[谷歌地圖上的共享位置功能](https://support.google.com/maps/answer/7326816?co=GENIE.Platform%3DAndroid&hl=en)等得知你的信息。
- 查閱並重復級別1-3中的所有步驟。重置密碼，查看你的隱私/數據共享許可，看看你的電腦和手機上有沒有你無法識別的軟件。
- 留意其他信號，比如你的手機電池不像比以前續航時間短，手提電腦的網絡慢。你可以閱讀Coalition Against Stalkerware的文章看看有沒有遇上[其他信號](https://stopstalkerware.org/get-help/)。
- **不要馬上刪除可疑軟件** -- 你或許需要保留它們作爲證據。此外，刪除可能會導致情況惡化。

**如果你比較確定你的伴侶正在監視你，且感到害怕：**

- 尋求幫助。你不應該自己一個人面對：
  - 找一臺公共或者朋友的手機/電腦聯系Coalition Against Stalkerware收集的[這份列表上的機構](https://stopstalkerware.org/get-help/resources/)，其中有些可以幫助你搜集證據，安全地移除跟蹤監視軟件。
  - 通過公共設備或者電話聯系可信好友，讓他們幫你分析情況到底有多糟糕。
- 保留所有數字和紙質證據，比如相關的短訊，郵件，來電等。你可以閱讀NNEDV的這篇[記錄保存證據的指南](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence)。
- 當你不再需要這些證據，逐一在你的設備上刪除可疑軟件和跟蹤監視軟件，或者重置出廠設置。（買一部新的設備會更加安全）。務必手動重裝軟件和導入數據，免得你在恢復備份的時候把跟蹤監視軟件一並恢復。

**更多其他信息**

- 閱讀Wirecutter這篇教你[防範家暴者](https://thewirecutter.com/blog/domestic-abusers-can-control-your-devices-heres-how-to-fight-back/)的文章
- 閱讀Coalition Against Stalkerware的[安全工具指南](https://stopstalkerware.org/get-help/)

---

### 👤 我不想給在線約會/交友/組織提供我的真實手機號碼

有些軟件需要用你的手機號碼註冊（如Signal和Whatsapp），你可以通過以下這些渠道獲得第二個手機號碼：

- [Twilio](https://www.twilio.com/) (1 USD/月, 設置過程相對複雜，可以閱讀[這裡](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46) 以及 [這個指南](https://source.opennews.org/articles/shields-using-signal-without-your-phone-number/))
- [Burner](https://www.burnerapp.com/) (5 USD/月, 但支持短期預付)
- [Google Voice](https://voice.google.com/about) (免費，但僅在美國有效)
- 手機運營商：買一個預付卡，費用不同

但注意：

- 如果你失去或者不再訂閱你的第二個手機號碼，其他人可以購買這個號碼並盜用你的身份。
- 絕大部分的公司會把你的信息交給相關部門，如果後者有提供正確的請求文件。

#### 要做到完全匿名，使用假名建立一個無法被追蹤的網絡身份

- 如果你是公眾人物，藝術家或者運動活躍人士，你可以考慮用一個假名或者集體身份，閱讀[Tactical Tech manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online) 瞭解更多細節。
- 完全安全匿名，使用這個指南：  [creating untraceable online accounts and protecting your real identity](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46).

---

### 🤐 出行目的地沒有很好的數據保護條例，或者有網絡審查

- 注意手機運營商可能會在未經你同意下與第三方共享你的地理位置信息和個人信息。
- 在你出行前設置VPN以便 a）不受影響地接入服務，b）最少化對你的數據收集。避免免費的VPN或者擁有者不明的VPN服務。閱讀[Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/)和[Freedom of the Press](https://freedom.press/training/choosing-a-vpn/)的建議。
- 考慮帶一次性電話出行，並把你的個人電腦留在家。如果你有工作需要，需要安裝新的和未經檢測的，有可能侵犯你的數據隱私的軟件在你的設備上，這一條尤其有用。
- 重新評估哪些在線服務是安全的：
  - 如果可以，閱讀你最常用的服務的透明度報告，看他們多常與執法部門等恭喜那個數據：
    - [Google Transparency Report: Request for user information](https://transparencyreport.google.com/user-data/overview)
    - [Facebook Transparency Report: Government Requests for User Data](https://transparency.facebook.com/)
    - [Apple Transparency Report](https://www.apple.com/legal/transparency/)
  - 查看這些服務商的總部在哪裏，以及這會如何影響它們的隱私政策。

### 😣 我需要幫助，我的系統正在遭受攻擊

如果你爲公民組織工作，你可以聯系：
- Access Now's [Digital Security Helpline](https://www.accessnow.org/help/)
- 人權捍衛者（Front Line Defender）的 [Emergecy Contact](https://www.frontlinedefenders.org/zh-hant/node/2814)

如果你時間充裕，你可以申請Digital Defenders Partnership [Incident Emergency Grant](https://www.digitaldefenders.org/sections/about-us/emergency-grants/).

---

## 💦❓ 其他建議

這部分內容提供相對萬用的安全建議，適用於不面臨以上幾種情境的普通用戶。

#### 電子郵件

- 設置 [Protonmail](https://protonmail.com/) 或 [Tutanota](https://tutanota.com/) 進行端對端加密郵件。
- 使用PGP加密郵件。

#### 設備權限

- 購買 [YubiKey](http://www.amazon.com/Yubico-Y-072-YubiKey-NEO/dp/B00LX8KZZ8/ref=sr_1_1?ie=UTF8&qid=1421839152&sr=8-1&keywords=yubikey+NEO) USB key 來進行二步驗證。
- 用含有字母和數字的密碼來解鎖你的手機。
- [Generating Diceware passwords](http://world.std.com/~reinhold/diceware.html).

#### 文件存儲和共享

- 用端對端加密的雲儲存設備（Dropbox並不是其中之一）：[Tresorit](https://tresorit.com/), [SpiderOak](https://spideroak.com/).
- 使用加密的移動硬盤和USB，[Apricorn](https://www.apricorn.com/)等公司有提供這些硬件。
- 如果你需要匿名發送文件，使用特殊的文件共享服務，如 [OnionShare](https://onionshare.org/)等。
- 使用 [CryptPad](https://cryptpad.fr) （開源，端對端加密）而非谷歌文件和微軟辦公室。

#### 聊天軟件

- WhatsApp 設置：
  - 要100%實現端對端加密，關閉聊天記錄備份 (Settings > Chats > Chat backup) 並刪除你之前的備份 ( [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).
  - 在Whatsapp上開啓安全通知 (Settings > Account > Security)
  - 設置一個密碼，防止你的帳號在你不知情的情況下被移動(Settings > Account > Two-Step Verification)
- Telegram：
  - 使用"Secret Chat"來確保安全對話（注意，這個功能呢個意味着你的對話內容不會出現在電腦版或網頁版的Telegram）
  - 僅允許你的聯系人添加/尋找你
  - 開啓Secret Chats中的自我刪除倒計時功能（self-destruct timers）
- 閱讀這份關於[安全聊天軟件](https://www.securemessagingapps.com/)的列表，了解更多除端對端加密以外的其他安全和便利性考量。

#### 搭建/運營網站

- 閱讀[EDRI關於網站運營的倫理考量](https://edri.org/ethical-web-dev/)。特別留意對隱私的討論和建議。
- 保護你的網站免受阻斷服務攻擊等其他攻擊：
  - [Deflect](https://deflect.ca/)（有免費版本提供給非盈利組織）
  - Cloudflare (有 [有提供給藝術、人權、公民社會、記者、捍衛民主等組織的免費版本](https://www.cloudflare.com/galileo/)
  - 谷歌[Project Shield](https://projectshield.withgoogle.com/):僅對新聞、人權、選舉監察想光的網站開放。
  - [Themes Security Wordpress 插件](https://wordpress.org/plugins/better-wp-security/)
- 考慮使用更加注重隱私的網站搭建服務，如[Greenhost](https://greenhost.net/)，或者 [Gecko & Fly](https://www.geckoandfly.com/32144/anonymous-offshore-web-hosting/) 和 [PrivacyTools](https://www.privacytools.io/providers/hosting/)推薦的。
  - 建立一個[安全文檔](https://securitytxt.org/) 以便研究人員可以發布安全隱患。

#### 其他

- 購買[YubiKey](http://www.amazon.com/Yubico-Y-072-YubiKey-NEO/dp/B00LX8KZZ8/ref=sr_1_1?ie=UTF8&qid=1421839152&sr=8-1&keywords=yubikey+NEO)用以進行二步驗證。
- 確保你的設備上有盡可能少的信息，數據，或照片。
- 不要使用智能电视或者智能音箱。
- 用[DuckDuckGo](http://duckduckgo.com/)匿名搜索。
- 如果你或者你的機構深度使用Google Suite，考慮Google的[Advance Protection program](https://www.wired.com/story/google-advanced-protection/)。
- 把你的信用卡，護照，設備等放在法拉第籠（Faraday Bag）里，它可以屏蔽任何信號傳輸。 ([Micah Lee 的指南](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
- 使用更安全的操作系統： [Tails](https://ssd.eff.org/en/module/keeping-your-data-safe) (可以通過ＵＳＢ盤使用) 或者 [Qubes OS](https://www.qubes-os.org/).
- Android用戶可以通過[F-Droid](https://f-droid.org)下載軟件，[F-Droid](https://f-droid.org)是一個開源的注重安全的應用軟件市場。
- 對於美國居民，凍結你的信用信息，防止黑客獲取敏感數據。閱讀更多信息： Security Checklist's [Freeze Your Credit](https://securitycheckli.st/)。

---

## 🧠 資訊來源

我們咨詢了許多專家，並總結了自己的經驗來建立這份清單。如果你還是沒有獲得你希望獲得信息，我們建議你閱讀以下這些文章：

- [The Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/)
- [Citizen Lab's Security Planner](https://securityplanner.org/)

你可以閱讀 Martin Shelton整理的指南： [Current Digital Security Resources](https://medium.com/@mshelton/current-digital-security-resources-5c88ba40ce5c)。

---

## 📝 授權

本著作係採用[創用 CC 姓名標示-非商業性-相同方式分享 4.0 國際 授權條款](https://creativecommons.org/licenses/by-nc-sa/4.0/)授權.
