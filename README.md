# Awesome-Dify-Workflow

<p align="center">
  <a href="./README_EN.md"><img alt="README in English" src="https://img.shields.io/badge/English-d9d9d9"></a>
  <a href="./README.md"><img alt="简体中文版自述文件" src="https://img.shields.io/badge/简体中文-d9d9d9"></a>
</p>

分享一些好用的 Dify 工作流程，自用、学习两相宜，请使用 Dify 0.6.14 及以上版本导入。

所有的 Workflow 基本都可以 **免费** 使用，不需要对接第三方平台 API，模型使用 Deepseek，主要是因为便宜，注册即送 500 万 Token。

更多 Workflow 收集整理中……

## 参考截图
所有 DSL 都为工作流模式，可以方便的发布为工具后，嵌入 ChatBot 流程。工作流会包含基础的输入、条件判断、变量聚合器、输出等内容。

![snap](./snapshots/Xnip2024-07-16_16-58-05.jpg)


# DSL 目录

你可以参考下面每个 yml 的描述，找到你需要的 Workflow，然后在 DSL 文件夹中找到对应的文件，复制文件的 URL，导入自己的 Dify 账号即可。

## 翻译
- **中译英.yml** 通过宝玉的 Prompt，直译->反思->意译，将中文翻译成高质量的英文。
- **DuckDuckGo 翻译+LLM 二次翻译.yml** 与三步翻译类似，但是把第一步的直译变成传统翻译引擎翻译，节省 Token，提高翻译效率，同时提高翻译质量。
- **translation_workflow.yml** 使用吴恩达提出 Agentic Workflow 制作的翻译工具，录入`输入语言`、`目标语言`、`国家`、`原始文本` 4 个参数，提供更细致的翻译结果，按照[translation-agent](https://github.com/andrewyng/translation-agent) 原版提示词制作，一字未改。

## 工具
- **SEO Slug Generator.yml** 给自己的博文生成 url slug，参考来源于宝玉的 twitter

## 代码
- **Python Coding Prompt.yml** 通过聊天对话方式生成 Python 代码，Prompt 来自 [Sonnet 3.5 for Coding 😍 - System Prompt](https://www.reddit.com/r/ClaudeAI/comments/1dwra38/sonnet_35_for_coding_system_prompt/)


# 使用方法
注册 [Dify](https://cloud.dify.ai/) 账号，添加 Deepseek 模型。

![snap](./snapshots/Xnip2024-07-16_13-17-53.jpg)

![snap](./snapshots/Xnip2024-07-16_13-17-10.jpg)

复制 Workflow 的 URL，导入 DLS 文件即可，发布你自己的 Workflow，既可以使用。当然，你可以进行必要的调整，例如模版的调整，或提示词的调整。

![snap](./snapshots/Xnip2024-07-16_13-15-39.jpg)

![snap](./snapshots/Xnip2024-07-16_12-45-29.jpg)

![snap](./snapshots/Xnip2024-07-16_12-45-37.jpg)









