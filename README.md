# 介绍 

交谈，是我们每天都在做的事，也是最容易习惯的人机交互方式，这是各种音箱大卖的原因之一。"Kim智能语音助理"是一个开源的语音、文本交互方案。同时，通过部署云端服务，使设备具备远程会话能力能力，增加可玩性。

除此之外，Kim的目标是将智能语音助理与智能家居系统无缝结合，我们已经支持著名开源智能家居系统"HomeAssistant"，可以接入小米、博联等主流品牌的智能家居设备。

与阿里云的深度融合，使Kim对云端能力触手可及，让你的私人语音助理更加智能，更易扩展，充满魅力。

[![GitHub license](https://img.shields.io/github/license/tenstone/kim-voice-assistant.svg)](https://github.com/tenstone/kim-voice-assistant/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/tenstone/kim-voice-assistant.svg)](https://github.com/tenstone/kim-voice-assistant/issues)
[![Python3.6](https://img.shields.io/badge/python3.6-green-brightgreen.svg)](https://www.python.org)
[![PyPI](https://img.shields.io/pypi/v/nine.svg)](https://pypi.python.org/pypi)


## 主要特性

1. 基于阿里云服务构建
1. Docker化快速安装部署
1. 优化中文语义仲裁算法（KSM），精准理解中文语义
2. 可选安装"远程会话服务"
2. 跨平台支持Respberry Pi、macOS、Windows

## 应用场景

### 内置功能

1. 智能家居控制
1. 讲段子，查天气、查快递等
1. 听新闻头条，热门微博
1. ……

### 自定义插件，扩展Kim的能力

1. 根据用户意图，请求外部网络接口，完成语音对话交互（或selenium实现Web语音交互）
1. 语音客服机器人
1. ……

你完全可以把Kim作为一个交互入口，去实现更多功能。

## 技术架构

Kim使用Python3.6编写，设备端实现了中文语义仲裁算法和"Kim大脑"；会话日志数据存储、插件、设备在线状态及数据传输等功能基于阿里云服务实现。

![technical architecture](https://raw.githubusercontent.com/tenstone/kim-voice-assistant/master/images/technical_architecture.png)


# 安装使用

## 直接安装（支持Windows、macOS等平台）

### 安装步骤

## 技术文档

1. [智能语音交互(ASR)：一句话识别RESTful API](https://help.aliyun.com/document_detail/52787.html)
1. [智能语音交互(TTS)：语音合成RESTful API](https://help.aliyun.com/document_detail/52793.html)
1. [阿里云物联网套件：介绍](https://help.aliyun.com/document_detail/30522.html)
1. [阿里云物联网套件：设备端基于MQTT接入](https://help.aliyun.com/document_detail/30539.html)
1. [阿里云物联网套件：服务器端Python SDK使用](https://help.aliyun.com/document_detail/42700.html)
1. [表格存储：使用与开通](https://help.aliyun.com/document_detail/27293.html)
1. [表格存储：Python SDK](https://help.aliyun.com/document_detail/31723.html)
1. [云小蜜：快速创建会话机器人](https://help.aliyun.com/document_detail/60459.html)
1. [云小蜜：知识库配置指南](https://help.aliyun.com/document_detail/60747.html)
1. [阿里云云市场：API市场](https://market.aliyun.com/data)
1. [HomeAssitant：接入文档](https://home-assistant.io/docs/)
1. [HomeAssistant：智能家居组件接入](https://home-assistant.io/components/)

### 运行方法

# TODO

1. 支持Docker镜像安装（语音模式仅支持基于Linux Kernel的平台）

# 鸣谢

1. 感谢阿里云提供技术支持
1. 感谢阿里云[天池大赛](https://tianchi.aliyun.com/)官方
1. 感谢[The Jasper Project](http://jasperproject.github.io/)和[DingDang](https://github.com/wzpan/dingdang-robot)的开发者，他们启发了我的灵感




