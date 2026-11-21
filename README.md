# Silent Return

**Silent Return** 是一个 Android 上的 DeepSeek 聊天客户端（个人修改版）。它不接入官方账号体系，直接用你自己的 DeepSeek 开放平台 API Key，会话与设置全部保存在本机。

> 本仓库**只分发 APK**，不包含源码。APK 由 GitHub Actions 构建并签名。
> 这不是 DeepSeek 官方发布，与深度求索公司没有隶属关系。

## 下载

- 最新 APK：见 [Releases](../../releases/latest)
- 或直接下载仓库根目录下的 `SilentReturn-*.apk`

要求：Android 11（API 30）及以上。

## 安装

1. 下载 APK；
2. 点击安装（系统会提示「未查询到 ICP 备案」「未经安全审核」，继续安装即可）；
3. 打开后按引导填入 API Key（DeepSeek 开放平台：<https://platform.deepseek.com/api_keys>）；
4. 开始对话。

升级：直接覆盖安装即可，会话与设置不会丢。

## 功能

| 分类 | 内容 |
|---|---|
| 接入 | 多模型切换、自定义接入点（DeepSeek 官方 / OpenAI 协议 / Anthropic 协议） |
| 用量 | 请求与 Token 统计、按模型计费、导出用量 |
| 会话 | 本地会话历史、置顶、分组（可拖动排序）、多选批量操作、重命名、删除 |
| 交互 | 系统预测性返回（含手势预览）、抽屉滑动、长按菜单、流式输出 |
| 内容 | Markdown / 公式（KaTeX）/ Mermaid / 代码高亮、消息复制与朗读 |
| 隐私 | API Key 存在 Android Keystore；会话、设置、统计存在本机数据库；无自建服务端 |

## 开源协议与使用范围

- **授权协议：GPL-3.0-or-later**（继承上游 `deepseek-app-replica`）。
- **作者声明：本项目仅供个人学习与研究使用，请勿用于商业用途。**
  需要商用授权请联系作者；同时请注意，由于上游为 GPL-3.0，任何分发仍需遵守 GPL-3.0 的条款。
- **源码不随安装包/本仓库分发**，如需对应版本的源代码可开 issue 索取。

## 归属与许可

- 交互与视觉参考 DeepSeek 官方开源示例 [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo)（MIT）。
- 本项目基于开源项目 [LiJiaHua1024/deepseek-app-replica](https://github.com/LiJiaHua1024/deepseek-app-replica)（GPL-3.0-or-later）构建，并做了修改。
- 因此本二进制同样遵循 **GPL-3.0-or-later**。为满足 GPL 的源码要求：**源码不随本仓库分发，但可以按需提供**——如果你需要对应版本的源代码，请开 issue 说明，我会通过其他方式提供。
- 项目内所有商标、标识及版权归其各自所有者。

## 免责声明

本项目仅供个人技术研究与交互学习使用。使用自备 API Key 产生的费用由你自行承担；请遵守 DeepSeek 服务条款与所在地法律法规。
