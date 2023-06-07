# 飞书 SDK

   根据飞书的[开发文档](https://open.feishu.cn/document/ukTMukTMukTM/uQjN3QjL0YzN04CN2cDN)，开发了更加方便使用的 SDK。

## yaml 的配置
需要配置以下格式

    feishu:
        app_secret: 'your app_secret'
        app_id: 'your app_id'
        
配置环境变量

    import os
    os.environ.setdefault('PYLYCHEE_SETTINGS', 'your path.yml')
