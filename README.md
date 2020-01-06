## debug-tsserver_server

VSCode 用于调试 tsserver 的服务端配置。

### 前置条件

（1）配置 [debug-tsserver_client](https://github.com/thzt/debug-tsserver_client) 客户端  

（2）客户端启动调试  
会启动 tsserver，端口号默认为 `9002`。  
端口号可在 [debug-tsserver_client/index.js#L7](https://github.com/thzt/debug-tsserver_client/blob/master/index.js#L7) 配置。 

（3）VSCode 打开本仓库，按 `F5` attach 到 tsserver  

- - -

### 参考

[淡如止水 TypeScript（八）: 3. 调试 tsserver](https://www.yuque.com/thzt/typescript/suz2wo#d1ba7040)
