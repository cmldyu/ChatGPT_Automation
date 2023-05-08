# ChatGPT_自动化

使用未被检测到的 Chrome Driver 接口与 ChatGPT 通信

您需要安装 Chrome 浏览器。为了通过 Cloudflare 机器人测试，必须使用未被检测到的 Chrome 浏览器。

以下是快速开始的方法。

## 安装

```
git clone https://github.com/ugorsahin/ChatGPT_Automation
cd ChatGPT_Automation
pip install .
```

## 用法

```
from chatgpt_automation import ChatGPT_Client

chatgpt = ChatGPT_Client(用户名, 密码)

answer = chatgpt.interact("嘿伙计，今天咋样？")

print(answer)
```

