# 项目名称: BaiduDiskScanQrCodeSystem
*关键词：* 百度网盘扫码登录系统，远程登录系统，共享账号系统

## 项目介绍

*BaiduPanScanLoginSystem* 是一个基于百度网盘的远程扫码登录系统，采用 Java Spring Boot 后端和 Vue.js 前端构建。通过远程授权登录，提供强大的后台管理功能。项目涵盖百度账号管理、套餐管理、卡密管理、批量生成卡密、自动开卡、自动废卡、多种套餐验证方式等全方位功能。此外，系统还提供丰富的设置选项，允许管理员灵活调整用户界面的 HTML、公告内容，同时提供详细的使用教程和联系客服地址，以确保用户体验无缝连接。
## 服务器推荐：https://www.007idc.cn/aff/GVGFOKTS

## 基础功能

1. **账号管理：** 管理用户百度账号，支持添加、删除、修改账号信息。

2. **套餐管理：** 灵活管理不同的套餐选项，按照不同的认证方式生存套餐
     - 目前支持的套餐方式：
     - 1.只验证可用次数
     - 2.只验证过期时间
     - 3.同时校验时间和次数
     - 4.校验时间，过期时间内 每日刷新次数
3. **卡密管理：** 提供卡密管理功能
     - 绑定套餐一键批量生成卡密（高效生成大量卡密，提高系统效率）
     - 自动检测卡密是否使用
     - 自动检测卡密是否过期废除
4. **多张套餐验证方式：** 支持不同的套餐验证方式，以满足不同用户需求。

5. **系统设置：** 允许管理员灵活设置系统参数，包括用户界面的 HTML、公告内容等。
     - 修改管理员基本信息
     - 修改扫码界面公告（html格式）
     - 修改联系客服链接
     - 修改使用教程链接

6. **用户界面定制：** 提供修改用户界面的 HTML 功能，使管理员能够个性化定制界面。
     - 内置模版
     - 多界面模版切换（下一期）
  
8. **使用教程：** 提供详细的使用教程，帮助用户快速上手系统功能。

9. **联系客服：** 提供联系客服地址，方便用户获取帮助和支持。
    - 设置外链一键引流

## 界面展示
<img width="444" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/958c96bd-085f-45fb-b5e5-38f3b11c8ac0">
<img width="444" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/6ff31ec8-e784-46a1-84f0-73aa5ce847e1">

<img width="1710" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/22eb7294-aba3-4e05-bc3e-f5c0fc92ae63">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/58b23fb1-8a64-49aa-815d-714f7631835b">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/60c9a6d7-d199-4292-a3a5-4feecb1a18fa">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/8ccc9985-1eae-4e17-99ba-d39425c2f5f1">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/4a8882e8-62ba-4c64-9ba2-2d25e6f42a99">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/cebc2f09-19e2-4b09-8a4e-85b7504a5aaa">





## 功能列表
   - 远程扫码登录（pc、pad、phone）✅
   - 配置花联系外链+广告功能 ✅
   - 基础后台功能 ✅
   - 支持多种验证方式 ✅
   - 支持套餐绑定cookie ✅
   - 支持key 绑定套餐 ✅
   - 批量生成卡密 ✅
   - 自动识别是否使用卡 ✅
   - 一键复制卡地址（不需要手动填写域名）✅
   - 批量导入cookie ❌
   - cookie添加分组概念 ❌
   - 按照分组生产批量key ❌
   - 一键批量出卡功能 ❌
   - 前端展示界面模版功能 ❌
    

## 技术栈

- **后端开发：** Java Spring Boot 框架，采用 Token 鉴权实现数据安全。

- **前端框架：** Vue.js，使用路由拦截器实现单点登录，保障数据安全。

- **数据库：** 使用 mysql 数据库存储用户信息和系统配置。

- **安全性：** 采用 Token 鉴权、单点登录等先进的安全技术，确保用户信息的机密性和系统的稳定性。

## 快速开始

1. **项目部署和启动：**
   ```bash
   java -jar BaiduDiskScanQrCodeSystem.jar
   ```
## ⬇️ 本系统为商用版系统，所有功能暂不开源 购买程序！定制开发！ ⬇️
## ⬇️ 本系统为商用版系统，所有功能暂不开源 购买程序！定制开发！ ⬇️
## ⬇️ 本系统为商用版系统，所有功能暂不开源 购买程序！定制开发！ ⬇️
## 联系方式
- 联系邮箱： fifteenyang@qq.com（主题百度网盘扫码）
- 备注（百度网盘扫码系统）
- <img width="200" alt="image" src="https://github.com/zxyyang/BaiduDiskScanQrCodeSystem/assets/50910542/74f0a186-9f91-43b7-920a-a5db99914123">

感谢您的支持和使用！我们致力于提供更优质的百度网盘扫码登录体验。
