欢迎来到 飞书 的 文档!
====================================
Pylychee 是一个各种第三方 SDK 的集合体，省去了按照第三方接口文档对接的过程。谢谢你的关注。

快速安装
===================
pip install pylychee
    
开始使用
===================
使用前需要设置环境变量 PYLYCHEE_SETTINGS, 值为 yml 的文件位置
    
    import os
    os.environ.setdefault('PYLYCHEE_SETTINGS', 'your path.yml')

不同的 SDK，yaml 的配置也不同，比如飞书的 yaml 如何：

    feishu:
        app_secret: 'your app_secret'
        appid: 'your appid'

多个 SDK 的 yaml 配置，可以在一起配置使用。
