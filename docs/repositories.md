# 公开仓库关系

这里按用途整理公开仓库。多个仓库有时是同一项目的当前主线、稳定保留线、开发工作区或下载入口，不能按仓库数量理解成同样数量的独立产品。

## 当前工具与作品

| 项目 | 入口 | 仓库分工 |
| --- | --- | --- |
| grokbot-lite | [源码与发布](https://github.com/h1neolzr7f/grokbot-lite) | 让 Grok Bot 远程执行在无图形界面 Linux 服务器上运行，后台约 190 MB，一键安装 |
| Nai学长工作室 | [当前 Windows 主线](https://github.com/h1neolzr7f/NaiXueZhang-Studio-Upgrade) | 本地图库与生成任务工作台；源码、文档和 Windows Release 在同一仓库维护 |
| 丁真笔记本 | [桌面 / Android 源码与发布](https://github.com/h1neolzr7f/dingzhen-notebook) | 已完成试卷的采集、OCR、人工校对与复习；桌面截图使用合成回归数据 |
| Manga-NAI-GPT | [当前主线](https://github.com/h1neolzr7f/Manga-NAI-GPT) | 一个故事变成漫画：故事模式自动分镜、出图、嵌字成整章，另有换角色、改字幕、去字、分层；基于 Manga Editor Desu 的个人 fork，独立维护 |
| manga-nai-editor | [实验线](https://github.com/h1neolzr7f/manga-nai-editor) | NAI V5 整页直出、原生中文气泡、分格局部重绘等实验；正式版本以 Manga-NAI-GPT 为准 |
| Manga Editor Desu · NAI（历史 / NovelAI 线） | [历史仓](https://github.com/h1neolzr7f/Manga-Editor-Desu-NAI) | 上游 manga-editor-desu 的 NovelAI 改版与旧 Windows 发行；新功能优先在 Manga-NAI-GPT |
| yizi | [源码](https://github.com/h1neolzr7f/yizi) | 针对已有漫画页面的本地中文编剧辅助工具，不生成新的页面图片 |
| 樱夜·尸潮 | [玩家仓](https://github.com/h1neolzr7f/sakurayo-zombietide) · [开发仓](https://github.com/h1neolzr7f/sakurayo-v46-handoff) | 玩家仓提供下载与使用说明；开发仓保存代码基线和维护材料，两者不是两个独立游戏 |
| 边缘图阁 GalleryEdge | [源码与发布](https://github.com/h1neolzr7f/GalleryEdge) | 作品索引 + 图形化运维面板；仓库只含合成演示数据 |
| astrbot-plugin-nai5-mutsumi | [源码](https://github.com/h1neolzr7f/astrbot-plugin-nai5-mutsumi) | AstrBot 插件：NAI5 出图 / 反推，需自备 AstrBot 与 NovelAI 令牌 |
| 智慧工地识别 | [源码](https://github.com/h1neolzr7f/smart-site-safety) | YOLO / Streamlit 演示项目；样例推理与历史训练指标分开说明 |
| 体育馆预约 | [源码](https://github.com/h1neolzr7f/campus-sport) | Spring Boot / Vue 课程工程；数据库和启动前置以项目 README 为准 |
| 学生管理 | [源码](https://github.com/h1neolzr7f/student-manager) | Java Swing / JDBC 课程实验 |

## 手机端与版本保留线

| 仓库 | 状态 |
| --- | --- |
| [NaiXueZhang-Phone](https://github.com/h1neolzr7f/NaiXueZhang-Phone) | Android 独立版公开源码。支持范围、签名和构建验证以该仓库说明为准 |
| [NaiXueZhang-Phone-APK](https://github.com/h1neolzr7f/NaiXueZhang-Phone-APK) | APK 下载入口，不是另一套源码或独立项目 |
| [NaiXueZhang-Studio](https://github.com/h1neolzr7f/NaiXueZhang-Studio) | Windows v1.4 稳定保留线；新开发在 Upgrade 仓库 |

## 已归档

| 仓库 | 迁移入口 |
| --- | --- |
| [NaiXueZhang-Studio-Dev](https://github.com/h1neolzr7f/NaiXueZhang-Studio-Dev) | 历史开发快照；迁移到 [NaiXueZhang-Studio-Upgrade](https://github.com/h1neolzr7f/NaiXueZhang-Studio-Upgrade) |

## 索引仓库

- [dev-portfolio](https://github.com/h1neolzr7f/dev-portfolio) 汇总代表项目和课程工程。
- [h1neolzr7f](https://github.com/h1neolzr7f/h1neolzr7f) 是 GitHub 个人主页仓库。

私有开发底稿、草稿和内部网站不列在公开作品集中；原样 fork 的他人仓库（没有我自己的改动）也不列在这里。需要反馈时，请在对应的当前主线仓库提交可复现问题，并删除日志中的账号、令牌、私人图片和本机路径。
