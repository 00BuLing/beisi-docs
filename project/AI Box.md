# AI Box

## 项目介绍

AI Box 是一个可以集成各种 AI 模型的工具，如 deepseek、通义千问、Kimi 等。

## 项目思路

整合市场上主流 AI 大模型，收取订阅费用。

## 收入与支出

| 收入项   | 支出项        |
| -------- | ------------- |
| 用户付费 | 服务器费用    |
| 广场收入 | 模型 API 费用 |

## 智创空间

在 AI 模型基础上开发的细分领域的 AI 应用，如 AI 生成 PPT、AI 语音转文本

## 项目技术栈

前端使用 flutter 开发，后端使用 node.js 开发。数据库使用 MySQL。

## 加固后签名方法

参考资料：

https://blog.csdn.net/Android_xiong_st/article/details/130853689

https://apkprotect.baidu.com/doc#/apk-sign

命令：

```shell
java -jar apksigner.jar sign --ks aibox.keystore --v3-signing-enabled false --v4-signing-enabled false app.apk
```

## 项目设计

### 1. 主页面 UI：

**核心功能：多模型智能中枢**  
&emsp;&emsp;以"AI Box"为中心设计，顶部突出显示用户当前选择的 AI 模型（如 deepseek/通义千问/Kimi 等）。

<a href="https://postimg.cc/HVm0nspw">
  <img src="https://i.postimg.cc/02MVtbFB/image.webp" alt="image.webp" width="150" />
</a>

### 2. 左侧菜单 UI：

**多维导航中枢**  
采用沉浸式侧边抽屉设计，包含三级功能矩阵：

- 基础功能模块: 新对话/历史记录
- 系统功能区：账户中心与设备管理
- 特色交互：智创空间通过 Webview 无缝对接 H5 生态，支持用户探索社区创作的 AI 角色模板和场景预设。

<a href="https://postimg.cc/8JDKSdnv">
  <img src="https://i.postimg.cc/nz96q043/image.webp" alt="image.webp" width="150" />
</a>

### 3. 设置页面 UI

**个性化智控中心**  
采用垂直列表布局：

- 账户安全/福利活动/语言设置/版本设置/客服设置
- 图标位于文字左侧，便于快速识别功能。

<a href="https://postimg.cc/VJ6C0J2C">
  <img src="https://i.postimg.cc/sgP98Scw/image.webp" alt="image.webp" width="150" />
</a>

### 4. AI 对话页面

**多模态交互工作台**  
核心功能架构：

- 顶部情境栏：实时显示当前模型
- 中部对话区：  
  • 智能显示：支持代码高亮/数学公式渲染  
  • 上下文追溯：可折叠的对话分支管理
- 底部增强输入：  
  • 多模态切换：支持文本/语音/图片输入  
  • 智能建议：动态预测用户意图

<a href="https://postimg.cc/c6BhQ8k9">
  <img src="https://i.postimg.cc/CMW2pGGg/AI.webp" alt="AI.webp" width="150" />
</a>

### 加入 apifox 查看接口

[加入团队 倍司网络科技](https://app.apifox.com/invite?token=fRofJiPuhreDpx2qo9TYN)
