# OTU


## 概述

本专案用于部署 OTU，在合理使用的程度下，本镜像不会因为大量占用资源而导致封号。

部署完成后，每次启动应用时，运行的 OTU 将始终为最新版本

## 部署

### 步骤

 1. Fork 本专案到自己的 GitHub 账户（用户名以 `example` 为例）
 2. 修改专案名称，注意不要包含两个关键字（修改后的专案名以 `demo` 为例）
 3. 修改 `README.md`，替换为自己的内容（如 `example/demo`）

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/MinocaX/OTU)

 4. 回到专案首页，点击上面的链接以部署 V2Ray

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `b9cd8d9a-f809-4411-b261-093cb9597dc9` | 用户主 ID，用于身份验证，为 UUID 格式 |
| `WSPATH` | `/` |HTTP 协议路径 |
