# 目前有计费bug，礼拜六修
# New API
### Linux.do公益版
> [!NOTE]
> 本项目为开源项目，在[One API](https://github.com/songquanpeng/one-api),[New API](https://github.com/linux-do/new-api)的基础上进行二次开发

> [!IMPORTANT]
> 使用者必须在遵循 OpenAI 的[使用条款](https://openai.com/policies/terms-of-use)以及**法律法规**的情况下使用，不得用于非法用途。
> 本项目仅供个人学习使用，不保证稳定性，且不提供任何技术支持。
> 根据[《生成式人工智能服务管理暂行办法》](http://www.cac.gov.cn/2023-07/13/c_1690898327029107.htm)的要求，请勿对中国地区公众提供一切未经备案的生成式人工智能服务。


## 主要变更
此分叉版本的主要变更如下：

1. 额度签到(前端暂不可配，此功能仅支持Linux.do论坛账户登陆方式使用)
2. 消息穿透
3. qa记录(仅记录文字)
4. 额度有效期

## 部署
### 部署要求
- 本地数据库（默认）：SQLite（Docker 部署默认使用 SQLite，必须挂载 `/data` 目录到宿主机）
- 远程数据库：MySQL 版本 >= 5.7.8，PgSQL 版本 >= 9.6

## 功能截图
![img.png](img.png)
![img_2.png](img_2.png)
![img_3.png](img_3.png)
![img_4.png](img_4.png)
![img_5.png](img_5.png)
![img_6.png](img_6.png)
![img_7.png](img_7.png)
## 技术支持

- [Linux.do](https://github.com/linux-do)

- [BennyThink](https://github.com/BennyThink)

## 快速反馈
- [全球工单中心](https://linux.do/u/furry/summary)
## 相关项目
- [One API](https://github.com/songquanpeng/one-api)：原版项目
- [Midjourney-Proxy](https://github.com/novicezk/midjourney-proxy)：Midjourney接口支持
- [chatnio](https://github.com/Deeptrain-Community/chatnio)：下一代 AI 一站式 B/C 端解决方案
- [neko-api-key-tool](https://github.com/Calcium-Ion/neko-api-key-tool)：用key查询使用额度
