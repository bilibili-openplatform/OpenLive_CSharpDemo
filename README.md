## 说明 
本项目为直播创作者服务中心`C#`版Demo案例，用于验证签名以及基础ws示例。  

本SDK实现为基础功能，更多高级功能以及使用请自行探索，以及根据具体的业务功能和需求自行修改（例如重连、心跳等）

开放平台相关文档请访问：[哔哩哔哩互动玩法接入文档](https://open-live.bilibili.com/document/eba8e2e1-847d-e908-2e5c-7a1ec7d9266f)

## 环境要求
`Visual Studio 2022 + dotnet6`

## 使用范围
本签名示例的覆盖范围为[直播创作者服务中心](https://open-live.bilibili.com/document/bdb1a8e5-a675-5bfe-41a9-7a7163f75dbf#h1-u5E73u53F0u4ECBu7ECD)中相关接口的签名实现，不包含[哔哩哔哩开放平台文档中心](https://open.bilibili.com/doc)中的相关接口，请注意。

## 使用方法
在`OpenBLiveSample`项目的`Program.cs`文件头部需要填写的内容中填写注释说明中对应的内容。
```C#
        public const string AccessKeyId = "";//填入你的accessKeyId，可以在直播创作者服务中心【个人资料】页面获取(https://open-live.bilibili.com/open-manage)
        public const string AccessKeySecret = "";//填入你的accessKeySecret，可以在直播创作者服务中心【个人资料】页面获取(https://open-live.bilibili.com/open-manage)
        public const string AppId = "";//填入你的appId，可以在直播创作者服务中心【我的项目】页面创建应用后获取(https://open-live.bilibili.com/open-manage)
        public const string Code = "";//填入你的主播身份码Code，可以在互动玩法首页，右下角【身份码】处获取(互玩首页：https://play-live.bilibili.com/)
```

然后运行`OpenBLiveSample`项目即可得到示例结果
- 例如
![运行截图](https://github.com/user-attachments/assets/b3b8fc57-1627-45ee-b3e4-6aedf20ff51e)

图例中的消息字段说明见[长链消息cmd文档](https://open-live.bilibili.com/document/f9ce25be-312e-1f4a-85fd-fef21f1637f8)
