<p align="center">
    <img src=".//img/logo.png">
</p>

![image](https://img.shields.io/github/stars/No-Github/Dork-Admin.svg?label=Stars&style=popout) ![GitHub last commit](https://img.shields.io/github/last-commit/No-Github/Dork-Admin.svg?style=popout)

---

# Manual🦄

盘点近年来的各国各行较知名的数据泄露、供应链污染事件

灵感来源: https://haveibeenpwned.com/PwnedWebsites、https://www.freebuf.com/articles/paper/147403.html

消息源: [verizon DBIR](https://enterprise.verizon.com/resources/reports/dbir/)、[haveibeenpwned](https://haveibeenpwned.com)、[securityaffairs](https://securityaffairs.co/wordpress/tag/data-leak)、[hackernews](http://hackernews.cc/archives/category/%E6%95%B0%E6%8D%AE%E6%B3%84%E9%9C%B2)、[Freebuf](https://www.freebuf.com)、[bleepingcomputer](https://www.bleepingcomputer.com)、[zdnet](https://www.zdnet.com)、[Solidot](https://www.solidot.org)、[Rainbowtabl.es](https://rainbowtabl.es/)

<p align="center">
    <img src=".//img/readme.jpg">
</p>

# 数据泄露
## 2019🤦‍

**6月**
- **中国猎头公司 FMC Consulting** 配置错误的ElasticSearch集群造成数据泄露(据文章称涉事公司收到报告毫无反应，直到CNCERT出面才下线数据)

    泄露内容：数百万份简历和公司记录，以及客户和员工的PII数据。

    事件经过：FMC Consulting（一家中国猎头公司）拥有一个配置错误且可公开访问的ElasticSearch集群，泄露了数百万份简历和公司记录，以及客户和员工的PII数据。
     包含数十万条客户记录，内部电子邮件以及员工日常任务的数据库以及他们在联系客户时所做的调用都没有受到保护，将所有数据暴露给知道在哪里以及如何查找它的人。
     根据该公司的LinkedIn简介，“FMC成功地帮助我们的客户在中国充满活力的市场中放置了10,000多个竞争职位（截至2018年底）。这些职位包括专业职位，中层管理职位和区域业务负责人。“
     作为GDI基金会成员和独立安全研究员的Sanyam Jain发现了错误配置的ElasticSearch集群，并联系了BleepingComputer以取消数据库。

    link: https://www.bleepingcomputer.com/news/security/headhunting-firm-leaks-millions-of-resumes-client-private-data/

- **PayID** 遭网络攻击 十万客户信息泄露

    影响人数：10万

    泄露内容：不详

    事件经过：西太平洋银行（Westpac）的实时支付平台PayID系统遭网络攻击，近10万客户的私人信息泄露。这次袭击行为还会影响到其它银行的客户。计算机安全专家警告，这些被窃取的私人信息可能会被用于欺诈。根据悉尼晨锋报获得的一份机密备忘录，西太平洋银行向澳洲银行业和金融业披露了有关这次网攻事件的信息。其中说：“2019年5月22日，西太平洋银行注意到，澳洲支付平台PayID（NPPA PayID）的大量查询（约60万个）来自七个被泄露的西太平洋银行有效账户，约9.8万个查询成功解析了一个短名字，并暴露给了欺诈者。”

    link: https://www.smh.com.au/business/banking-and-finance/australians-private-details-exposed-in-attack-on-westpac-s-payid-20190603-p51u2u.html

- **格雷斯兰大学** 未经授权的用户访问当前员工的电子邮件帐户

    泄露内容：全名、社會安全號碼、出生日期、位址、電話號碼、電子郵件地址、父母/兒童、工資資訊、格雷斯蘭的註冊或可能註冊的財政援助資訊

    事件经过：在6月14日发布的数据泄露通知中称，Graceland 已經意識到三個實例,即未經授權的使用者訪問當前員工的電子郵件帳戶,包括與這些帳戶相關的內容和附件。未經授權的使用者分別于 2019 年 3 月 29 日以及 2019 年 4 月 1 日至 30 日和 2019 年 5 月 12 日至 5 月 1 日訪問這些個人帳戶。這些帳戶現已得到保護,但是,已經確定,在過去幾年中與這些電子郵件帳戶交互的一些人的個人資訊在未經授權的使用者訪問期間可用。格雷斯蘭曾試圖使用檔案上的位址向這些人發送一封物理信件。

    link: https://www.graceland.edu/notice-of-data-breach

    link: https://www.bleepingcomputer.com/news/security/three-us-universities-disclose-data-breaches-over-two-day-span/

- **俄勒冈州立大学 (OSU)** 資料隱私事件

    事件经过：俄勒岡州立大學週五宣佈,5月初發生的資料隱私事件可能影響到636份包含個人識別資訊的學生記錄和家庭記錄。

    一名 OSU 員工的電子郵件帳戶被大學外的個人入侵,用於向全國發送網路釣魚電子郵件。OSU 和法醫專家進行的一項調查發現,在 OSU 員工電子郵件帳戶的收件匣中發現了幾份檔,這些檔包含 636 名學生和學生家庭成員的個人資訊。

    "OSU正在繼續調查此事,並確定網路攻擊者是否用個人資訊查看或複製這些檔,"該大學負責大學關係和行銷的副校長史蒂夫·克拉克(Steve Clark)說。"雖然我們目前沒有跡象表明個人資訊已被查看或使用,但 OSU 已將這一事件通知了這些學生和家庭成員。我們還提供了有關現有支援服務的資訊,包括該大學將免費提供的 12 個月信用監控服務。

    克拉克說,OSU正在審查許多保護程式和IT系統,該大學使用來保護其資訊系統,電子郵件帳戶,學生和家庭記錄。他說:"我們將繼續監控此類工作和系統,並採取進一步措施保護大學的資訊技術和敏感性資料。

    link: https://today.oregonstate.edu/news/oregon-state-university-reports-it-security-incident

- **密蘇里州南部州立大學(MSSU)** 造網路釣魚攻擊，資料洩露

    泄露内容：名字和姓氏，出生日期，家庭住址，电子邮件地址，电话号码和社会安全号码

    事件经过：它在发送给佛蒙特州司法部长办公室的数据泄露通知中表示，它已被警告1月9日网络钓鱼邮件可能引发网络攻击。

    网络钓鱼攻击使该大学的员工中有几名受害者提出了执法通知。事后，大学官员被告知要延迟通知受影响的个人，直到调查完成为止。

    MSSU还聘请了一家领先的法证调查公司来调查安全事件并“阻止潜在的电子邮件利用，包括重置所有员工Office 365帐户的密码”。

    在分析受影响的Office 365帐户的内容后，MSSU发现电子邮件包含在存储的“名字和姓氏，出生日期，家庭住址，电子邮件地址，电话号码和社会安全号码”中。

    link: https://www.documentcloud.org/documents/6153866-Missouri-Southern-State-University-Notice-of.html

- **芝加哥大學** 超過150萬捐贈者的私人資訊暴露

    影响人数：150万

    泄露内容：全名、出生日期、完整地址、电话号码、电子邮件、性别、婚姻状况、财富信息和当前状态、通讯说明

    事件经过：超過160萬潛在和現有的芝加哥大學醫學捐贈者的個人資訊被一個配置錯誤和未受保護的彈性搜尋伺服器暴露在互聯網上沒有密碼。

    5月28日,安全發現研究員鮑勃·迪亞琴科(Bob Diachenko)發現了這個可公開訪問的ElasticSearch實例,一天前,連接互聯網的設備搜尋引擎Shodan將其添加到其公開伺服器索引中。

    在仔細查看公開的資料後,Diachenko 瞭解到,名為"data-ucmbsd2"的 34GB 大小彈性搜索群集包含 1,679,993 條記錄,任何知道在哪裡以及如何查找它的人都可以訪問這些記錄。

    link: https://www.bleepingcomputer.com/news/security/private-info-of-over-15m-donors-exposed-by-uchicago-medicine/


- **复古遊戲網站 Emuparadise** 遭受 110 萬帳戶的資料洩露

    影响人数：110萬

    泄露内容：电子邮件地址，IP地址，用户名和密码

    事件经过：“在2018年4月，自称”地球上最大的复古游戏网站“，Emupardise遭遇了日期违规。受损的vBulletin论坛公开了110万个电子邮件地址，IP地址，用户名和密码存储为盐渍MD5哈希。数据提供通过dehashed.com到HIBP。“

    link: https://www.bleepingcomputer.com/news/security/gaming-site-emuparadise-suffered-data-breach-of-11m-accounts/

- **AMCA** 数据泄露1900万客户受影响

    影响人数：1900万

    泄露内容：银行账户数据和信用卡号，社会安全号码

    事件经过：正如美国证券交易委员会诊断的SEC通知中所述，AMCA告知该公司“2019年8月1日至2019年3月30日期间，未经授权的用户可以访问AMCA的系统，该系统包含AMCA从各种实体收到的信息，包括Quest Diagnostics，以及AMCA收集的信息。““截至2019年5月31日，AMCA认为，其信息包含在AMCA受影响系统中的Quest Diagnostics患者人数约为1190万人，” 美国证券交易委员会的通知也表示。

    Quest Diagnostics表示，它无法确认从AMCA收到的信息的准确性，并且没有实验室测试结果受到安全事件的影响，因为它们没有提供给AMCA。

    诊断信息服务提供商补充说，它“非常重视此事，致力于保护患者的个人，医疗和财务信息的隐私和安全。”

    AMCA告诉Quest Diagnostics他们“已就此事件与执法部门联系”，但尚未提供有关违规行为的“详细或完整信息”。

    link: https://www.bleepingcomputer.com/news/security/billing-details-for-119m-quest-diagnostics-clients-exposed/

    link: https://www.bleepingcomputer.com/news/security/quest-labcorp-amca-sued-for-breach-impacting-over-19-million/

    link: https://www.bleepingcomputer.com/news/security/over-400-000-opko-health-clients-impacted-by-amca-data-breach/

**5月**
- **上海交大** 泄漏 8.4TB 邮件元数据 (你知道shodan搜这种未授权访问的业务有多容易吗？我来告诉你)[点击看看](https://www.shodan.io/search?query=port%3A%229200%22+all%3A%22elastic+indices%22)

    泄露内容：8.4 TB 电子邮件元数据、发送电子邮件的人的IP地址和用户代理，设备类型等

    事件经过：安全研究员通过搜索 Shodan，发现了一个没有任何身份验证的 ElasticSearch 数据库。该数据库属于上海交大，包含了 8.4TB 邮件元数据，但不包含邮件正文内容。数据库包含了 95 亿行数据，5 月 23 日数据库容量只有 7TB，24 日就增加到了 8.4 TB。交大安全团队在收到报告之后就在当天关闭了开放访问。元数据包括了发送方，接收方，IP 地址、检查邮件时的用户代理，以及设备类型等。

    link: https://rainbowtabl.es/2019/06/09/shanghai-jiao-tong-university-email-metadata-leak/

    link: https://www.solidot.org/story?sid=60937


- **三星** 多个项目代码泄露 包括SmartThings源代码和密钥

    泄露内容：多个内部项目，包括三星SmartThings敏感的源代码、证书和密钥。

    事件经过：三星数十个自主编码项目出现在旗下Vandev Lab的GitLab实例中。该实例被三星员工用于分享并贡献各种应用、服务和项目的代码。由于这些项目被设置为“公开”，同时没有受到密码的保护，因此任何人都可以查看项目，获取并下载源代码。迪拜信息安全公司SpiderSilk的安全研究员莫撒布·胡赛因（Mossab Hussein）发现了这些泄露的文件。他表示，某个项目包含的证书允许访问正在使用的整个AWS帐号，包括100多个S3存储单元，其中保存了日志和分析数据。

    link: http://hackernews.cc/archives/25425

- **Ladders** Database Exposed 13M User Records

    影响人数：1300万

    泄露目标：Ladders User

    link: https://securityaffairs.co/wordpress/84861/data-breach/ladders-data-leak.html

- **Instagram** 4900万条数据曝光，影响人数达数百万

    影响人数：4900万条记录

    泄露目标：Instagram用户

    泄露内容：用户资料、图片、粉丝数据、以及验证过的国家/地区、私人联系信息（包括电话、电子邮件等），甚至还有用户已删除信息内容。

    事件经过: 据TechCrunch网站报道，Instagram的一个大型数据库由于在AWS存储桶上没有受到保护，导致任何人都可以在没有身份验证的情况下访问它。该数据库首先由安全研究人员Anurag Sen发现，并立即报告给了TechCrunch网站。

    link: https://securityaffairs.co/wordpress/85905/data-breach/instagram-data-leak.html

- **Hindustan** 大量员工和商业信息公开暴露

    泄露目标：Hindustan雇员、应聘者

    大致时间：2019年5月

    泄露内容：包括新雇员的个人信息和明文密码、客户基础设施安装报告以及管理人员的Web应用程序,应聘者的ID、姓名，手机号码、加入日期、加入地点、招聘人员SAP代码、招聘人员姓名、创建日期、用户名、明文密码、BGV状态、已接受的offer以及应聘申请表的链接。超过2,800名员工的名称和SAP代码,可以使用SAP代码和名称查找和’停用’员工”的界面,使用SmartManage报告系统管理的客户安装报告和项目数据,一份内部分析报告数据库，包含5700条事件记录、每周客户报告（约18,000个条目）以及可追溯到2016年的安装报告

    link:https://www.freebuf.com/news/204276.html

- **优衣库** 遭到黑客攻击，超过46万用户数据泄漏

    影响人数：46万用户

    泄露目标：用户

    大致时间：2019年5月

    泄露内容：个人信息、电子邮件、地址以及部分信用卡资料

    事件经过：日本最大的服装零售商迅销集团发布消息称，旗下优衣库以及GU品牌的在线商城遭到黑客攻击，约46万用户的数据泄漏，包括用户个人信息、电子邮件、地址以及部分信用卡资料等。迅销称，此事件仅限于日本网站，发生在4月23日至5月10日期间，是一次基于列表的攻击。当客户在多个网站上使用相同的用户名和密码组合时，可能会遭受此类攻击，建议用户更改密码。

    link: https://www.freebuf.com/news/203923.html

- **OGUsers** 论坛遭遇了数据泄露,被竞争对手脱裤

    影响人数：16万

    大致时间：2019年5月19日

    泄露内容：Email addresses, IP addresses, Passwords, Private messages, Usernames

    事件经过：In May 2019, the account hijacking and SIM swapping forum OGusers suffered a data breach. The breach exposed a database backup from December 2018 which was published on a rival hacking forum. There were 161k unique email addresses spread across 113k forum users and other tables in the database. The exposed data also included usernames, IP addresses, private messages and passwords stored as salted MD5 hashes.

    link: https://haveibeenpwned.com/PwnedWebsites#OGUsers

- **Canva** 1.39 亿用户数据泄露

    影响人数：1.39 亿

    泄露目标：Canva 用户

    泄露内容：用户名字、真名 、电邮地址、城市国家信息 、哈希密码、Google 令牌 、Gmail 地址

    事件经过：自称 GnosticPlayers 的黑客声称窃取了澳大利亚网站 Canva 的 1.39 亿用户数据。Canva 是一个非常受欢迎的平面设计服务，Alexa 排名在 200 以内。黑客窃取的数据包括了用户名字、真名 、电邮地址、城市国家信息，其中 6100 万用户有哈希密码，其他用户的信息还有用于登陆的 Google 令牌。有 7800 万用户使用了 Gmail 地址。Canva 证实它的数据库遭到非法访问，表示尚未发现账号被入侵，出于谨慎考虑它已经鼓励用户更改密码。

    link: https://www.zdnet.com/article/australian-tech-unicorn-canva-suffers-security-breach/

- **Ordine Avvocati di Roma** 遭到一个自称意大利匿名者的组织的数据泄露。

    影响人数：41,960

    泄露目标：罗马律师

    泄露内容：Email addresses, Email messages, Geographic locations, Passwords, Phone numbers

    事件经过：In May 2019, the Lawyers Order of Rome suffered a data breach by a group claiming to be Anonymous Italy. Data on tens of thousands of Roman lawyers was taken from the breached system and redistributed online. The data included contact information, email addresses and email messages themselves encompassing tens of thousands of unique email addresses. A total of 42k unique addresses appeared in the breach.

    link: https://haveibeenpwned.com/PwnedWebsites#OrdineAvvocatiDiRoma

- **Flipboard** 遭黑客攻击，用户名密码等信息泄露

    影响人数：未知

    泄露目标：Flipboard用户

    泄露内容：用户名、姓名、电子邮件地址和密码,Flipboard连接到第三方服务，例如Twitter和Facebook的数字令牌

    事件经过：本周，新闻聚合应用Flipboard就此前发生的信息泄露事件向用户发送电子邮件进行告知。在这次事件中，黑客获得了用户的用户名、电子邮件地址和受保护的密码。从2018年6月2日至2019年4月22日，Flipboard的数据库发生了“未经授权的访问”，导致用户的帐号信息泄露。Flipboard表示，黑客“有可能获得了”一些数据库的拷贝，但尚未透露有多少帐号被入侵等细节。

    link: https://tech.sina.com.cn/i/2019-05-30/doc-ihvhiqay2380994.shtml

- **Perceptics** 车牌识别公司遭黑客入侵，敏感数据被盗

    泄露内容：内部文件，文件名和附带目录总数量近65000，包括商业计划、财务数据和个人信息。数百GB，Microsoft Exchange和Access数据库、ERP数据库、HR记录、Microsoft SQL Server数据存储等

    事件经过：据外媒5月24日报道，Perceptics公司是一家提供车牌识别器、车牌识别系统和车辆识别产品的公司。该公司遭到黑客入侵，内部文件被窃取，文件名和附带目录总数量近65000，包括商业计划、财务数据和个人信息。被盗文件达数百GB，包括Microsoft Exchange和Access数据库、ERP数据库、HR记录、Microsoft SQL Server数据存储等。该公司业务涉及边境安全数据采集、商用车检查、电子收费和道路监控，因此拥有大量敏感数据。该公司表示已发现其网络遭到入侵，正在对事件进行调查。

    link: https://www.leiphone.com/news/201905/44M2ZJusnWhYY89Z.html

- **Pyramid Hotel Group** 85GB的安全日志暴露于公网

    泄露内容：安全审计日志

    事件经过：近日，研究人员发现了一个公开的数据库，内容包含了万豪在内的众多连锁酒店的安全日志，其中还包括潜在的安全漏洞。该团队于2019年5月27日发现故障服务器，经过检测发现该服务器连接了酒店和度假村管理公司Pyramid Hotel Group，该公司是美国、夏威夷、英国、爱尔兰等地包括万豪、喜来登、希尔顿等19个酒店及物业的管理方。故障服务器可通过9200端口关联到Elasticsearch数据库，并可不受限制的访问由开源入侵检测系统Wazuh生成的安全审计日志。该数据库的暴露直接公开了酒店的大量敏感数据，虽然数据库中每个记录都没有明确的名称，但Tarrytown House Estate、Carton House Luxury Hotel、Aloft Hltels、Temple Bar Hotel这些关键词都是可以直接识别的。据统计，暴露的安全审计日志内容一共达到了85.4GB。

    link: https://www.zdnet.com/article/unsecured-database-exposes-security-logs-of-major-hotel-chains/#ftag=RSSbaffb68

**4月**
- **Bilibili** 网站后台工程源代码被上传至[Github](https://github.com/openbilibili)(ikun大胜利?),官方回应:较老版本，已报案

    影响人数：1亿bog

    泄露目标：bilibili

    泄露内容：网站后台工程源代码

    大致时间：2019年4月22

    事件经过：大家好，我是练习时长两年半的灭霸，爱好是唱跳rap篮球music~

- **Docker Hub** 未经授权的访问者访问了Docker Hub的数据库，可能导致泄露19万用户敏感数据

    影响人数：19万

    泄露目标：Docker Hub用户

    大致时间：2019年4月

    事件经过：官方发送的安全通知，Docker于2019年4月25日发现有未经授权的访问者访问了Docker Hub的数据库。
    在进行调查之后，确定该数据库包含大约190000个用户的敏感信息。这些信息包括用于Docker自动编译的GitHub和Bitbucket存储库的访问令牌以及一小部分用户的用户名和密码哈希值。

- **京东** 疑似泄露5千万用户数据,官方回应:谣传

    影响人数：5000万

    泄露目标：京东用户

    大致时间：2019年4月

- **领英** 某AWS开放数据库泄露6000万条领英用户信息记录,官方回应:不是我们的数据库

    影响人数：6000万

    泄露目标：领英用户

    泄露内容：数据中包含领英个人资料信息，包括ID、个人资料网址、工作经历、教育经历、住址、技能、其他社交个人资料以及个人资料上次更新的时间。

    大致时间：2019年4月

    事件经过：近日，研究人员发现了八个不安全的数据库泄露了约6000万条领英用户信息记录。虽然大多数信息是公开的，但数据库中包含领英用户的电子邮件地址。

- **Facebook** 再被指泄漏用户数据，至少5.4亿用户资料任由下载(厉害了，又是你facebook)

    影响人数：至少5.4亿名用户

    泄露目标：Facebook 用户

    大致时间：2019年4月

    事件经过：据《彭博社》报导，网络保安公司 UpGuard 在亚马逊云端数据库上发现大量 Facebook 用户的个人资料，涉及至少5.4亿名用户，且数据开放予任何人下载。报导指出，墨西哥城媒体公司 Cultura Colectiva 的数据库储存了5.4亿名 Facebook 用户的个人资料，包括身份证号码、帐号称谓、网上评论及回应记录等。Cultura Colectiva 专门发布拉丁美洲娱乐及文化消息，在 Facebook、Instagram、Twitter、YouTube 等开设专页，拥有逾4500万用户追踪。《彭博社》向 Facebook 查询，Facebook 随后通报亚马逊，相关数据库已被封锁。Facebook 发言人表示，公司政策禁止将用户资料储存于公开数据库，此次发现事件后即时通知亚马逊处理；发言人称，公司致力与平台开发商合作保障用户私隐。

**3月**
- **SkyMed** Database Exposes Medical Info, PII Data of 137k People in U.S.

    影响人数：13万

    泄露目标：SkyMed members

    泄露内容：full names, addresses, dates of birth, email addresses, phone numbers

    link: https://www.bleepingcomputer.com/news/security/database-exposes-medical-info-pii-data-of-137k-people-in-us/


- **北京机到网络科技有限公司** 3300万份国人简历泄露

    影响人数：3300万

    泄露内容：求职者的用户名，性别，年龄，当前城市，家庭住址，电子邮件地址，电话号码，婚姻状况，工作经历，教育历史和工资历史

    事件经过：A large database with approximately 33 million profiles for people seeking jobs in China has been fully accessible and unprotected online. This information included sensitive information that could have been used for scammers and identity theft.

    The database was discovered by Sanyam Jain, a security researcher and member of GDI.Foundation, who found the database using the Shodan search engine.

    link: https://www.bleepingcomputer.com/news/security/unsecured-database-exposed-33-million-job-profiles-in-china/

**1月**
- **德国政界** 数百德国政客个人数据泄露

    泄露目标：除极右翼民主党以外的所有其他政党，其中还包括一些名人和记者。

    泄露内容：电子邮件地址、手机号码、身份证照片以及相当一部分聊天记录

    事件经过：据BBC、路透社等多家海外媒体报道，所有泄露的信息都是通过一个名为“G0d”的Twitter帐户在之前的数周内放出的，账户信息显示，该账户目前有粉丝约17000人，地址位于汉堡，并使用了“安全研究”、“艺术家”、“讽刺与反讽”等标签形容自己。

- **华硕** 内网密码在 GitHub 上泄露

    泄露内容：企业内网密码

    事件经过：北京时间3月28日早间消息，据美国科技媒体TechCrunch报道，一名信息安全研究员两个月前向华硕发出警告称，有华硕员工在GitHub代码库中错误地发布了密码。这些密码可以被用于访问该公司的企业内网。其中一个密码出现在一名员工分享的代码库中。通过该密码，研究员可以访问内部开发者和工程师使用的电子邮件帐号，从而与计算机的使用者分享夜间构建的应用、驱动和工具。有问题的代码库来自华硕的一名工程师，他将电子邮件帐号密码公开已有至少一年时间。目前，尽管GitHub帐号仍然存在，但这个代码库已被清理。

    link: http://hackernews.cc/archives/25173

---

## 2018🤷‍

**12月**
- **Quora** 1亿用户数据因为第三方黑客恶意攻击而遭到泄露

    影响人数：1亿

    泄露目标：Quora用户

    泄露内容：姓名、电子邮箱、加密密码、个人资料

    大致时间：公开于2018年12月3日

    事件经过：12月3日，美国知名问答社区 Quora 发公告称，1亿用户数据因为第三方黑客恶意攻击而遭到泄露，其中包括用户的邮箱、姓名和被加密的密码，以及他们在网站上分享的内容。

    link: http://hackernews.cc/archives/24547

**11月**
- **Amazon** 部分用户信息被泄露：包括姓名和邮件地址

    影响人数：不详

    泄露目标：Amazon用户

    泄露内容：姓名、邮件地址

    事件经过：北京时间11月22日早间消息，据美国财经媒体CNBC报道，亚马逊向给用户发邮件称，由于出现技术问题，一些用户的姓名和邮件地址被泄露。目前已经有一些人在网上发布他们收到的邮件截图。这些邮件中说，用户没有必要因此次事故而修改密码。但CNBC指出，有了名字和邮件地址，黑客仍然可以借此重设用户帐号，或利用邮件发起“钓鱼攻击”。

    link: http://hackernews.cc/archives/24486

**10月**
- **国泰航空** 数据泄露，940万乘客受影响

    影响人数：940万

    泄露目标：国泰航空乘客

    泄露内容：乘客姓名；国籍；出生日期；电话号码；电邮地址；地址；护照号码；身份证号码；飞行常客计划的会员号码；顾客服务备注；及过往的飞行记录信息。

    事情经过: 根据国泰航空的说法，他们于今年3月在系统中发现可疑活动后立即与网络安全公司合作进行调查，确定攻击者如何获得系统访问权限以及如何修复漏洞。调查进行至5月，国泰航空发现攻击者能够访问包含多达940万条乘客个人数据的系统。

    link: https://news.cathaypacific.com/%E5%9C%8B%E6%B3%B0%E8%88%AA%E7%A9%BA%E5%85%AC%E4%BD%88%E6%B6%89%E5%8F%8A%E4%B9%98%E5%AE%A2%E8%B3%87%E6%96%99%E7%9A%84%E8%B3%87%E6%96%99%E5%AE%89%E5%85%A8%E4%BA%8B%E4%BB%B6#
    link: https://www.solidot.org/story?sid=58359

**9月**
- **喜达屋酒店** 5亿条个人信息泄露

    影响人数：5亿

    泄露目标：喜达屋酒店消费者

    泄露内容：姓名、电子邮箱、邮寄地址、电话号码、护照号码、帐户信息、出生日期、性别、旅行信息、住宿信息、信用卡信息等。

    大致时间：2018年9月10日，但泄露真正发生时间可追溯到2014年。

    事件经过：与很多其它官方违规声明一样，这家万豪旗下的连锁酒店发布了一份称其服务器遭受“未授权访问”的声明，一个顾客预订数据库被黑客入侵，可能有约5亿顾客的信息泄露。该消息公布后，万豪国际酒店股价在当天盘前交易中一度下跌逾5%。

**8月**
- **华住酒店** 被曝5亿条个人信息泄露在暗网兜售
    影响人数：5亿

    泄露内容：身份证号、手机号

    事件经过：今年8月份，网曝华住酒店集团旗下酒店用户信息在“暗网”售卖，售卖者称数据已在8月14日脱库。身份证号、手机号，一应俱全，共涉及5亿条公民信息。此次泄露的全部数据信息被卖家打包以8比特币出售（当时约合人民币38万元）。卖家还称，以上数据信息的截止时间为2018年8月14日。

- **Newegg** 5000万信用卡账号支付信息泄露

    影响人数：5000万

    泄露目标：Newegg在线消费者

    泄露内容：信用卡账号

    大致时间：2018年8月14日-9月18日

    事件经过：网络犯罪团伙Magecart在Newegg网站上注入了信用卡略读代码。每当消费者在线购买东西时，支付信息会直接发送到Magecart的C＆C（命令和控制服务器）上。

**7月**
- **汽车供应商 Level One** 数据泄露导致一百多家汽车厂商机密数据曝光

    泄露目标：在全球 100 多家合作伙伴

    泄露内容：与 Level One 合作的多家汽车制造厂商（包括特斯拉、通用、福特、大众等）的装配线、工厂原理图、保密协议；机器人的配置、规格、动画；蓝图；ID 凭证和VPN 访问请求表；客户联系信息等。涉及厂商超过 100 家。

    事件经过：据多家外媒报道，7 月初，来自 UpGuard 安全团队的研究员 Chris Vickery 在网上发现了汽车供应商 Level One 的不安全数据库，数据库包括将近 47000 份文件，涵盖汽车制造厂商近十年的详细蓝图、工厂原理图、客户材料（如合同、发票、工作计划等），以及各种保密协议文件，甚至连员工的驾驶证和护照扫描件等隐私信息也包含在内。整个数据库的数据总量达 157 GB。Chris Vickery 表示，通过 Level One 的文件传输协议 rsync，可以不需要密码，直接访问他发现的这个数据库。

- **500px**

    影响人数：1486万

    泄露内容：出生日期，电子邮件地址，性别，地理位置，姓名，密码，用户名

    大致时间：2018年7月5日

    事件经过：In mid-2018, the online photography community 500px suffered a data breach. The incident exposed almost 15 million unique email addresses alongside names, usernames, genders, dates of birth and either an MD5 or bcrypt password hash. In 2019, the data appeared listed for sale on a dark web marketplace (along with several other large breaches) and subsequently began circulating more broadly. The data was provided to HIBP by a source who requested it to be attributed to "BenjaminBlue@exploit.im".

    link: https://haveibeenpwned.com/PwnedWebsites#500px

**6月**
- **A站** 官方宣传近千万条用户数据外泄(把用户数报高一点好让快手爸爸多给钱?)

    影响人数：官方宣传近千万条用户

    事件经过: 北京时间 6 月 13 日凌晨，AcFun 发布公告称网站遭遇黑客攻击，近千万条用户数据外泄。呼吁 2017 年 7 月 7 日之后从未登陆过的用户以及密码强度低的用户及时更改密码。如果在其他网站使用与 A 站相同的密码，也应及时修改。

- **Exactis** 3.4亿人口总数据泄露

    影响人数：3.4亿（2.3亿消费者数据，1.1亿企业数据）

    泄露目标：互联网个人和企业用户

    泄露内容：数据种类超过400类，包括电话号码、电子邮箱、邮寄地址、兴趣爱好、年龄、宗教信仰、宠物情况等。

    事件经过：美国市场营销公司Exactis采集了大约3.4亿条记录，大小约2TB，可能涵盖了2.3亿人的个人数据，几乎是全美的上网人口。Exactis此次的信息泄露并不是黑客撞库引起或者其它恶意攻击，而是他们自己的服务器没有防火墙加密，直接暴露在公共的数据库查找范围内。

- **MyHeritage** 9200万用户数据泄露

    影响人数：9200万

    泄露目标：MyHeritage用户

    泄露内容：邮箱地址、加密密码

    事件经过：网络安全研究人员于2018年6月对MyHeritage发出安全警告，发现外部服务器上存有敏感的MyHeritage信息。该公司确认信息真实性后立即发布通告，提醒用户立即更改密码，所有在2017年10月26日之前注册的帐户都存在泄露风险。

**5月**
- **Linux Forums** 遭遇数据泄露，导致276k电子邮件地址泄露。

    影响人数：27万

    泄露目标：Linux Forums用户

    泄露内容：Email addresses, IP addresses, Passwords, Usernames

    事件经过：In May 2018, the Linux Forums website suffered a data breach which resulted in the disclosure of 276k unique email addresses. Running on an old version of vBulletin, the breach also disclosed usernames, IP addresses and salted MD5 password hashes. Linux Forums did not respond to multiple attempts to contact them about the breach.

    link: https://haveibeenpwned.com/PwnedWebsites#LinuxForums

**4月**
- **Panera** 3700万用户数据泄露

    影响人数：3700万

    泄露目标：Panera用户

    泄露内容: 姓名、邮箱、地址、生日、信用卡账号后四位

- **TrueMove H** 遭遇数据泄露

    影响人数：46000人

    泄露内容：驾驶执照和护照

    事件经过：运营商向在线客户公开存储在亚马逊AWS S3存储桶中的个人数据。泄露的数据还包括身份证件的扫描，数据一直保留至4月12日，当时该公司限制访问。
    安全研究人员Niall Merrigan发现了大量数据，试图将此问题告知TrueMove H，但运营商没有回应。Merrigan透露，该AWS存储桶包含总计32GB的46,000条记录。

**3月**
- **Facebook** 用户数据泄露，影响美国大选(小扎你看你就像个外星人)

    影响人数：8700万

    泄露目标：Facebook用户

    泄露内容：个人资料、政治倾向、好友信息、私人消息

    大致时间：2018年3月

    事件经过：事件起源于Facebook与剑桥分析公司的合作，剑桥分析公司为了学术研究，在脸书上创建了一个应用预测用户性格喜好的APP用来测试，可是剑桥分析公司不仅收集了用户的测试结果，还在未经允许地情况下顺道收集了5000万用户在Facebook上的个人信息。
    剑桥分析公司获得了5000万活跃用户数据后，建立起用户画像，通过计算机对每个用户的兴趣爱好、性格和行为特点进行精确分析，预测他们的政治倾向。然后定向向用户推送新闻，借助Facebook的广告投放系统，影响用户的投票行为。于是，Facebook对美国大选产生了难以推脱的影响。

**2月**
- **MyFitnessPal** 1.5亿用户数据泄露

    影响人数：1.5亿

    泄露目标：MyFitnessPal用户

    泄露内容：姓名、电子邮箱、加密密码

    大致时间：2018年2月下旬

    事件经过：美国著名运动装备品牌Under Armour称有1.5亿MyFitnessPal用户数据被泄露了，MyFitnessPal是一款在苹果和谷歌应用商店中很受欢迎的应用，跟踪用户每天消耗的卡路里、设置运动目标、集成来自其它运动设备的数据，还可以分享运动成果到类似Facebook这样的社交平台上。此次关于用户数据泄露的声明使得该公司的股票价格盘后下跌了2.4%。

---

## 2017🙎‍

**10月**
- **Disqus** 宣布他们遭受了数据泄露

    影响人数：17,551,044

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：In October 2017, the blog commenting service Disqus announced they'd suffered a data breach. The breach dated back to July 2012 but wasn't identified until years later when the data finally surfaced. The breach contained over 17.5 million unique email addresses and usernames. Users who created logins on Disqus had salted SHA1 hashes of passwords whilst users who logged in via social providers only had references to those accounts.

    link: https://haveibeenpwned.com/PwnedWebsites#Disqus

**9月**
- **Equifax** 一亿四千三百万美国人数据泄露

    影响人数：一亿四千三百万

    泄露目标：基本上包括了美国的每一个成年人

    泄露内容：姓名、社会保险号码、生日、地址，驾照号码，信用卡号码，信用报告纠纷相关文件。
    事件经过：2017年9月Equifax发现5月至7月期间遭到黑客攻击导致1.43亿用户的个人信息遭到泄露将近一半美国人的隐私信息暴露在风险中包括姓名、社安号美国身份证号、地址、驾照号、社保账号等还包括20.9万人的信用卡号码18.2万人的个人税收信用文件是当时有史以来规模最大、破坏性最强的数据泄露事件之一。Equifax股价在事件公布一天内暴跌近14%两周内下跌了31%且面临4.39亿美元的法律、补救、保险和调查成本。Equifax的CEO、CSO首席安全官、CIO 首席信息官在事发后立即宣布退休。

    大致时间：公开于2018年12月3日

**8月**
- **Aadhaar印度国家身份认证系统** 11亿用户数据泄露(印度国家身份认证系统将公民信息卖给了乡村企业家?)

    泄露目标：印度公民

    泄露内容：Aadhaar号码、姓名、电子邮箱、住址、电话号码以及照片

    大致时间：2017年8月—2018年1月

    事件经过：2018年1月4日，印度乡村企业家 Bharat Bhushan Gupta爆料说，有人在移动社交工具WhatsApp上向他推销Aadhaar数据库，购买之后，Aadhaar数据库确实为他提供了大量意想不到的用户信息。

---

## 2016🙇‍

**12月**
- **优酷** 遭遇数据泄露，暴露了9200万个唯一用户帐户和相应的MD5密码散列

    影响人数：918万

    泄露目标：优酷用户

    泄露内容：Email addresses, Passwords

    link: https://haveibeenpwned.com/PwnedWebsites#Youku

- **Uber** 被黑客盗取用户信息

    影响人数：5760万

    泄露目标：用户和司机

    泄露内容：电话号码电子邮箱、姓名,司机的驾照号

    事件经过：2016年底黑客通过窃取Uber公司的AWS实例凭证获得了数千万Uber用户和司机的个人数据。5700万人的个人身份信息被窃取包括电话号码电子邮箱、姓名等此外60.7万名司机的驾照号被盗。最终Uber支付了1.48亿美元的法律诉讼和解费。

- **Yahoo!** 两起数据泄露事件

    影响人数：5亿、10亿

    泄露目标：Yahoo用户

    泄露内容：用户名、电子邮箱、电话、生日、密码以及安全问答等

    事件经过：2016年Yahoo! 公布了2起数据泄露事件——一起是在9月这一事件危害5亿以上的账户持有人另一起是在12月这一事件影响了超过10亿的账户持有人。泄露的信息于2014年至2016年12月期间收集黑客窃取的信息包括用户名、电子邮箱、电话、生日、密码以及安全问答等。Yahoo! 在事后补救和法律费用上花费超过9500万美元因未及时向投资者披露黑客行为被额外罚款3500万美元。由于违规行为Verizon收购Yahoo!比原报价少了3.5亿美元。

**11月**
- **xHamster** 数十万色情账号有消息称黑客正在交易(要命)

    影响人数：377,377

    泄露目标：xHamster用户

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：In November 2016, news broke that hackers were trading hundreds of thousands of xHamster porn account details. In total, the data contained almost 380k unique user records including email addresses, usernames and unsalted MD5 password hashes.

    link: https://haveibeenpwned.com/PwnedWebsites#xHamster

**9月**
- **爱拍** 包含约650万个账户的数据在网上被泄露

    影响人数：649万

    泄露目标：爱拍用户

    泄露内容：Email addresses, Passwords

    link: https://haveibeenpwned.com/PwnedWebsites#Aipai

**8月**
- **Epic Games** 252k账户被曝光

    影响人数：25万

    泄露目标：Epic Games用户

    泄露内容：Email addresses, IP addresses, Names, Passwords, Payment histories, Phone numbers, Physical addresses, Usernames, Website activity

    link: https://haveibeenpwned.com/PwnedWebsites#EpicGames

- **Cross Fire** 俄罗斯游戏论坛被黑客入侵 (战斗民族的枪战梦想?)

    影响人数：1286万

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：In August 2016, the Russian gaming forum known as Cross Fire (or cfire.mail.ru) was hacked along with a number of other forums on the Russian mail provider, mail.ru. The vBulletin forum contained 12.8 million accounts including usernames, email addresses and passwords stored as salted MD5 hashes.

    link: https://haveibeenpwned.com/PwnedWebsites#CrossFire

**3月**
- **CD Projekt RED** 论坛遭遇数据泄露

    影响人数：187万

    泄露目标：CD Projekt RED论坛用户

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：In March 2016, Polish game developer CD Projekt RED suffered a data breach. The hack of their forum led to the exposure of almost 1.9 million accounts along with usernames, email addresses and salted SHA1 passwords.

    link: https://haveibeenpwned.com/PwnedWebsites#CDProjektRed

**2月**
- **Linux Mint** 遭到黑客攻击，ISO受到后门的感染

    影响人数：14万

    泄露内容：Avatars, Dates of birth, Email addresses, Geographic locations, IP addresses, Passwords, Time zones, Website activity

    事件经过：In February 2016, the website for the Linux distro known as Linux Mint was hacked and the ISO infected with a backdoor. The site also ran a phpBB forum which was subsequently put up for sale complete with almost 145k email addresses, passwords and other personal subscriber information.

    link: https://haveibeenpwned.com/PwnedWebsites#LinuxMint

**1月**
- **BitTorrent** 的论坛遭到黑客攻击

    影响人数：3万

    泄露目标：BitTorrent用户

    泄露内容：Email addresses, IP addresses, Passwords, Usernames

    事件经过：In January 2016, the forum for the popular torrent software BitTorrent was hacked. The IP.Board based forum stored passwords as weak SHA1 salted hashes and the breached data also included usernames, email and IP addresses.

    link: https://haveibeenpwned.com/PwnedWebsites#BitTorrent

- **uTorrent** 遭遇数据泄露

    影响人数：39万

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：In early 2016, the forum for the uTorrent BitTorrent client suffered a data breach which came to light later in the year. The database from the IP.Board based forum contained 395k accounts including usernames, email addresses and MD5 password hashes without a salt.

    link: https://haveibeenpwned.com/PwnedWebsites#uTorrent

---

## 2015🙃

**10月**
- **Patreon** 被黑，超过16GB资料流落网络

    泄露目标：Patreon用户

    泄露内容：注册名称、电子邮件位址、张贴内容、送货地址，以及2014年以前的某些帐单地址，Patreon网站的原始码

    事件经过：10月，独立安全研究人员Troy Hunt在他自己所设立的haveibeenpwned网站上公布：音乐众筹网站Patreon已遭骇客入侵，并有超过16GB的资料在网路上流窜， Patreon也已证实此事。Patreon是由音乐家Jack Conte及开发人员Sam Yam在2013年创立的众筹网站，主要是替音乐或影片的作者筹募创作基金。Hunt指出，黑客公布了超过16GB的Patreon资料，其中包含14GB的资料库纪录，还有逾230万个电子邮件位址与数百万封的讯息，甚至还有Patreon网站的原始码。

    link: http://www.ijiandao.com/safe/it/16278.html

**9月**
- 内蒙古19万考生信息泄露

    影响人数：19万

    泄露目标：内蒙古19万名高考考生

    泄露内容：姓名、身份证号码及其父母姓名、电话

    事件经过：据新华社电内蒙古自治区教育招生考试中心透露，内蒙古19万名高考考生信息近日遭泄露。9月2日上午得知此事后，教育招生考试中心立即组织人员进行研判，并确认网传信息基本属实。随后，该单位立即报警，希望警方进行彻查。这些信息中包括考生的姓名、身份证号码及其父母姓名、电话，名单覆盖了内蒙古自治区的12个盟市，数量最多的地方达4万多条。

    link: https://news.ifeng.com/a/20150908/44601584_0.shtml

- **TalkTalk** 400万人信息泄漏

    影响人数：400万

    泄露目标：TalkTalk用户

    泄露内容：姓名、地址、生日、电话号码、电邮地址、账户详细情况、信用卡详细情况等

    事件经过：今年9月英国宽带服务提供商TalkTalk表示，该公司网站日前所遭受的网络攻击可能导致其400多万客户的个人数据被盗，这可能是英国史上最大规模的数据泄漏事件之一。该公司表示很客户的姓名、地址、生日、电话号码、电邮地址、账户详细情况、信用卡详细情况等数据很有可能都被窃取了。这是TalkTalk今年第三次遭受网络攻击，计算机安全专家格雷汉姆·克鲁利(Graham Cluley)指出：“他们的品牌将受损，他们的客户可能已经忍无可忍了。”

    link: http://news.mydrivers.com/1/453/453003.htm

**8月**
- **大麦网** 600多万用户账号密码泄露 数据已被售卖

    影响人数：600万

    泄露目标：大麦网用户

    泄露内容：用户注册信息数据库

    事件经过：8月27日，乌云漏洞报告平台发布报告显示，线上票务营销平台大麦网再次被发现存在安全漏洞，600余万用户账户密码遭到泄露。起初发现有大麦网用户数据库在黑产论坛被公开售卖，于是对泄露的用户数据进行验证，发现相邻账号的用户ID也是连续的，并均可登录。因此，丛技术的角度可以初步证明本次大麦网的数据泄露有被拖库嫌疑(网站用户注册信息数据库被黑客窃取)。

    link: http://tech.sina.com.cn/i/2015-08-27/doc-ifxhkafa9342416.shtml

**2月**
- **Uber** 5万名优步司机信息遭泄露

    影响人数：5万

    泄露目标：优步司机

    泄露内容：司机的个人信息

    事件经过：2月28日，大约5万名优步(Uber)司机的个人信息被不知名的第三方人士获取，成为该公司遭遇的最大规模的数据泄露事件。去年9月Uber系统中出现一个漏洞，能让外人在未经授权的情况下，获取部分司机的姓名和驾照号码。虽然Uber声称已堵上这一漏洞，但随后的调查显示，去年5月，相关数据曾遭遇“一次未授权的访问“。

    link: http://tech.huanqiu.com/original/2015-02/5777913.html

**1月**
- **机锋论坛** 包括用户名、邮箱、加密密码的2300万用户信息泄漏

    影响人数：2300万

    泄露目标：机锋用户

    泄露内容：用户名、注册邮箱、加密后的密码等信息

    事件经过：机锋科技旗下机锋论坛被曝出存在高危漏洞，多达2300万用户的信息遭遇安全威胁。这也成为2015年国内第一起网络信息泄露事件。据知情人士称，机锋论坛泄露的2300万用户数据包括用户名、注册邮箱、加密后的密码等信息，由于机构数据库对用户密码仅使用了简单的MD5（计算机安全领域广泛使用的一种散列函数）加密，黑客能够快速破解出绝大部分明文密码。

    link: http://tech.sina.com.cn/it/2015-01-06/01199932312.shtml

---

## 2014🙅‍

**12月**
- **12306**大量用户资料泄露

    影响人数：13万

    泄露目标：12306用户

    泄露内容：用户帐号、明文密码、身份证邮箱等信息

    事件经过：12月25日，国内漏洞报告平台乌云官网爆出，大量12306用户数据在互联网疯传包括用户帐号、明文密码、身份证邮箱等信息。关于此次12306用户数据泄露事件，国内某安全研究团队方面验证了该消息的准确性，并获取到了该文中提到的样本数据，文件标题为《12306 邮箱-密码-姓名-身份证-手机(售后群：31109xxxx).txt》，共计131653条记录、文件大小14M。随机抽取了一批帐号(约50个)均成功登陆12306，证明了该批数据是准确的，对于里面出现的明文用户密码，该团队初步推测是利用现有用户数据进行“撞库”。针对用户信息泄露一事，12306官方网站随后发布公告称，经过调查，此次泄露信息全部含有用户的明文密码，并称12306网站数据库所有用户密码均为多次加密的非明文转换码，同时暗示用户的明文密码为第三方抢票软件泄漏。

    link: https://www.williamlong.info/archives/4089.html

**11月**
- **Warframe**

    影响人数：81万

    泄露目标：Warframe论坛玩家

    泄露内容：Email addresses, Usernames, Website activity

    事件经过：In November 2014, the online game Warframe was hacked and 819k unique email addresses were exposed. Allegedly due to a SQL injection flaw in Drupal, the attack exposed usernames, email addresses and data in a "pass" column which adheres to the salted SHA12 password hashing pattern used by Drupal 7. Digital Extremes (the developers of Warframe), asserts the salted hashes are of "alias names" rather than passwords.

    link: https://haveibeenpwned.com/PwnedWebsites#Warframe

**9月**
- **Yandex** 的大量账户泄露的消息被曝光。

    影响人数：118万

    泄露内容：Email addresses, Passwords

    事件经过：In September 2014, news broke of a massive leak of accounts from Yandex, the Russian search engine giants who also provides email services. The purported million "breached" accounts were disclosed at the same time as nearly 5M mail.ru accounts with both companies claiming the credentials were acquired via phishing scams rather than being obtained as a result of direct attacks against their services.

    link: https://haveibeenpwned.com/PwnedWebsites#Yandex

**5月**
- **Avast** 论坛被黑，423k会员数据被曝光

    影响人数：42万

    泄露目标：Avast论坛用户

    泄露内容：Email addresses, Passwords, Usernames

    link: https://haveibeenpwned.com/PwnedWebsites#Avast

- **小米论坛** 用户数据遭泄漏

    影响人数：800万

    泄露目标：小米论坛用户

    泄露内容：用户名、密码、邮箱、注册IP以及密码盐

    据国内安全问题反馈平台乌云网昨晚公布信息显示，小米论坛存在用户资料泄露，涉及800万小米论坛注册用户，疑似小米手机论坛的用户数据库已经在黑客界传播，小米用户需要即时修改密码。乌云网称，泄漏的数据包含用户名、密码、邮箱、注册IP以及密码盐（salt），由于小米账户的特殊性（云存储），如果帐号密码被破解，很可能影响到用户的个人数据安全，比如，通讯录、短信、照片、GPS位置信息甚至远程擦除手机数据（格式化）。

    link: https://www.williamlong.info/archives/3853.html

**1月**
- **Snapchat** 暴露了460万个用户名和电话号码

    影响人数：460万

    泄露内容：Geographic locations, Phone numbers, Usernames

    事件经过：In January 2014 just one week after Gibson Security detailed vulnerabilities in the service, Snapchat had 4.6 million usernames and phone number exposed. The attack involved brute force enumeration of a large number of phone numbers against the Snapchat API in what appears to be a response to Snapchat's assertion that such an attack was "theoretical". Consequently, the breach enabled individual usernames (which are often used across other services) to be resolved to phone numbers which users usually wish to keep private.s

    link: https://haveibeenpwned.com/PwnedWebsites#Snapchat

---

## 2013😢

**10月**
- **Adobe** 1.53亿账号泄露

    影响人数：1.53亿

    泄露目标：Adobe用户

    泄露内容：Email addresses, Password hints, Passwords, Usernames

    link: https://haveibeenpwned.com/PwnedWebsites#Adobe

**9月**
- **imgur** 遭遇数据泄露

    影响人数：174万

    泄露内容：Email addresses, Passwords

    事件经过：In September 2013, the online image sharing community imgur suffered a data breach. A selection of the data containing 1.7 million email addresses and passwords surfaced more than 4 years later in November 2017. Although imgur stored passwords as SHA-256 hashes, the data in the breach contained plain text passwords suggesting that many of the original hashes had been cracked. imgur advises that they rolled over to bcrypt hashes in 2016.

    link: https://haveibeenpwned.com/PwnedWebsites#imgur

**2月**
- **tumblr** 遭遇数据泄露，导致超过6500万个账户被曝光。

    影响人数：6546万

    泄露内容：Email addresses, Passwords

    事件经过：In early 2013, tumblr suffered a data breach which resulted in the exposure of over 65 million accounts. The data was later put up for sale on a dark market website and included email addresses and passwords stored as salted SHA1 hashes.

    link: https://haveibeenpwned.com/PwnedWebsites#Tumblr

## 2012👀

**7月**
- **Dropbox** 遭遇了数据泄露，暴露了数千万客户的存储凭据。

    影响人数：6864万

    泄露内容：Email addresses, Passwords

    事件经过：In mid-2012, Dropbox suffered a data breach which exposed the stored credentials of tens of millions of their customers. In August 2016, they forced password resets for customers they believed may be at risk. A large volume of data totalling over 68 million records was subsequently traded online and included email addresses and salted hashes of passwords (half of them SHA1, half of them bcrypt).

    link: https://haveibeenpwned.com/PwnedWebsites#Dropbox

**5月**
- **LinkedIn** 遭遇了数据泄露

    影响人数：1.6亿

    泄露内容：Email addresses, Passwords

    事件经过：2016年一名俄罗斯黑客Peace在暗网出售LinkedIn的用户资料总资料多达1.67亿笔当中达1.17亿笔包含了账号密码售价为5个比特币当时约合2200美元。黑客Peace表示这些资料源自2012年的一次攻击,当时Peace就黑掉了LinkedIn并曾在网上出售LinkedIn超过600万条的账户信息。

    link: https://haveibeenpwned.com/PwnedWebsites#LinkedIn

**1月**
- **VK** 遭到黑客攻击，近1亿个账户被曝光。

    影响人数：9333万

    泄露内容：Email addresses, Names, Passwords, Phone numbers

    事件经过：In approximately 2012, the Russian social media site known as VK was hacked and almost 100 million accounts were exposed. The data emerged in June 2016 where it was being sold via a dark market website and included names, phone numbers email addresses and plain text passwords.

    link: https://haveibeenpwned.com/PwnedWebsites#VK

## 2011🤔

**12月**
- 2011年底，中国发生的一系列数据泄露事件影响了1亿用户，其中包括来自 **17173游戏网站** 的750万用户。

    影响人数：750万

    泄露目标：17173用户

    泄露内容：Email addresses, Passwords, Usernames

    link: https://haveibeenpwned.com/PwnedWebsites#17173

- **CSDN** 用户数据库泄露事件

    影响人数：600万

    泄露目标：CSDN用户

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：2011年12月21日，黑客在网上公开了知名程序员网站CSDN的用户数据库，高达600多万个明文的注册邮箱账号和密码遭到曝光和外泄，成为中国互联网历史上一次具有深远意义的网络安全事故。

    link: https://www.williamlong.info/archives/2933.html

- **天涯社区** 4000万用户资料泄露

    影响人数：4000万

    泄露目标：天涯用户

    泄露内容：Email addresses, Passwords, Usernames

    事件经过：据天涯网新浪微博上的介绍，由于历史原因，天涯社区早期使用过明文密码，2010年之后改成了加密密码。此次遭到黑客泄漏的用户便是2009年保存的备份数据。该份高达386M的泄漏文件“天涯数据.kz”经过下载验证，里面保存了天涯的用户名、密码、邮箱三个数据，根据泄漏的天涯用户名和密码测试，大部分都可以可直接登录到天涯社区。从密码的构成看，泄密的密码很多并非是弱密码，而是8位以上的强密码，因此可以认为天涯的确是以明文方式保存的用户密码。

    link: https://www.williamlong.info/archives/2939.html

**6月**
- **当当** 遭遇数据泄露

    影响人数：480万

    泄露目标：天涯用户

    泄露内容：Email addresses

    事件经过：In 2011, the Chinese e-commerce site Dangdang suffered a data breach. The incident exposed over 4.8 million unique email addresses which were subsequently traded online over the ensuing years.

    link: https://haveibeenpwned.com/PwnedWebsites#Dangdang

- **Sony** 多业务被攻击

    影响人数：3.7万

    泄露内容：Dates of birth, Email addresses, Genders, Names, Passwords, Phone numbers, Physical addresses, Usernames

    事件经过：In 2011, Sony suffered breach after breach after breach — it was a very bad year for them. The breaches spanned various areas of the business ranging from the PlayStation network all the way through to the motion picture arm, Sony Pictures. A SQL Injection vulnerability in sonypictures.com lead to tens of thousands of accounts across multiple systems being exposed complete with plain text passwords.

    link: https://haveibeenpwned.com/PwnedWebsites#Sony

---


# 供应链攻击
## 2018

**12月**
- **驱动人生** 供应链攻击事件

    事件经过：2018年12月14日下午，腾讯安全御见威胁情报中心监测到一款通过“驱动人生”系列软件升级通道传播的木马突然爆发，仅2个小时受攻击用户就高达10万。该病毒会通过云控下发恶意代码，包括收集用户信息、挖矿等，同时利用“永恒之蓝”高危漏洞进行扩散。腾讯御见威胁情报中心立即对该病毒疫情对外通报，并发布详细的技术分析报告。

    2018年12月14日晚，驱动人生公司接到腾讯御见威胁中心的事件预警后，对该事件高度重视，第一时间与腾讯安全御见威胁情报中心进行联系，告知在木马爆发时，驱动人生公司相关技术人员正在国外旅游团建，因此高度怀疑该事件是驱动人生公司的升级服务器被黑客攻击导致，并请求腾讯企业安全应急响应中心一起协助追查事故原因。同时，驱动人生公司对该事件向深圳警方报警，并对外发布了紧急声明和采取相应的应对措施。

    link: https://www.freebuf.com/articles/system/192194.html

    link: https://www.anquanke.com/post/id/169683

**5月**
- **Python** 官方库SSH-Decorator被植入后门

    事件经过：据 Reddit 用户报告，在 Python 库的SSH-Decorator 软件包中发现了窃取用户 SSH 私钥及帐号密码的后门，目前该库已被Python官方移除。SSH-Decorator 为以色列开发人员Uri Goren开发，主要用途为解决用户从Python代码中发起的SSH通信连接。

    link: https://www.reddit.com/r/Python/comments/8hvzja/backdoor_in_sshdecorator_package/
    link: http://www.arkteam.net/?p=3601

**4月**
- 攻击者试图在 **Mailparser** 中植入后门

    事件经过：在4月底，NPM包管理团队（Node Package Manager）发现，有攻击者意欲想在流行的JavaScript软件包Mailparser中植入后门。

    link: http://blog.npmjs.org/post/173526807575/reported-malicious-module-getcookies

## 2017

**12月**
- **Wordpress** Keylogger事件

    事件经过：Catalin Cimpanu发现几起针对WordPress站点的攻击，主要通过加载恶意脚本进行键盘记录，挖矿或者挂载广告。并且有证据表明，这种攻击从4月份活跃至今。起因是WordPress被注入了一个混淆的js脚本，从主题的function.php文件进行植入。加载的js脚本地址为：
    ```
    <script type='text/javascript' src='hxxp://cloudflare[.]solutions/ajax/libs/reconnecting-websocket/1.0.0/reconnecting-websocket.js'></script>
    <script type='text/javascript' src='hxxp://cloudflare[.]solutions/ajax/libs/cors/cors.js'></script>
    ```
    其中reconnecting-websocket.js用作websocket通信，cors.js中包含后门。Cors.js更改前端页面，释放javascript脚本进行输入监听，之后将数据发送给攻击者（wss://cloudflare[.]solutions:8085/）。

    link: https://www.bleepingcomputer.com/news/security/keylogger-found-on-nearly-5-500-infected-wordpress-sites/
    link: https://www.anquanke.com/post/id/89941

**10月**
- **Elmedia Player** 软件攻击事件

    事件经过：Elmedia Player是一款专门为Mac OS X 打造的免费媒体播放器，通过它可播放和管理Mac上的Flash影片、电影视频等等。2017年10月19日ESET注意到Elmedia Player软件的制造商Eltima正在其官方网站上发布一个被植入OSX/Proton恶意软件的应用程序。ESET联系Eltima之后2017年10月20日Eltima官方发布安全公告，公告称旗下macOS平台下的Folx 和 Elmedia Player两款软件的DMG因为官网被入侵而被篡改并被植入了恶意代码，具体影响到了2017年10月19日在官网下载该两款软件的用户。该软件用户数大约在100万左右。这是今年既XshellGhost和CCleaner之后又一起严重的针对供应链攻击的事件。

    link: https://www.anquanke.com/post/id/87063

**9月**
- **PyPI** 上发现十余个恶意Python库

    事件经过：2017年，斯洛伐克国家安全办公室发现，在PyPI库中存在十余款恶意的Python软件包，之后，这些软件包被Python官方迅速移除。

    link: https://www.bleepingcomputer.com/news/security/ten-malicious-libraries-found-on-pypi-python-package-index/

- **CCleaner** 被植入恶意代码

    事件经过：近日，有安全研究团队表示，著名的系统优化工具CCleaner被发现植入恶意代码。大量使用该工具的用户恐将面临泄密风险。这是继Xshell后门事件后，又一起严重的软件供应链来源攻击事件。据研究人员估算全球2000万用户受到感染，但CCleaner官方称只有227万用户受到影响。

    link: http://it.rising.com.cn/dongtai/18995.html

- **Chrome插件User–Agent Switcher** 供应链攻击事件

    事件经过：在此处事件中User-Agent Switcher为广大的攻击者提供了一种新型的供应链攻击模式—从大分发机构出发,对交付这一过程进行攻击,作者通过混淆自己的恶意代码进入图片接着在插件运行的时候再从图片中解密出恶意代码进行运行,从而绕过了Chrome商店的严格审查机制,成功的堂而皇之的登录到了Chrome应用商店,然而对用户而言,官方的应用商店无疑是代表着官方的认证,以及质量和安全,时至今日已经Chrome商店的统计数据显示:累计有458,450的用户已经安装了该插件,可以看到Chrome商店在这之中扮演着重要的角色,交付这一环节上,就让chrome成功收录了自己的应用,然后利用chrome应用商店这个更为广大的品台吸引到更多的用户进行下载使用,从而造成更大的危害。

    link: https://www.anquanke.com/post/id/86892

**8月**
- **NetSarang** 旗下多款软件的关键模块被植入了高级后门

    事件经过：2017年7月17日，NetSarang公司发布旗下多款产品的新版软件，更新修复多处bug和增强了会话加密能力，用于对抗CIA木马“BothanSpy”的密码劫持功能。
    2017年8月7日，NetSarang与卡巴斯基发布联合声明，声称7月18日发现软件存在安全漏洞被攻击。
    2017年8月15日，NetSarang与卡巴斯基更新联合声明，发现在香港利用该软件漏洞的案例。

    NetSarang系列软件的关键网络通信组件nssock2.dll被植入了恶意代码，厂商在发布软件时并未发现恶意代码，并给感染组件打上了合法的数字签名随新版软件包一起发布，用户机器一旦启动软件，将会加载组件中的恶意代码，将主机的用户信息通过特定DGA(域名生成算法)产生的DNS域名传送至黑客的远程命令控制服务器，同时黑客的服务器会动态下发任意的恶意代码至用户机器执行。

    link: https://www.freebuf.com/articles/terminal/144842.html

    link: https://slab.qq.com/news/tech/1637.html

- **假冒“老毛桃”工具** 推广木马

    事件经过：2017年8月，360安全中心接到多起网友反馈，称电脑中所有浏览器的主页都被篡改，而且强制锁定为http://dh936.com/?00804推广页面。据360安全专家分析，这是一款假冒“老毛桃”PE盘制作工具的推广木马在恶意作祟。下载该制作工具后，其捆绑的“净网管家”软件会释放木马驱动篡改首页。当发现中招者试图安装安全软件时，还会弹出“阻止安装”提示，诱导中招者停止安装。专家进一步分析后发现，该驱动还设置了不少保护措施逃避安全软件查杀，如禁止自身文件和注册表的浏览和读取等。

    link: http://bobao.360.cn/interref/detail/207.html

- **WireX Android Botnet** 污染 Google Play 应用市场

    事件经过：2017年8月17日，名为WireX BotNet的僵尸网络通过伪装普通安卓应用的方式大量感染安卓设备并发动了较大规模的DDoS攻击，此举引起了部分CDN提供商的注意，此后来自Akamai, Cloudflare, Flashpoint, Google, Oracle Dyn, RiskIQ, Team Cymru等组织联合对该事件进行分析，并于8月28日发布了该事件的安全报告。

    报告发现大约有300种不同的移动应用程序分散在Google Play商店中，WireX引发的DDoS事件源自至少7万个独立IP地址，8月17日攻击数据的分析显示，来自100多个国家的设备感染了WireX BotNet。

    link: https://blog.cloudflare.com/the-wirex-botnet/?utm_content=buffer9e1c5

    link： https://slab.qq.com/news/kuaixun/1641.html

- **Arris** 为AT&T家庭用户定制版调制解调器内置后门事件

    事件经过：2017年8月，安全研究人员发现知名电信设备制造商Arris生产的调制解调器存在5个安全漏洞，其中有3个是硬编码后门账号漏洞。攻击者利用三个后门账号均可控制设备，提升至ROOT权限、安装新固件，乃至于架设僵尸网络等。有问题的调制解调器型号为Arris NVG589、Arris NVG599，主要在美国宽带运营商AT&T的网络里使用，但在Arris官网找不到信息（停产产品？）。Nomotion研究人员推测，它们可能是专为AT&T家庭用户定制的入网设备。研究人员认为易受漏洞攻击调制解调器至少有22万台。

    link: https://www.4hou.com/info/news/7522.html

**7月**
- **基于域名bjftzt.cdn.powercdn.com** 的软件升级劫持攻击

    事件经过：360安全卫士在2017年7月5日披露，有多款软件用户密集反映360“误报了软件的升级程序”，但事实上，这些软件的升级程序已经被不法分子恶意替换。这次事件其实是基于域名bjftzt.cdn.powercdn.com的一组大规模软件升级劫持事件。用户尝试升级若干知名软件客户端时，运营商将HTTP请求重定向至恶意软件并执行。恶意软件会在表面上正常安装知名软件客户端的同时，另外在后台偷偷下载安装推广其他软件。山东、山西、福建、浙江等多省的软件升级劫持达到空前规模，360安全卫士对此类攻击的单日拦截量突破40万次。

    link: http://www.mottoin.com/detail/1324.html

**5月**
- **惠普** 笔记本音频驱动内置键盘记录后门事件

    事件经过：2017年5月，来自瑞士安全公司Modzero的研究人员在检查Windows Active Domain的基础设施时发现惠普音频驱动中存在一个内置键盘记录器监控用户的所有按键输入。研究人员指出，惠普的缺陷代码（CVE-2017-8360）不但会抓取特殊键，而且还会记录每次按键并将其存储在人类可读取的文件中。这个记录文件位于公用文件夹C:\Users\Public\MicTray.log中，包含很多敏感信息如用户登录数据和密码，其他用户或第三方应用程序都可访问。因此安装到计算机上的恶意软件甚至是能物理接近计算机的人都能够复制日志文件并访问所有的用户按键、提取敏感数据如银行详情、密码、聊天日志和源代码。2015年，这个按键记录功能以新的诊断功能身份在惠普音频驱动版本1.0.0.46中推出，并自此有近30款惠普计算机都内置有这种功能。

    link: https://www.anquanke.com/post/id/86085

**2月**
- **百度** 旗下网站暗藏恶意代码,官方回应:外包团队干的,已报案

    事件经过：经火绒安全实验室截获、分析、追踪并验证，当用户从百度旗下的http://www.skycn.net/和 http://soft.hao123.com/这两个网站下载任何软件时，都会被植入恶意代码。该恶意代码进入电脑后，会通过加载驱动等各种手段防止被卸载，进而长期潜伏，并随时可以被“云端”远程操控，用来劫持导航站、电商网站、广告联盟等各种流量。

    link: https://www.huorong.cn/info/148826116759.html

## 2016

**10月**
- **索尼** 80款监控摄像头被曝存在后门,索尼拒绝回复

    事件经过：2016年10月，安全公司SEC Consult曝出了索尼安防摄像头的后门漏洞，竟然影响了高达80款索尼“IPELA ENGINE”的网络摄像头产品。
    在就在最新固件中，SEC发现了两大后门——

    1、Hardcoded密码和root账户

    学过编程应该知道，Hardcoded也就是硬编码，并非变量，是写死的固定内容，SEC开发的工具软件IoT侵入者于是便通过穷举法来获取到密码内容。同时，SEC还发现了隐藏的root口令，达到让所有人以超级管理员身份登录。

    2、两个Debugging账户

    索尼挖的坑还不止于此。索尼为固件修复留了两个debug调试账户，一个用户名“primana”密码“primana”，还有一个用户名“debug”密码“popeyeConnection”。

    debug账户因为可以远程访问，所以危险系数更高，比如被不法分子用集群服务器攻击。SEC已经将报告递交索尼，后者也在新固件对上述问题进行了修复。至于为什么要留后门以及到底用来干什么，索尼拒绝回复。

    link: https://news.mydrivers.com/1/510/510837.htm

<p align="center">
    <img src=".//img/sony.jpg">
</p>

## 2015

**12月**
- **Juniper** VPN后门事件

    事件经过：2015年12月15日著名网络设备厂商Juniper公司发出风险声明，其防火墙、VPN设备使用的操作系统具有重大安全风险，建议尽快升级相关版本。根据声明，设备的SSH登录系统在输入任意用户名的情况下，使用超级密码就可以最高权限登录系统，设备的VPN安全通道上传递的数据可以被攻击人解密、篡改和注入。全球上万NetScreen设备被攻击。

    link: https://www.anquanke.com/post/id/83148

**10月**
- **百度**旗下应用开发SDK Moplus被曝其中内含后门

    事件经过：2015年11月百度moplus SDK的一个被称为虫洞（Wormhole）的漏洞被漏洞报告平台wooyun.org所披露，研究人员发现Moplus SDK具有后门功能，但这不一定是由于漏洞或跟漏洞相关，之所以称之为漏洞是基于Moplus SDK的访问权限控制以及应该如何限制这种访问的角度。因此，它虽然具有漏洞相关的概念而实际上是一个后门程序，如推送钓鱼网页，插入任意联系人，发送伪造短信，上传本地文件到远程服务器，未经用户授权安装任意应用到Android设备。而执行这些行为唯一的要求是该设备首先需要连接互联网。由于Moplus SDK已经被集成到众多的Android应用程序中，这就意味着有上亿的Android用户受到了影响。

    研究结果还表明，已经有恶意软件在利用Moplus SDK的漏洞，它被植入到14000款app当中，这些app有接近4000个都是由百度出品的。经统计有2846个app包含后门库，苹果设备感染量未知。

    link: https://www.leiphone.com/news/201511/N9FR2E1434teyADU.html

**9月**
- **XcodeGhost** 事件

    事件经过：2015年9月，XcodeGhost事件爆发，超过4000个不同版本的苹果应用被感染，影响了中国近一亿苹果手机用户。
    Xcode非官方版本恶意代码污染事件

    Xcode 是由苹果公司发布的运行在操作系统Mac OS X上的集成开发工具（IDE），是开发OS X 和 iOS 应用程序的最主流工具。2015年9月14日起，一例Xcode非官方版本恶意代码污染事件被披露，多数分析者将这一事件称为“XcodeGhost”。攻击者通过向非官方版本的Xcode注入病毒Xcode Ghost，它的初始传播途径主要是通过非官方下载的 Xcode 传播，通过 CoreService 库文件进行感染。当应用开发者使用带毒的Xcode工作时，编译出的App都将被注入病毒代码，从而产生众多携带病毒的APP。至少692种APP受污染，过亿用户受影响，受影响的包括了微信、滴滴、网易云音乐等著名应用。

    link: https://unit42.paloaltonetworks.com/novel-malware-xcodeghost-modifies-xcode-infects-apple-ios-apps-and-hits-app-store/

    link: https://security.tencent.com/index.php/blog/msg/96

- **幽灵推Ghost Push**

    事件经过：2015年8月，酷派大神手机用户在安装官方提供的系统升级包后，手机便被预安装了MonkeyTest和TimeService等未知软件。截止到9月18日，该类病毒的每日感染量已经扩大到了最高70万台/天，有上万种机型收到了Ghost Push的影响，典型的有酷派、三星、MOTO等等。

    link: https://www.freebuf.com/articles/terminal/78781.html

**2月**
- **方程式组织** 硬盘固件程序攻击

    事件经过：卡巴斯基安全实验室在2015年2月16日起发布系列报告披露了一个网络攻击组织：“方程式”组织（Equation Group）。该组织拥有一套用于植入恶意代码的超级信息武器库（在卡巴的报告中披露了其中6个），其中包括两个可以对数十种常见品牌的硬盘固件重编程的恶意模块，这可能是该组织掌握的最具特色的攻击武器，同时也是首个已知的能够感染硬盘固件的恶意代码。而通过相关安全公司分析的结论可以看出，在此次硬盘固件程序攻击事件中可以做到如此有针对性（特定目标、行业），部分攻击方式极有可能属于物流链劫持，即在特定目标采购、返修主机或硬盘的过程中修改了硬盘固件。

    link: https://www.freebuf.com/news/59185.html

## 2014

**8月**
- **磊科(NetCore)** 全系列路由器中的“疑似后门”程序

    事件经过：磊科(NetCore)路由器中内置了一个叫做IGDMPTD的程序，按照它的描述应该是IGD MPT Interface daemon 1.0。该程序会随路由器启动，并在公网上开放端口，攻击者可以执行任意系统命令、上传下载文件，控制路由器。

    一切的开始源自于今年8月份买了一个磊科(NetCore)家用路由器。随后发现IGDMPTD，并做了测试工具验证。Google后发现在今年8月25日，趋势科技的研究员Tim Yeh发表文章描述了这个”疑似后门”的IGDMPTD，并报告厂商。

    随后在今年10月3日Tim Yeh再次发表文章，指出磊科官方并未完全删掉这个”后门程序”。

    link: http://blog.trendmicro.com/trendlabs-security-intelligence/netis-routers-leave-wide-open-backdoor/

    link: http://blog.trendmicro.com/trendlabs-security-intelligence/netis-router-backdoor-patched-but-not-really/

**4月**
- **Joomla** 插件后门

    link: https://blog.sucuri.net/2014/04/joomla-plugin-constructor-backdoor.html

**3月**
- **WordPress**的盗版插件后门程序

    事件经过：2011年，WordPress团队发现目前在WordPress流行的一些插件存在安全隐患，插件被恶意插入后门程序，以便获取用户的数据，主要是用户的管理员密码。

    这些恶意后台并非是插件作者有意作为，而是第三方的人在破解了插件作者的管理信息之后插入后门信息的。

    link: https://blog.sucuri.net/2014/03/unmasking-free-premium-wordpress-plugins.html

## 2013

**12月**
- **NetGear** 多款路由器存在后门

    事件经过：NetGear生产的多款路由器存在后门。该后门为厂商设置的超级用户和口令，攻击者可以利用后门，在相邻网络内可获取到路由器的root权限，进而植入木马完全控制用户的路由器。后续可发起dns劫持攻击。

    link: https://www.cnvd.org.cn/flaw/show/CNVD-2013-15013

**10月**
- **腾达Tenda** 路由器后门

    事件经过：在友讯科技（D-Link）路由器发现后门之后，安全研究员又在另一家路由器制造商腾达（Tenda）的产品中发现了后门。安全研究人员分析了腾达路由器W302R的最新固件， 发现了名叫MfgThread的独立线程，捆绑了7329端口，接收 UDP数据包，会对含有特殊字符的指令作出反应，这些特殊字符包括了e、1和X——对于e，会返回一个预定义的字符串，基本上是一个ping测试；对于 1，它将允许你运执行iwpriv命令， iwpriv命令可用于配置路由器网络端口；对于X，它给予你root权限，可以执行任何命令。作者认为，这个后门可能最早是在腾达的W302R路由器上 实现的，存在于W330R路由器和Medialink的路由器MWN-WAPR150N中。

    link: http://www.devttys0.com/2013/10/from-china-with-love/

    link: https://www.freebuf.com/articles/terminal/14425.html

**6月**
- **美国** "棱镜门"事件

    事件经过：棱镜计划（PRISM）是一项由美国国家安全局（NSA）自2007年起开始实施的绝密电子监听计划，该计划的正式名号为“US-984XN”，直接进入美国网际网路公司的中心服务器里挖掘数据、收集情报，包括微软、雅虎、谷歌、苹果等在内的9家国际网络巨头皆参与其中。

    其中以思科公司为代表的科技巨头利用其占有的市场优势在科技产品中隐藏“后门”，协助美国政府对世界各国实施大规模信息监控，随时获取各国最新动态。思科公司多款主流路由器产品被曝出在VPN隧道通讯和加密模块存在预置式“后门”，即技术人员在源码编写过程中已经将“后门”放置在产品中，利用“后门”可以获取密钥等核心敏感数据。

- **DLink** 存在管理后门

    事件经过：当攻击者请求中的User Agent（Http请求包中用于标识浏览器的字段）包含特殊的字符串“xmlset_roodkcableoj28840ybtide”，该用户可以绕过路由器的帐号密码验证直接访问其Web管理界面。

    link: http://blog.jobbole.com/49959/
    link: https://bbs.pediy.com/thread-182012.htm

## 2012

**6月**
- **F5** BIG-IP内置SSH私钥

    事件经过：  F5公司是应用交付网络(ADN)领域全球领导者.提供应用安全,数据中心防火墙,负载均衡,数据存储,广域网优化,虚拟化及云计算解决方案。

    2012年6月，安全研究人员发现F5多个产品（F5 BIG-IP）存在一个未明配置错误，允许未身份验证的用户以“root”账户登录设备。问题原因是SSH private key对应的公钥内置于漏洞设备中，使得用户可以绕过验证直接登录F5设备。

    link: https://www.trustmatta.com/advisories/MATTA-2012-002.txt

    link: https://www.trustmatta.com/advisories/matta-disclosure-policy-01.txt

**1月**
- **中文版putty等** SSH远程管理工具被曝存在后门

    事件经过：2012年1月，中文版putty等SSH远程管理工具被曝存在后门，窃取用户名与口令发送至指定服务器上。

    link: https://www.cnbeta.com/articles/tech/171116.htm

## 2010

**11月**
- **ProFTPD** 镜像服务器被入侵

    事件经过：流行的开源FTP服务器ProFTPD在2010年发现被人在代码中放了一个后门。 在安装了包含有后门的ProFTPD服务器版本后，攻击者可以获得系统控制权限，攻击者的IP地址来自沙特阿拉伯地区。在该版本中，输入命令“HELP ACIDBITCHEZ”会出现一个root shell。攻击者利用了一个尚未修复的0day漏洞。受影响的版本是从11月28日到2日在官方镜像下载的ProFTPD 1.3.3c。

    link: https://www.exploit-db.com/exploits/15662

    link: http://www.h-online.com/security/news/item/Back-door-in-ProFTPD-FTP-server-1146592.html

## 2003

**11月**
- **Linux内核** 后门

    事件经过：早在2003年，有人试图向Linux内核插入一个微妙后门源代码。该代码被写入到给一个后门，没有外在标志，被托管的服务器入侵与Linux源相连的其他电脑。只有两行代码被更改， 并有可能轻轻松松瞒过大多数的眼睛。幸运的是，后门代码审计人员发现了。关于谁应该对此负责的猜测仍然很多。也许某个要求Linus Torvalds向Linux添加后门程序的三个字母的机构可能知道。

    link: https://freedom-to-tinker.com/2013/10/09/the-linux-backdoor-attempt-of-2003/

    link: https://lwn.net/Articles/57135/

## 2001

**1月**
- **Borland** 的数据库软件后门

    事件经过：Borland公司的InterBase数据库软件中的一个“后门”使得任何拥有适当口令的人都可以对数据库和运行数据库的计算机系统实施严重的破坏行为。

    计算机紧急反应小组在当地时间星期三发表的咨询报告中称，这一“后门”可以使黑客改变存储在数据库中的信息，甚至在计算机中运行造成更大破坏的程序。用户名和口令写在程序里，很容易被发现，而且不能通过改变设置清除掉。

    Borland公司承认存在这样一个“后门”，并且已经开始发布补丁，并通知用户和合作伙伴将于本周推出修改后的版本，这一漏洞存在于4、5、6版的InterBase中。

    link: https://www.kb.cert.org/vuls/id/247371/

---

`“我想，你们这帮家伙应该考虑比这大得多的问题。”`