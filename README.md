---
title: Reverse interview
tags: Interview
author: Kimi Tsai <kimi0230@gmail.com>
description: https://github.com/viraptor/reverse-interview
---
# Reverse interview

> - 原文:[viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)
> - 原文作者:[Stanisław Pitucha(viraptor)](https://github.com/viraptor)
> - 翻譯:[kimi0230](https://github.com/kimi0230)

下面列表裡的問題對於參加技術面試的人來說可能有些用.
列表裡的問題並不一定適用於某個特定的職位或者工作類型, 也沒有排序.
最開始的時候這只是我自己的問題列表,
但是慢慢添加一些我想知道更多的問題和我可能對這家公司產生疑慮的問題.
我也注意到被我面試的人提問我的問題太少了, 感覺他們挺浪費機會的.

如果你問過的問題沒有被列出來, 請提交一個 PR.

This is a list of questions which may be interesting to a tech job applicant.
The points are not ordered and many may not apply to a given position, or work type. 
It was started as my personal list of questions,
which grew over time to include both things I'd like to see more of and red flags which I'd like to avoid.
I've also noticed how few questions were asked by people I interviewed and I think those were missed opportunities.

If you asked something not listed here, send in a PR.

Translations:
- [Arabic](https://github.com/viraptor/reverse-interview/blob/master/translations/ARABIC.md)
- [Catalan](https://github.com/viraptor/reverse-interview/blob/master/translations/CATALAN.md)
- Chinese [Simplified](https://github.com/yifeikong/reverse-interview-zh) / [Traditional](https://github.com/NeroCube/reverse-interview-zh-tw/blob/master/README.md)
- [English](https://github.com/viraptor/reverse-interview/blob/master/README.md)
- [French](https://github.com/viraptor/reverse-interview/blob/master/translations/FRENCH.md)
- [German](https://github.com/viraptor/reverse-interview/blob/master/translations/GERMAN.md)
- [Hindi](https://github.com/hraverkar/reverse-interview/blob/master/translations/Hindi.md)
- [Indonesian](https://github.com/viraptor/reverse-interview/blob/master/translations/INDONESIAN.md)
- [Italian](https://github.com/viraptor/reverse-interview/blob/master/translations/ITALIAN.md)
- [Korean](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/blob/master/Reverse_Interview/README.md)
- [Portuguese (Brazilian)](https://github.com/viraptor/reverse-interview/blob/master/translations/pt-BR.md)
- [Russian](https://github.com/kix/reverse-interview/blob/master/README.md)
- [Spanish](https://github.com/felHR85/Entrevista-inversa/blob/master/README.md)
- [Turkish](https://github.com/viraptor/reverse-interview/blob/master/translations/TURKISH.md)
- [Vietnamese](https://github.com/tuannh99/reverse-interview/blob/master/README.md)

---

## Expected usage (預期使用方式)
* 挑出下列問題你是否感興趣
* 查出下列答案哪些是你可以自己上網找到
* 都找不到的話就問問面試官

絕對不要把這個列表裡的每個問題都問過, 請尊重面試官的時間, 你可以主動找已被發布的答案, 來顯示你的積極性

請記住事情總是靈活的, 組織的結構調整也會經常發生.
擁有一個 bug 追蹤系統並不會保證可高效處理 bug.
CI/CD (持續集成系統) 也不一定保證交付時間會很短.

- Check which questions are interesting for you specifically
- Check which answers you can find yourself online
- Otherwise ask

Definitely don't try to ask everything from the list. 
(Respect the interviewer's time and show initiative by finding answers on your own if they're already published)

Remember that things tend to be fluid, re-organizations happens often.
Having a bug tracking system doesn't make bug handling efficient and CI/CD doesn't mean your time to deliver is necessarily short.

---
# The Role (職責)

1. 有無 on-call 的計畫或規定?(有無值班和加班的費用)
2. 我一天的工作任務是什麼? 
3. 有給我設定特別的目標嗎?
4. 團隊裡資深跟資淺的工程師比例是多少? (未來有計劃改變嗎?)
5. 入職訓練是什麼?
6. 獨自開發和按部就班工作的比例大概是怎樣?
7. 每天預期/核心工作時間是多少小時?
8. 你覺得在此職位怎樣算是成功?
9. 你預期在前 1 ~ 3 個月需要我完成什麼目標?
10. 你如何評估試用期的表現?
11. 我怎麼知道這職位一天一週的任務?
12. 是否還有什麼問題要問我?
13. 在工作上我會跟哪些人比較密集的合作
14. 我的主管和更上級的主管是什麼樣的管理風格?(事無鉅細 or 著眼宏觀)
15. 我在這個職位該如何發展, 會有什麼機會?

##### 原文
1. What's the on-call plan/schedule? (what's the pay for standby and call-out)
2. What are the tasks I would do on a usual day?
3. Are there any specific goals for me?
4. What's the junior/senior balance of the team? (and are there plans to change it)
5. What does the onboarding look like?
6. How much freedom for decision making do individual developers have?
7. What are the expected/core work hours?
8. What is your definition of success for this role?
9. What do you expect me to accomplish in the first 1 month/3 months?
10. How will you evaluate my performance at the end of the trial period?
11. What does a typical day/week look like in this role?
12. Do you have any concerns about my application?
13. Tell me about who I would be working most closely with.
14. What management style does my immediate manager and their manager have? (from micro- to macro-)
15. How can I develop in my new role / what opportunities are offered?

---
# Tech (技術)
1. 公司常用哪些技術棧?
2. 你們怎麼使用版控?
3. 你們怎麼測試的?
4. 你們怎麼追蹤bug?
5. 你們怎麼監控專案?
6. 你們怎麼整合和部署改動的程式碼?是使用 CI/CD 部署嗎?
7. 你們的基礎設施設置是否受版本控制/可作為代碼使用？
8. 你們從計劃到完成一個任務的工作流程是怎樣?
9. 你們如何準備故障修復?
10. 有標準的開發環境嗎?是強制的嗎?
11. 你們建置一個本地的開發環境需要多久?
12. 你們需要花多長久來解決安全問題與相依性問題?
13. 所有的開發者都可以使用他們電腦的本機admin權限?
14. 可以介紹一下你們的技術原則或展望嗎?
15. 你們有程式開發的文件嗎?有沒有單純給消費者使用的文件?
16. 你們有沒有更高層的開發文件, 譬如 ER diagrams (entity relationship diagra, 實體聯絡模型), DB schema
17. 你們有使用靜態代碼分析嗎?
18. 你們如何管理內部和外部的資產?
19. 你們如何管理依賴?

##### 原文
1. What are the usual stacks used at the company?
2. How do you use source control?
3. How do you test code?
4. How do you track bugs?
5. How do you monitor projects?
6. How do you integrate and deploy changes? Is it CI/CD?
7. Is your infrastructure setup under version control / available as code?
8. What's the workflow from the planning to the finished task?
9. How do you prepare for disaster recovery?
10. Is there a standardised development environment? Is it enforced?
11. How quickly can you setup a new local test environment for the product? (minutes / hours / days)
12. How quickly can you respond to security issues in the code or dependencies?
13. Are all developers allowed to have local admin access of their computers?
14. Tell me about your technical principles or vision.
15. Do you have a developer documentation for your code? Do you have a separate documentation for customers?
16. Do you have some higher level documentation? (ER diagrams, database schema)
17. Do you employ static code analysis?
18. How do you manage internal / external artifacts?
19. How do you manage dependencies?

---
# The Team (團隊)
1. 工作是怎麼組織的?
2. 團隊內/團隊間的交流通常是怎樣
3. 你們有使用什麼工具來組織project嗎? 你實際上有什麼體驗?
4. 如果遇到不同意見的話是怎麼處理的?
5. 是誰來決定優先順序/時程?
6. 如果被退回了會怎樣?("這個在預計的時間內做不完")
7. 如果團隊錯過發布目標時怎麼辦?
8. 每週都會開什麼類型會議?
9. 會有定期和主管一對一對談嗎?
10. 產品/服務的規劃是什麼樣的?(n週一發布 / 持續部署 / 多個發布流 / ...)
11. production環境發生問題了怎麼辦? 是否有不批評人而分析問題的文化?
12. 有沒有一些團隊正在遇到尚待解決的挑戰?
13. 你們如何追蹤進度
14. 預期和目標是如何設定的? 由誰決定?
15. 你們如何實施Code review的?
16. 可以介紹一下團隊裡如何執行一個典型的sprint嗎?
17. 你們如和平衡技術和商業目標?
18. 你們如何共享知識,資訊?
19. 這團隊有多大?

##### 原文
1. How is the work organised?
2. How does the intra/inter-team communication typically work?
3. Do you use any tools for project organization? What is your experience with them?
4. How are differences of opinions resolved?
5. Who sets the priorities / schedule?
6. What happens after pushback? ("this can't be done in the projected time")
7. What happens when the team misses a release target?
8. What kind of meetings happen every week?
9. Would there be a regular 1-on-1 with my manager?
10. What's the product/service schedule? (n-weekly releases / continuous deployment / multiple release 1.treams / ...)
11. What happens after production incidents? Is there a culture of blameless analysis?
12. What are some ongoing challenges the team is experiencing that you are yet to resolve?
13. How do you track progress?
14. How are expectations and goals set, and who does the setting?
15. What does a code review look like here?
16. Walk me through a typical sprint on this team
17. How do you balance technical vs business goals?
18. How do you share knowledge?
19. How big are the teams?

---
# Your Potential Coworkers (未來的同事)
1. 開發者頃向於向誰學習?
2. 你最喜歡這裡的什麼地方?
3. 你最不滿意這裡的什麼的地方?
4. 如果可以你想改變什麼地方?
5. 團隊最老的成員待多久?
6. 如果在小團隊, 出現團員個性互相衝突的情況, 你們是如何解決的?

##### 原文
1. Who do developers tend to learn from?
2. What do you like best about working there?
3. What do you like least?
4. What would you change if you could?
5. How long has the longest team member been there?
6. If it's a small team, has there been experiences of conflicting personalities and how was this dealt with?

---
# The Company (公司)
1. 為什麼公司在徵此職缺? (產品發展 / 新產品 / 波動 / ...)
2. 有沒有會議/出差預算,跟使用規則?
3. 晉升的流程,要求,預期怎樣勾通?
4. 績效評估的流程是什麼?
5. 技術和管理的職業路徑是分開的嗎?
6. 公司是否有公司級別的學習資源, 譬如電子書訂閱, 線上課程等?
7. 公司是否有預算提供證照考取?
8. 公司目前的成熟度如何(早期尋找方向 / 有內容的工作 / 維護中 / ...)
9. 我是否可以為開源項目做貢獻?需要經過批准嗎?
10. 有競業條款或保密協議嗎?
11. 你覺得公司未來5/10年會變成怎樣?
12. 你覺得clean code 對這裡大部分的開發人員來說代表什麼?
13. 你上一次注意到有人成長是什麼時候, 在哪方面成長了?
14. 在這裡你覺得怎樣是成功, 如何衡量成功?
15. 這裡有運動或者是團體活動嗎?
16. 有內部的駭客松活動嗎?
17. 公司支援開源項目嗎?
18. 團隊/公司舉辦什麼樣的社交活動,每個人都參加嗎?
19. 為什麼公司決定聘請外部人員而不是提拔內部員工？
##### 原文
1. Why is the company hiring? (product growth / new product / fluctuation / ...)
2. Is there a conference/travel budget and what are the rules to use it?
3. What's the promotion process? How are requirements / expectations communicated?
4. What is the performance review process like?
5. Is there a separate tech and management career path?
6. Are there any company-wide resources for learning available, like ebooks subscriptions, or online courses?
7. Is there a budget for getting certifications?
8. What's the maturity stage? (early finding direction / feature work / maintenance / ...)
9. Can I contribute to FOSS projects? Are there any approvals needed?
10. Are there any non-compete or non-disclosure agreements I'll be asked to sign?
11. Where do you see the company in the next 5/10 years? 
12. What does clean code mean to the majority of developers here?
13. When is the last time you noticed someone growing here, and in what way were they growing?
14. What does it mean to be successful here, and how do you measure success?
15. Is there a Sports / Team building Activity?
16. Are there any Hackathons conducted internally?
17. Does the company support open-source projects?
18. What kind of social events does the team/company host and are these attended by everyone?
19. Why did the company decide to hire an outsider over promoting an internal employee?

---
# Social issues (社交問題)
1. 你們對多元化招聘的看法?
2. 您認為公司文化的差距在哪裡?(什麼是公司文化?)
3. 你認為這裡的工作跟生活的平和如何?
4. 公司對氣候的變化持有什麼態度?
##### 原文
1. What's the status of / view on diverse hiring?
2. What do you think are the gaps in the company culture? (and what is the company culture?)
3. What does work-life balance mean here?
4. Does the company have a stance regarding climate change?

---

# Conflict (衝突)
1. 發生意見分歧如何解決?
2. 如果被退回了會怎樣?("這個在預計的時間內做不完") 同[the-team-團隊no.6](#the-team-團隊)
3. 當團隊面臨壓力且工作量超負荷時, 怎麼處理？
4. 如果有人指出流程/技術/等方面需要改進的地方,怎麼處理?
5. 當管理成預期和工程師的績效之間有差去的時候如何處理?
6. 可以說說公司如何處理有毒環境?
##### 原文
1. How are differences of opinions resolved?
2. What happens after pushback? ("this can't be done in the projected time")
3. What happens when the team is under pressure and commits to work over their capacity / velocity?
4. If someone identifies areas of improvement in process / technology / etc, what happens?
5. When there is a gap between expectations from management and performance of an engineer or team, what happens?
6. Could you tell me a story about a toxic situation and how the company dealt with it?

---
# The Business (商業)
1. 請問公司是否有盈利?
2. 如果沒有的話, 還需要多久?
3. 公司的資金來源是什麼? 誰影響或制定了最高的決定跟方向?
4. 你們如何獲利的?
5. 什麼東西阻礙了獲利?
6. 公司未來一年/五年的增長計劃是什麼?
7. 你認為目前遇到最大的挑戰是什麼?
8. 你認為你們的競爭優勢是什麼?
   
##### 原文
1. Are you profitable?
2. If not, how long is your runway?
3. Where does the funding come from and who influences the high level plan/direction?
4. How do you make money?
5. What's preventing you from making more money?
6. What is the company's growth plan for the next 1 year? 5 years?
7. What are the big challenges you see coming up?
8. What have you identified as your competitive advantage?

---
# Remote Work (遠端工作)
1. 遠端工作和辦公室工作的比例是多少?
2. 公司提供電腦等硬體設備嗎? 是否有換新計劃?
3. 你如何看待自備電腦設備 [BYOD](https://en.wikipedia.org/wiki/Bring_your_own_device)?是否已經有相關政策?
4. 額外的附件和家具可以通過公司購買嗎?這方面是否有預算?
5. 有共享辦公室或者上網的預算嗎?
6. 多久需要去辦公室?
7. 公司會議室是否都配備視訊裝置?
##### 原文
1. What's the ratio of remote to office workers?
2. Does the company provide hardware and what's the refresh schedule?
3. How do you feel about [BYOD](https://en.wikipedia.org/wiki/Bring_your_own_device)? Are there any policies around it already?
4. Are extra accessories/furniture possible to buy through the company? Is there a budget for them?
5. Is there a budget for co-working space or internet access?
6. How often are office visits expected?
7. Are the office meeting rooms always prepared for video conferences?

---
# Building Layout (辦公室佈局)
1. 辦公室的佈局如何?(開放式 / 小隔間 / 獨立辦公室)
2. 是否有支援/ 市場/ 或者其他會有大量電話打入的團隊在我們團隊附近?
##### 原文
1. What's the office layout? (open plan / cubicles / offices)
2. Is there a support / marketing / other call-heavy team close to my new team?

---
# Catch all (終極問題)
1. 在這個職缺/團隊/公司工作的最好和最壞的方面是什麼?
2. 你一開始為什麼會選擇這家公司?
3. 你為什麼會留在這家公司?
##### 原文
1. What's the best and what's the worst aspect of working in this role / team / company?
2. What got you to choose to work for the company initially?
3. What keeps you at the company?

---

# Compensation (待遇)
1. 公司是否獎金計劃, 獎金是如何分配的?
2. 過去幾年這裡通常發百分之幾的獎金?
3. 有 401k(us)或者其他退休養老金等福利嗎? 如果有, 公司是否有配套的商業保險嗎?
4. 有醫療福利嗎?如果有,什麼時候開始?
5. 更換工作地點,公司有提供費用嗎?
##### 原文
1. If you have a bonus scheme, then how are bonuses determined?
2. If you have a bonus scheme, then what have been the typical bonus percentages over the past few years?
3. Do you have a 401k or other retirement plan? If so, does the company match additional plan contributions?
4. Are there medical benefits and if so, when do they start?
5. Do you pay for relocation?

---
# Time Off (休假)
1. 帶薪的休假有幾天?
2. 病假跟事假是分開還是一起算?
3. 我可以預支帶薪的休假嗎?
4. 帶薪的休假何時刷新?
5. 有什麼育兒的政策嗎?
6. 無薪休假政策是什麼樣的?
7. 年假的政策是什麼?
##### 原文
1. How much Paid Time Off (PTO) is offered?
2. Are sick time and vacation time separate or do they come from the same pool?
3. Can I use vacation time before it's accrued, effectively going into a negative PTO balance?
4. What is the roll over policy is there for PTO?
5. What is the parental leave policy?
6. What is the policy on unpaid leave?
7. What is the policy for sabbatical leave?

---
# Other resources (其他資源)

Find more inspiration for questions in:

  - [The Joel Test: 12 Steps to Better Code](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/) by Joel Spolsky
  - [Questions I'm asking in interviews](https://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/) by Julia Evans

---
## Reference
* https://github.com/viraptor/reverse-interview