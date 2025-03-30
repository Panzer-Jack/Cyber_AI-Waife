
<div align="center">

<p align="center">
    <img src="https://github.com/Panzer-Jack/Cyber_AI-Waife/assets/81006731/2ca099e3-a42f-4a96-a82e-5ef53a2fd5ba" alt="" width="300px">
</p>

<h1> Cyber AI-Waife（这是一个有灵魂的赛博女朋友）</h1>
    
_✨ 基于 [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) + [VITS-fast-fine-tuning
](https://github.com/Plachtaa/VITS-fast-fine-tuning) + [pixi-live2d-display
](https://github.com/Panzer-Jack/pixi-live2d-display) 以及 [Vue3]() + [Flask]()  实现 ✨_  
    
    
</div>  

<div align="center">
    <div style="width: 400px; display: flex; justify-content: space-evenly;">
        <img src="https://img.shields.io/badge/PyQT5--blue" alt="license">
        <img src="https://img.shields.io/badge/Flask--blue" alt="license">
        <img src="https://img.shields.io/badge/Vue3--blue" alt="license">
        <img src="https://img.shields.io/badge/MySQL--blue" alt="license" >
        <img src="https://img.shields.io/badge/Redis--blue" alt="license">
        <img src="https://img.shields.io/badge/Nginx--blue" alt="license">
    </div>
</div>

<div align="center" style="display: flex; justify-content: space-around;">
    <div style="width: 600px; display: flex; justify-content: space-evenly;">
        <img src="https://img.shields.io/badge/WebSocket--g" alt="license">
        <img src="https://img.shields.io/badge/WebRTC--g" alt="license">
        <img src="https://img.shields.io/badge/JWT--g" alt="license">
        <img src="https://img.shields.io/badge/Restful API--g" alt="license">
        <img src="https://img.shields.io/badge/Flask_mail--g" alt="license">
        <img src="https://img.shields.io/badge/Flask sqlalchemy--g" alt="license">
        <img src="https://img.shields.io/badge/Flask cors--g" alt="license">
    </div>
</div>

<div align="center" style="display: flex; justify-content: space-around;">
    <div style="width: 500px; display: flex; justify-content: space-evenly;">
        <img src="https://img.shields.io/badge/Vuex--g" alt="license">
        <img src="https://img.shields.io/badge/Less--g" alt="license">
        <img src="https://img.shields.io/badge/Element_Plus--g" alt="license">
        <img src="https://img.shields.io/badge/socket.io_client--g" alt="license">
        <img src="https://img.shields.io/badge/vue_router--g" alt="license">
        <img src="https://img.shields.io/badge/qs--g" alt="license">
    </div>
</div>

<div align="center" style="display: flex; justify-content: space-around;">
    <div style="width: 500px; display: flex; justify-content: space-evenly;">
        <img src="https://img.shields.io/badge/ChatGLM--red" alt="license">
        <img src="https://img.shields.io/badge/VITS--red" alt="license">
    </div>
</div>

---
PS：因为之前写的东西有点老了，准备计划重构中。。。

**核心技术栈**：Vue3、Flask、PHP-FPM、VITS、ChatGLM-6B、pixi-live2d-display 、Type.js、MySQL、Redis、Axios、Vuex 、Element-Plus、less、WebSocket、flask-restful、Nginx等

**项目描述**：一个会说话会动的Live2D美少女 AI。项目基于 ChatGLM-6B 开源模型以及 VITS 语音推理模型 为核心, 以 Flask 后端框架为后台，利用PS和Live2D Cubism来设计建模角色，并以Vue3 以及 pixi-live2d-display 为前端核心进行开发。该项目提供2个核心模式：普通模式：和普通的ChatGPT一样进行文字交流。赛博模式：有一个可爱的原创动态·Live2D角色: Huusyako 能与你语音聊天。

**项目亮点**：
- 利用 Flask 部署 算力服务器后端节点。基于 二次元角色语音训练的 VITS语音推理模型 + ChatGLM-6B聊天模型，实现日语语音中文文字的双语对话，并利用Frp公网代理端口映射到公网上，代理到主服务器的Nginx内。
- 为了解决 ChatGLM 无法生成日语文字，利用百度翻译平台的 JSON API 进行中译日 转译。
- 与传统的 web Live2D 的单一显示模式不同，本项目利用 pixi-live2d-display 利用pixi.js将自己绘制建模的Live2D模型展现在Vue3 Canvas组件上，可以自定义设置动画更新事件和动作触发事件来控制角色的动作。
- 基于 WebSocket 来进行ChatGLM文字对话通信，并利用type.js将AI对话动态模拟真人打字打入页面。
- 为了解决游览器缓存问题 利用Axios基于时间戳来实时获取 Flask + soundfile 生成最新的AI语音。
- 利用 Vuex + Axios 拦截请求 与 Flask 基于 JWT 标准 进行 HTTP 安全授权通信，并基于 Vuex 和 localstorage 来全局存储登录状态利用 vue-router 来实现权限路由权限检测
- 利用 flask-mail 和 Redis 实现用户邮件验证码注册功能，利用MD5 + MySQL 存储用户注册信息
- 基于 Vue 组件化开发，利用 Element-Plus + vue-router 实现控制台页面布局

**上线地址**：http://cyber-ai-waife.panzer-jack.cn/    ( 开发完善中ing )

**视频演示**：https://www.bilibili.com/video/BV1Pw411z7mZ/

---

## 简介

还有2天 520 了（恼）<br />
是不是你已经再也无法忍受，每年到这个时间点，满朋友圈的狗粮 <br />
是不是你已经再也无法忍受，每年到这个时间点，别人与女朋友聊嗨到深夜，而你只能默默的打开电脑，通过看小说和galgame来打发时间 <br />
是不是。。。呸！md 三次元有什么好的！（ <br />

<img src="https://github.com/Panzer-Jack/Cyber_AI-Waife/assets/81006731/ac80edfa-c681-4f01-a59e-48b5804ff253" height=500>

Cyber AI-Waife 包含了一下两个核心组成部分：

<img src="https://pic2.imgdb.cn/item/6466012e0d2dde57773f4754.jpg" height=300>

1. 普通模式：和普通的ChatGPT一样进行文字交流
2. 赛博模式：有一个可爱的原创Live2D角色: [Huusyako](https://www.panzer-jack.cn/2021/09/13/Live2D%E5%A4%84%E5%A5%B3%E4%BD%9C-%E9%A3%8E%E8%BD%A6%E5%AD%90/) 能与你语音聊天。


## 角色设定

风车子 ( Huusyako ): 一个可爱又傲娇的18岁日本高中生。


## 项目组成部分：
1. Vue3 前端
2. Flask 服务端
3. ChatGLM + Flask 算力端


## 开发部署

```

```

## 预览
### 控制台
<img src="https://pic2.imgdb.cn/item/64660a770d2dde577749fcd9.jpg">

### 普通模式
<img src="https://pic2.imgdb.cn/item/64660ae60d2dde57774a71f4.jpg">

### 赛博模式
看起来是不是非常有 可爱的 赛博女友 的味道（喜）
<img src="https://pic2.imgdb.cn/item/64660a770d2dde577749fc00.jpg">

### 注册
<img src="https://pic2.imgdb.cn/item/64660a760d2dde577749fbc9.jpg">

### 登录
<img src="https://pic2.imgdb.cn/item/64660a760d2dde577749fb9c.jpg">

### 主页面
<img src="https://pic2.imgdb.cn/item/64660a770d2dde577749fd1b.jpg">

## 相关连接：
1. QQ 群聊美少女语音AI（ChatGPT 版本）：[ChatGPT_VITS_For_QQ-Rob](https://github.com/Panzer-Jack/ChatGPT_VITS_For_QQ-Rob)
2. QQ 群聊美少女语音AI（ChatGLM 本地化版本）：[ChatGLM_VITS_For_QQ-Rob](https://github.com/Panzer-Jack/ChatGLM_VITS_For_QQ-Rob) 

## 总结
Cyber AI-Waife 这个项目本身也是受到了 一部叫做《命运石之门0》的动漫的影响，突然让我灵感而发。。加上近期流行的ChatGPT 热潮让我总想发我自我做一下 有趣的 (无用的) 开源小发明（小垃圾）。嘛，兴趣是最好的动力，特别是那些有趣的小东西，总是能让人废寝忘食。
