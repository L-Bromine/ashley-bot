# Ashley Bot
Ashley Bot，艾希 Bot。   
基于 AliceBot、 Mirai 框架和 OpenAI API 实现的 QQ 智能群聊机器人。擅长作为可爱的猫娘和大家互动。  
**Warning: Ashley bot is still under heavy development. Some feature may be changed in future version.**

## How To Use

### 准备工作

#### 可用的 mirai-http-api 接口

请参阅相关项目文档，确保您已经成功运行并登入了机器人，并且有一个可用 `mirai-http-api`接口。

#### (可选) 在服务器上使用代理软件

在使用前，请确保您的服务器可以正常访问 OpenAI 相关 API，如果不能做到这一点，请考虑使用相关网络代理工具。相关部署教程请参阅相关文档。

如果使用代理请确保您在本机 1080 端口有可用的 sock 代理。

> **Note**: This feature may changed in the future. Using http proxy or change port number is not support at current time.

#### 安装依赖

```bash
$ python -m venv venv # You should create a virtualenv first. :-)
$ pip install -r requirements.txt
```

#### 修改配置

依赖环境安装结束后，请重命名`config.toml.example`为`config.toml`，重命名`config.yaml.example`为`config.yaml`，并按照提示或阅读详细说明修改其中配置。

### 运行机器人

使用以下命令来启动机器人

```bash
$ python main.py
```

##### (可选) 使用 Docker 或者 Supervisor 进行部署

*Coming Soon*

## More

Ashley 的名字来源于 AI 自己。她很高兴称呼自己为 Ashley 。我们也很高兴。

## Thanks
- [AliceBot](https://github.com/AliceBotProject/alicebot)

- [mirai](https://github.com/mamoe/mirai)

- [mirai-console-loader](https://github.com/iTXTech/mirai-console-loader)

- [mirai-http-api](https://github.com/project-mirai/mirai-api-http)
- [openai-python](https://github.com/openai/openai-python)