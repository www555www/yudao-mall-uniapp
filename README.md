## 简介

![title](https://file.sheepjs.com/www/preview/dcloud/01.png)

<div align="center">

[![star](https://gitee.com/sheepjs/shopro-uniapp/badge/star.svg)](https://gitee.com/sheepjs/shopro-uniapp.git)
[![fork](https://gitee.com/sheepjs/shopro-uniapp/badge/fork.svg?theme=gvp)](https://gitee.com/sheepjs/shopro-uniapp.git)
[![version](https://img.shields.io/badge/Shopro-V1.5-brightgreen)](https://gitee.com/sheepjs/shopro-uniapp.git)
[![license](http://img.shields.io/badge/license-MIT-orange)](https://gitee.com/sheepjs/shopro-uniapp.git)

[官方网站](https://www.shopro.top/) | [H5 演示](http://shopro.sheepjs.com/) | [管理系统](https://shopro.sheepjs.com/admin/) | [问题反馈](https://gitee.com/sheepjs/shopro-uniapp/issues)

</div>

## 特性

![features](https://file.sheepjs.com/www/preview/dcloud/02.png) 

- **支持主题色+自定义头部导航+自定义底部导航**
- **内含沉浸式头部、通用头部导航示例，支持后端自定义配置底部导航背景和样式**
- **店铺装修组件（轮播、标题栏、优惠券、商品组、宫格导航、列表导航+广告魔方+富文本、搜索栏等众多组件）**
- **内置微信公众号分享 jssdk+微信小程序分享卡片+微信 App 分享+海报分享统一封装**
- **内置微信公众号登录+微信小程序手机号登录+微信 App 开放平台登录+账号密码登录+iOS 登录统一封装**
- **内置余额支付+微信公众号 jssdk 支付+微信小程序支付+微信 App 支付+支付宝网页支付+支付宝 App 支付统一封装**
- **支持第三方 cdn 图片资源地址，并支持阿里云、腾讯云、七牛云图片缩放参数**
- **严格适配多终端场景并支持 App 审核上架**


## 技术栈

- **前端技术栈：uni-app、ES6、Vue3、Vite、Pinia;**
## 安装

```bash
# 1.克隆项目
$ git clone https://gitee.com/sheepjs/shopro-uniapp.git
```

```bash
# 2.拷贝.env.example示例配置文件 重命名为.env
$ cd shopro-uniapp
$ cp .env.example .env 
```

```bash
# 3.安装依赖 (需安装nodejs环境, 使用npm国内镜像)
$ npm install --registry=https://registry.npmmirror.com
```

```bash
# 4.使用HbuilderX 运行...
```

## 体验

![系统架构](https://file.sheepjs.com/www/preview/dcloud/04.png)

客户端演示地址：[https://shopro.sheepjs.com](https://shopro.sheepjs.com)

演示账号: shopro

演示密码: a123456

管理端演示地址：[https://shopro.sheepjs.com/admin/](https://shopro.sheepjs.com/admin/)

演示账号: shopro

演示密码: 123456

_（注意：演示环境已屏蔽管理权限和相关操作）_


## 项目结构

```
├── pages                   // 页面
│      ├── index            // 入口页面
│      ├── user             // 用户相关
│      ├── public           // 公共页面
│      ├── activity         // 活动页面
│      ├── app              // 积分、签到页面
│      ├── chat             // 客服页面
│      ├── commission       // 分销页面
│      ├── coupon           // 优惠券页面
│      ├── goods            // 商品页面
│      ├── order            // 订单页面
│      ├── pay              // 支付页面
├── sheep                   // 底层依赖/工具库
│      ├── api              // 服务端接口
│      ├── components       // 自定义功能组件
│      ├── config           // 配置文件
│      ├── helper           // 助手函数
│      ├── hooks            // vue-hooks
│      ├── libs             // 自定义依赖
│      ├── platform         // 第三方平台登录、分享、支付
│      ├── request          // 请求类库
│      ├── router           // 自定义路由跳转
│      ├── scss             // 主样式库
│      ├── store            // pinia状态管理模块
│      ├── ui               // 自定义UI组件
│      ├── url              // cdn图片地址格式化
│      ├── validate         // 通用验证器
│      ├── index.js         // Shopro入口文件
├── uni_modules             // dcloud第三方插件

```


## 更新

### 近期计划

- [ ] Typescript 重构；

### V1.5 更新简介 2022/12/07

- [x] 服务保障icon 变形问题；
- [x] 确认订单 可用优惠券逻辑修改；
- [x] `su-image`组件中`customStyle`添加`width`属性；

---

**<p align="center">如果您觉得我们的开源项目很有帮助，请点击 :star: Star(https://gitee.com/sheepjs/shopro-uniapp.git) 支持 SheepJS 开源团队:heart:</p>**

---
