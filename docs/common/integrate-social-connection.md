{{$localeConfig.brandName}} 社会化登录支持四种接入方式：**使用 JavaScript SDK**、**使用嵌入登录组件**、 **使用托管登录页** 和 **手动调用社会化登录接口**。每种不同的接入方式各有优劣点，你可以根据自己的业务需求来选择合适的方式。

以下是各种方式的优劣对比：

| 接入方式                                                                | 优势                                                                              | 劣势                                                | 是否推荐                                               |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------ |
| 使用 JavaScript SDK <img width=200 style="display:inline;float:right"/> | 接入简单，只需要几行代码。可自定义程度最高。                                      |                                                     | <img width=120 style="display:inline;float:right"/> 是 |
| 使用嵌入登录组件                                                        | 接入简单，只需要几行代码。可以将该组件集成到你的应用。自定义程度相对较高          |                                                     | 是                                                     |
| 使用托管登录页                                                          | 运维简单，由 {{$localeConfig.brandName}} 负责运维。每个用户池有一个独立的二级域名。 | 如果需要嵌入到你的应用，需要使用弹窗模式登录，即：点击登录按钮后，会弹出一个窗口，内容是 Authing 托管的登录页面，或者将浏览器重定向到 Authing 托管的登录页。                                | 是                                                     |
| 手动调用社会化登录接口                                                  |                                                                                   | 需要手动从 URL 解析用户信息。接入相对较为复杂麻烦。 | 不推荐                                                 |