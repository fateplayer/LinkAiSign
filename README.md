# LinkAiSign
[![Last Commit](https://img.shields.io/github/last-commit/smillsion/LinkAiSign.svg?color=blue&label=%E6%9C%80%E8%BF%91%E6%8F%90%E4%BA%A4)](https://github.com/smillsion/LinkAiSign/commits/main)

link-ai签到获取积分

## 更新
2024-04-03 增加bark失败推送

2024-04-02 返回用户积分总计

## 功能
签到获取积分和返回总积分

## 拉库指令
青龙拉库指令 `ql repo https://smillsion/LinkAiSign.git`

#### 1. 登陆Link-Ai平台后在浏览器控制台执行以下代码
``` javascript
copy(localStorage.token); console.log(localStorage.token);
```
#### 2. 将以上获得的密钥，添加到环境变量 `LinkAiToken` 后即可使用
#### 3. 如果需要使用bark失败推送，需要配置 `MT_BARK_SERVER` 和 `MT_BARK_KEY` 环境变量(bark只有ios应用，可在AppStore下载)

## 贡献代码
项目没有经过严格测试。有问题可以在 **[Issues](https://github.com/smillsion/LinkAiSign/issues)** 反馈。

若您有好的想法，发现一些 **BUG** 并修复了，欢迎提交 **[Pull Request](https://github.com/smillsion/LinkAiSign/pulls)** 参与开源贡献。


## 声明
本项目仅做个人学习用途，我不会对因为滥用该项目导致的任何问题负责。