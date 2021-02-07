# 107AB0703 呂晨汝
## 期中作業

![image](https://github.com/107ab0703/107ab0703/blob/main/%E7%9B%B8%E4%BC%BC%E5%BA%A60.8.png)

# 學你說話
@handler.add(MessageEvent, message=TextMessage)
def echo(event):
    line_bot_api.reply_message(
        event.reply_token,
        TextSendMessage(text=event.message.text)
    )
