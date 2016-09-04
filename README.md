# v2ray-configuration
本项目提供 v2ray 的常用配置文件，减少部署 v2ray 时编写配置的时间和出错的概率。

项目中每一个配置均经过测试并且无误。同一个配置包含服务器和客户端的配置，分别命名为 `server.json` 和 `client.json`，server.json 和 client.json 是匹配的，使用时请一同使用 server.json 和 client.json 并注意区分服务器和客户端，以避免降低出错的概率。

配置中 `client.json` 的 `adress` 是必要修改项，请改为实际的服务器 ip 地址，其它的都是可选修改项，如有需要可自行调整配置并注意配置服务器和客户端匹配。
