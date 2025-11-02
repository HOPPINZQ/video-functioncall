## 介绍 👋

纯前端工程，演示FunctionCall的使用。让AI去操作你的视频播放器

## 📗启动
 - video_ai.html修改如下配置
    ```text
    // 代理地址的大模型必须支持gpt系
    var settings = {
        "url": "OPENAI代理地址",
        "method": "POST",
        "timeout": 0,
        "headers": {
            "Authorization": "Bearer sk-你的APIKEY",
            "Content-Type": "application/json"
        },
        "data": JSON.stringify(data),
    };
    // 必须是gpt系对话大模型
    var model = "gpt-4o-mini";
    ```
 - 运行video_ai.html即可

## 演示
https://www.bilibili.com/video/BV1AAyZBkEN9/