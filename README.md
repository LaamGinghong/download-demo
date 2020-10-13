# Download Demo

## 准备工作

由于本项目依赖于 Node 环境，所以请事先安装好 Node.js，具体如何安装不做赘述。

```shell script
yarn install
```

## 启动服务

```shell script
cd service
node service.js
```

运行以上命令，启动一个本地 Node.js 服务，具体配置可以直接修改 service/service.js 文件。

前端页面可以直接通过文件系统来启动，也可以通过启动一个静态服务来启动，想怎么启动随你喜欢。

如果想要通过静态服务来启动，则首先安装 serve：

```shell script
yarn global add serve
```

返回到项目根目录中，启动静态服务：

```shell script
serve -s
```

