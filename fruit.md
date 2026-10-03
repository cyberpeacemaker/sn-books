你的記憶非常準確！你提到的新聞是川普簽署的《擴大對抗跨國網路犯罪能力》國家安全總統備忘錄（NSPM），這項政策被外媒稱為允許民間「網路私掠（Cyber Privateers）」的重大轉折。

* **政策核心概念**：打破過去僅限美軍（網路司令部）或情報單位（FBI/NSA）才能執行攻擊性網路行動的慣例，建立聯邦計畫讓經嚴格審查的**民間資安公司**也能參與反擊行動。
* **允許的反制行為**：獲准公司可以在政府監督下執行「網路監控」與「網路影響行動（Cyber Effects Operations）」，包含主動入侵海外駭客的網路系統、監控情報，甚至干擾、降級或毀損惡意伺服器與基礎設施。
* **打擊目標**：主要針對海外的「跨國網路犯罪組織（CE-TCOs）」，例如勒索軟體集團、網路詐騙集團及商業郵件詐欺者，藉此釋放政府機關的能量去應付國家級威脅。
* **嚴格的監管與限制**：這**並非**給予企業無限制任意「私自反駭（Hack-back）」的自由。公司必須與司法部（DOJ）或國土安全部（DHS）簽約，並在國家協調中心（NCC）的監督下執行任務；若行動無意中波及美國本土設施或公民，必須立刻中止並通報。

如果你的印象來自更早期，川普在第一任期（2018 年）也曾簽署過著名的 **NSPM-13** 備忘錄，當時是鬆綁美軍網路司令部（US Cyber Command）發動海外攻勢網路行動的審批流程，免去了繁瑣的跨部會審核。而最新的這份備忘錄，則是進一步把這種主動反制的能力與權限延伸到了民間企業。

---

https://www.whitehouse.gov/presidential-actions/2026/08/expanding-capabilities-to-combat-transnational-cyber-enabled-crime/

---

# GTI

- https://www.virustotal.com/gui/collection/report--26-10055084

##
GTIG assesses with high confidence that People's Republic of China (PRC)-based operator named Hou Wenhui provisions and manages core command and control (C2) infrastructure for threat actor group BASIN CASTLE (previously reported as TEMP.Hex; overlapping with public reporting on Mustang Panda).
By tracing historical C2 infrastructure documented in open source reporting , GTIG mapped legacy SOGU (PlugX) and Poison Ivy campaign infrastructure directly to the individual Hou Wenhui's personal contact details, self-signed certificates, and known developer aliases.
Hou Wenhui operates via his established corporate front companies in Sanmenxia City (Henan Province) and Beijing; specifically Henan Suerte Network Technology Co., Ltd. (河南斯尔特网络科技有限公司) and Henan Baolan Network Technology Co., Ltd. (河南宝蓝网络科技有限公司).
Historical developer forum publications authored by Hou Wenhui detail low-level Windows mechanics, including API hooking, kernel driver development, and anti-debugging techniques, demonstrating foundational technical expertise in defense evasion mechanisms utilized in SOGU malware.

---

"https://thehackernews.com/2026/08/trump-memo-paves-way-for-us-firms-to.html" 你覺得如何

---

這篇文章報導了一項非常具有突破性且充滿爭議的美國網路安全政策轉變。根據該篇來自《The Hacker News》（2026年8月14日）的報導，美國總統川普簽署了一份備忘錄，指示國家協調中心（NCC）建立一項計畫，**允許經過審查的美國私人企業對外國跨國犯罪組織（TCOs）進行「合法駭入」與破壞行動（即俗稱的 Hack Back 或主動網路防禦）。**

針對這項政策，我認為可以從以下幾個層面來分析它的影響與潛在風險：

### 1. 政策的核心意義：打破傳統防禦思維

過去，私人企業在網路安全上只能採取「被動防禦」（如架設防火牆、修補漏洞），即便是遭到勒索軟體或網路詐騙攻擊，也只能依靠政府執法機關（如 FBI）來進行跨國追查。
這項新政策允許私人企業利用其技術能力進行：

* **網路監視行動 (Cyber surveillance operations)**：未經授權即可存取駭客的敏感數據。
* **網路效應行動 (Cyber effects operations)**：直接中斷、癱瘓或摧毀駭客的基礎設施與網路。

這代表美國政府承認，面對每年高達 208 億美元的網路犯罪損失（如勒索軟體、殺豬盤、網路釣魚等），傳統的國家執法速度已經難以跟上，因此決定「外包」部分反擊權力給民間的技術高手與資安公司。

### 2. 潛在優勢 (Pros)

* **反應速度更快**：私人資安企業通常處於對抗網路攻擊的第一線，賦予他們反擊權，可以更及時地切斷犯罪組織的伺服器或中斷其金流。
* **緩解政府資源壓力**：跨國網路犯罪案件數量龐大，將反制行動擴展至民間，能大幅提升美國整體打擊網路犯罪的量能。

### 3. 巨大的法律與安全風險 (Cons & Risks)

正如報導末段專家所指出的，這項政策伴隨著極高的風險，這也是過去各國政府一直不敢開放「私人駭客反擊」的原因：

* **誤擊與連帶損害 (Collateral Damage)**：駭客經常使用跳板（例如入侵無辜第三國的醫院或一般企業伺服器來發動攻擊）。如果美國私人企業為了摧毀駭客網路，不小心癱瘓了其他國家的合法基礎設施，將引發嚴重的國際糾紛與法律問題。
* **歸因困難與地緣政治衝突**：備忘錄規定目標必須是「非外國政府直接控制」的犯罪集團。但在實務上，很難在第一時間分辨一個駭客組織是純粹的犯罪份子，還是受到敵對國家（如俄羅斯、北韓、伊朗）暗中支持的國家級駭客（APT）。如果私人企業不慎攻擊了外國國家資產，可能會引發國家級的網路報復，甚至升級為外交或軍事衝突。
* **監管難度極高**：雖然備忘錄要求企業如果在行動中牽涉到美國公民或美國境內的設備就必須立即停止，但網路世界的邊界非常模糊。NCC 與司法部（DOJ）是否有足夠的能力去即時監管這些獲得「合法授權」的企業不濫用權力，將是一大挑戰。

**總結來說：**
這是一步「險棋」。它確實能為飽受網路犯罪困擾的美國企業提供一種強而有力的反擊武器，但也徹底模糊了「國家軍事/情報行動」與「私人企業商業行為」之間的界線。這項計畫在未來 60 天內如何制定嚴格的審查機制與交戰守則（Rules of Engagement），將會是全球資安界與國際法學界高度關注的焦點。