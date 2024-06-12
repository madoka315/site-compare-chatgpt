# 🤖site-compare-chatgpt

⭐个人对第三方中文AI站点的对比，旨在满足个人偶尔的需求，且作分享

⭐Update: 2024-06-13

⭐如对高级模型需求不大，国内的大模型也很方便好用！例如通义千问、智谱清言

## 🧾规则
0. 纯手动依次注册测试统计，有任何重大错误疏漏，有失效跑路站点可以反馈
1. **站点收集自[https://github.com/LiLittleCat/awesome-free-chatgpt](https://github.com/LiLittleCat/awesome-free-chatgpt)，排名不分先后，未受到任何推广**
2. 不统计纯nextchat套壳（即只能填入APIKEY使用的）；不统计高价和文档糟糕的站点；由于个人需求，统计的站点大部分支持用量计费

## 📊站点一览及备注
   
| 名称         | GPT4T单价 (站点代币) <sup>注1</sup>         | 依据充值档位<sup>注2</sup>  | 同请求消耗测试 <sup>注3</sup> | 网站          | 支持高级模型 <sup>注4</sup>         | 免费特性 (量化)<sup>注5</sup>                     |
|--------------|------------------------|------------|--------------|---------------------------|---------------------|-----------------------------------------|
| ichat2019    | 5000token/元 (1w字节)   | 20元       | 86token(173字节) | www.ichat2019.com        | GPT4T               | 免费10000token(邀请15000token)           |
| 不墨         | 1777token/元 (2w6豆)    | 30元       | 65token(975豆)   | chat.bumo.tech           | GPT4T、Claude3      | 免费66token(邀请333token); 每日20token  |
| aivesa       | 8680token/元            | 28.8元     | 98token         | aivesa.cn                | GPT4T(❌附件)        | 免费20000token(邀请20000token)           |
| OPENAIGPT    | 1544token/元 (15.4条)  | 25.9元     | 100token(1条)   | chat.mossaigpt.com       | GPT4T               | 无                                      |
| 智友         | 2000token/元            | 任意       | 无免费额度无法测试 | chat.icoding.ink        | GPT4T、Claude3      | 无                                      |
| OhMyGPT      | 7249token/元 (3w4分)    | 20元       | 71token(333分)   | www.ohmygpt.com          | GPT4T(❌附件)、Claude3(❌附件) | 免费2772token；每日213token            |
| 柏拉图AI     | 2860token/元 (28.5条)  | 35元       | 100token(1条)   | chat.bltcy.top           | GPT4(具体不详)(❌附件) | 免费400token；每日20token               |
|              | 1430token/元 (14.3条)  |            | 200token(1条)  |                          | GPT4带附件、Claude3  |                                         |
| ai7号        | 14285token/元           | 39元       | 84token         | ai7.pro                  | GPT4(具体不详)       | 免费10000token(邀请10000token)           |
| Openai chat  | 28857token/元 (10点数) | 任意       | 81token(0.028点数) | ai.dfcsf.asia           | GPT4T、Claude3      | 免费2885token                           |
| AuroraVerse  | 1689token/元 (3378灵能) | 29.6元     | 有思想钢印无法测试 | vip.talktoai.club       | GPT4T、Claude3      | 免费1000token                           |
| OMEGA  | 2000token/元 | 任意    | 81token(0.4点数) | ai.omegaxyz.cn       | GPT4T      | 免费2000token                           |
- 注1: GPT4T代表```gpt-4-turbo```模型。网站有站点代币的，括号内表示1元能购买多少代币，token则表示量化后等值于多少token
- 注2: 选取十位数充值档位作为单价评价依据，网站可能具有其他充值档位
- 注3: 统一通过网站界面选择```gpt-4-turbo```模型，置空预设词，发送```hey how is it today```进行测试，统计网站显示的发送和回复总计需要的token
- 注4: 现阶段较强的大模型为GPT4和```claude-3-opus```，选取这两种模型作为支持状况的展示，网站可能支持其他大模型
- 注5：免费特性记录网站注册用户后可直接获得、使用的内容。不记录包括```gpt-3.5```、```gpt-4o```等官方也免费开放的模型

---
**以下是不能直接量化计费，但有优势的特殊站点**
| 名称 | 计费规则 | 网站 | 支持高级模型 | 免费特性 |
| --- | --- | --- | --- | --- |
| 智能AI助手 | 订阅: 50元/月不限次GPT4T<br>捐赠: 0.1元/次 GPT4官网、Claude3 (满30元赠API) | chat.tinycms.xyz:3002 | GPT4T、Claude3 | 免费每日10次GPT4T |
| Rawchat | 订阅: 49元/月专属共享账号<br>订阅: 3元/天专属共享账号 | sharedchat.cn| GPT4官网 | 有免费共享账号 |
| 试试威力AI | 订阅: 50元/月不限次GPT4(具体不详) | oai.aivipol.com | GPT4(具体不详) | 免费33次GPT4(具体不详) |
| Aitianhu | 捐赠: 30元/月不限次GPT4T | d2v2z6.aitianhu1.top | GPT4T | 无 |
| AI问答宝 | 订阅: 18.88元/月共享账号 | ai.wendabeta.net | GPT4官网 | 无 |
| 土豆AI | 订阅: 69.9元/月不限次GPT4T | tudouai.chat | GPT4T(❌附件) | 免费若干次 |
| EasyChat | 订阅: 50元/月不限次GPT4T | site.eqing.tech | GPT4T | 免费每日8次GPT4官网 |
| **特殊**Coze(GLOBAL) | API按量计费 | coze.com | GPT4T | 免费使用web端 |
