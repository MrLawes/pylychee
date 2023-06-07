# 消息

   飞书的[开发文档](https://open.feishu.cn/document/uAjLw4CM/ukTMukTMukTM/reference/im-v1/message/create)

## 发送消息
    
    import os
    
    from pylychee.apps import Messages
    
    os.environ.setdefault('PYLYCHEE_SETTINGS', 'your path.yml')
    messages = Messages()
    messages.send(text='消息内容', receive_ids=['消息接收者的ID',])

