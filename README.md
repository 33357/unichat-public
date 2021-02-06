<!--
 * @Author: 33357
 * @Date: 2021-02-05 13:15:37
 * @LastEditTime: 2021-02-06 13:06:47
 * @LastEditors: 33357
-->

# unichat-public

unichat 项目开源信息

## 目录

- [项目背景](#项目背景)
- [项目设计](#项目设计)
- [项目预览](#项目预览)
- [访问项目](#访问项目)
- [相关项目](#相关项目)
- [升级计划](#升级计划)
- [维护成员](#维护成员)
- [加入贡献](#加入贡献)
- [开源协议](#开源协议)

## 项目背景

unichat 是一款基于区块链上通证关系而搭建的匿名社群管理平台，致力于实现以下目标：

- **通证即社群：** 通证即社群关系，通证项目的社群应满足以下要求：
  
  1. 通证项目的社群应该能自发建立。
  2. 通证项目的社群应该能独立运营。
  3. 通证项目的社群应该能自发达成共识与决议。

- **通证即身份：** 通证即社群身份，项目应该将主体成员的身份在区块链上公开，包括以下内容：
  
  1. 项目负责人的身份在区块链上的公开。
  2. 项目投票者的身份在区块链上的公开。
  3. 项目参与者的身份在区块链上的公开。

- **通证即权利：** 通证即代表了用户在社群中的权利，其权利包括：

  1. 加入并获取社群信息的权利。
  2. 参与社群决议投票的权利。
  3. 提出决议并参与执行的权利。

## 项目设计

- **用户登录：** 用户通过其钱包使用私钥对服务器指定信息进行签名，从而服务器验证其为私钥持有者完成登录。

- **社群检索：** 服务器为用户发送 TokenList，用户通过钱包检索其持有的 Token，当余额不为 0 时则加入该 Token 所属社群。

- **社群添加：** 用户主动输入 Token 地址，钱包检索其持有余额是否为 0，当余额不为 0 时则加入该 Token 所属社群。

- **显示Token：** 用户进行聊天时可以看到其他用户的Token余额。

- **验证Token：** 用可以点击其他用户的名片跳转区块链浏览器验证Token余额。

## 项目预览

- **用户登录：**

<img  src="./image/login-1.jpg" width="250" height="500" alt="用户登录-1"/>->
<img  src="./image/login-2.jpg" width="250" height="500" alt="用户登录-2"/>->
<img  src="./image/login-3.jpg" width="250" height="500" alt="用户登录-3"/>

- **社群检索：**

<img src="./image/loadToken-1.jpg" width="250" height="500" alt="社群检索-1"/>->
<img src="./image/loadToken-2.jpg" width="250" height="500" alt="社群检索-2"/>

- **社群添加：**

<img src="./image/addToken-1.jpg" width="250" height="500" alt="社群添加-1"/>->
<img src="./image/addToken-2.jpg" width="250" height="500" alt="社群添加-2"/>->
<img src="./image/addToken-3.jpg" width="250" height="500" alt="社群添加-3"/>

- **显示Token：**

<img src="./image/chat-1.jpg" width="250" height="500" alt="显示Token-1"/>->
<img src="./image/chat-2.jpg" width="250" height="500" alt="显示Token-2"/>

- **验证Token：**

<img src="./image/businessCard-1.jpg" width="250" height="500" alt="验证Token-1"/>->
<img src="./image/businessCard-2.jpg" width="250" height="500" alt="验证Token-2"/>->
<img src="./image/businessCard-3.jpg" width="250" height="500" alt="验证Token-3"/>

## 访问项目

目前项目部署于：[https://unichat.top](https://unichat.top)

PC端支持Chrome浏览器和MetaMask，移动端支持IMToken。

## 相关项目

- **unichat Server端开源信息：** [unichat-server-public](https://github.com/33357/unichat-server-public)

- **unichat APP端开源信息：** [unichat-app-public](https://github.com/33357/unichat-app-public)

- **unichat 智能合约开源信息：** [unichat-contract-public](https://github.com/33357/unichat-contract-public)

## 升级计划

- **独立 APP 开发：** 为获得更好的用户体验，并支持更多功能，计划进行脱离钱包支持的独立 APP 开发。

- **去中心化存储：** 为了减少网络波动和不可抗力的影响，计划对用户聊天信息实现去中心化的存储。

- **多链支持：** unichat 目标为所有区块链网络用户提供服务，将会对绝大多数的区块链提供服务。

- **链上认证：** 将会对用户的身份信息进行上链，实现跨账户、跨钱包用户的统一身份认证。

## 维护成员

[@33357](https://github.com/33357)

## 加入贡献

因为项目升级计划的原因，暂不支持加入贡献，但欢迎发起讨论。

## 开源协议

[MIT](LICENSE)