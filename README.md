# fake-ola-node
一个基于GOlang编写的OLA挖矿客户端，支持在PC设备上运行，不再需要安卓和IOS设备，并且支持批量地址运行。
# 使用说明
配置config.json文件，支持多个client
```
{
  "client" : [
    {
      "name" : "节点1",
      "address" : "",
      "proxyUser" : "",
      "proxyPass" : "",
      "proxyType" : "",
      "proxy" : "",
      "retry" : true,
      "headers" : {
        "os-version" : "17.0",
        "os-type" : "ios",
        "app-version" : "0.2.1"
      }
    }
  ]
}
```
代理支持http和ssh代理，在proxyType填写你的代理信息即可，然后启动程序，开始挖矿。
