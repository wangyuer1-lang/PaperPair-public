# PaperPair 使用方式

[返回项目介绍](../README.md)

本文介绍已有预览版本的操作方式。公开安装包下载尚未开放，发布信息请查看[项目介绍](../README.md)或 [koko 的爱发电主页](https://afdian.com/a/paperpair)。

## 1. 导入论文

打开 PaperPair，点击 **Import PDF**。优先选择能够选中、复制文字的 PDF。软件创建本地阅读副本，保留原文件。

使用 Zotero 插件时，也可以从论文附件的 **Open in PaperPair** 命令进入。插件需要与操作系统及 PaperPair 版本匹配。

## 2. 选择语言与翻译方式

在 **Reading Agent** 中用 **Translate into** 选择目标语言，**Set default** 可记住新论文的默认语言。阅读指令仍可以修改。

**本地 Agent 路线：** 点击 **Copy Prompt**，将复制的完整任务交给具备本机文件访问能力的 Agent。让它完成翻译、逐行对齐、阅读检查和结果回填。无需在 PaperPair 里填写 API Key。复制按钮本身不会启动翻译；以软件实际接收结果为完成依据。

**API 路线：** 在 **API Settings** 输入 OpenAI 兼容接口、模型名称和自己的 API Key，再点击 **Run Instruction**。接口费用按所选服务商规则计算。

## 3. 调整阅读

- **By sentence / By paragraph**：按完整句子或段落组织，二者都保留一行译文、一行原文的对照。
- **Line order**：切换译文在上或原文在上。
- **Contents**：点击章节跳转，拖动分隔线调整目录宽度。
- **Theme**：切换阅读主题。
- **Reading Layout**：调整字号、行距、段落间距和阅读宽度。
- 需要修正时，选择对应的译文行进行修改。

## 4. 核对与保存

用 **Original Pages** 核对原稿，尤其注意复杂双栏、公式、特殊符号和图文混排。修改排版后，重新生成 **PDF Preview** 查看实际导出效果。

返回 **Bookshelf** 可以保存并继续阅读。**Save a Copy** 保存便携的 `.paperpair` 副本；**Export PDF** 导出新的双语阅读 PDF。使用 Zotero 时，**Save to Zotero** 将结果保存为新的附件。

当前未集成扫描 PDF 的 OCR，也不支持 Word 导入。图片内文字不会自动逐字翻译。重要术语、数值与结论仍应结合原文核对。
