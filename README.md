[English](#en) | [中文](#zh)

---

<a id="en"></a>
# Obsidian Video Assistant

## Overview

Obsidian Video Assistant is a plugin designed for video-based learning and note-taking. It is primarily useful for:

1. Language learning through videos  
2. Taking structured notes while watching videos  

This plugin must be used together with a YouTube subtitle extraction tool.

Recommended tools:

- Obsidian Web Clipper (Chrome extension, better performance)  
- yTranscript plugin (alternative)  

---

## Workflow

### 1. Capture Video and Subtitles

Use Web Clipper or other tools to save a YouTube video along with timestamped subtitles into an Obsidian note.

### 2. Enable Shadowing Mode

Open the note and click the Shadowing Mode icon in the ribbon.

In this mode:

- Subtitles scroll automatically with video playback  
- Clicking a timestamp jumps to the corresponding moment in the video  
- Buttons below the video allow skipping forward or backward by 5–10 seconds  

---

## Subtitle Features

Each subtitle block supports:

- Translation  
- Grammar analysis  

To enable these features:

- Configure a large language model in plugin settings  
- Currently tested languages: Chinese, English, French  

Note: Grammar analysis may be slow depending on the model. If a timeout occurs, retry usually works.

---

## Highlighting and Notes

In Shadowing Mode:

- Select any subtitle text  
- A highlight toolbar will appear  
- Choosing a colour automatically creates a video note  

Additional details:

- If notes already exist for the video, the existing note will be opened  
- Click the Highlight Note button in the ribbon to open notes in the right sidebar  
- Note storage location can be configured in settings  

Note behaviour:

- Each highlight includes the original timestamp  
- Highlights with the same timestamp are automatically grouped  

Important recommendation:

If you plan to finish a video over multiple sessions, do not rename the note until completion. Renaming may lead to duplicate note creation.

---

## Installation

1. Go to the plugins folder in your Obsidian vault  
2. Create a folder named `video assistant`  
3. Download and place the following files into the folder:  
   - main.js  
   - manifest.json  
   - styles.css  
4. Open Obsidian → Community Plugins  
5. Locate Video Assistant  
6. Configure your LLM (if translation/grammar features are needed)  
7. Enable the plugin  

---

<a id="zh"></a>
# 中文

## 简介

Obsidian Video Assistant 是一个用于视频学习与笔记记录的插件，主要适用于：

1. 通过视频进行语言学习  
2. 观看视频的同时记录结构化笔记  

该插件需配合 YouTube 字幕下载工具使用。

推荐工具：

- Obsidian Web Clipper（Chrome 扩展，效果更佳）  
- yTranscript 插件（备选）  

---

## 使用流程

### 1. 获取视频与字幕

使用 Web Clipper 或其他工具，将 YouTube 视频及其带时间戳的字幕保存为 Obsidian 笔记。

### 2. 启用 Shadowing Mode

打开笔记后，点击 Ribbon 中的 Shadowing Mode 图标。

该模式下：

- 字幕会随视频播放自动滚动  
- 点击字幕时间戳可跳转至对应视频位置  
- 视频下方提供前进或后退 5–10 秒按钮  

---

## 字幕功能

每个字幕块支持：

- 翻译  
- 语法解析  

如需使用上述功能：

- 需在插件 Settings 中配置大模型  
- 当前测试支持：中文、英文、法文  

说明：语法解析速度可能较慢，取决于模型性能。如出现 timed out，可重试。

---

## 高亮与笔记

在 Shadowing Mode 下：

- 选中任意字幕文本  
- 会弹出高亮工具栏  
- 选择任意颜色后，会自动创建视频笔记  

补充说明：

- 若该视频已有笔记，则会直接打开已有笔记  
- 点击 Ribbon 中的 Highlight Note 可在右侧 Sidebar 打开笔记  
- 笔记保存路径可在 Settings 中配置  

笔记特性：

- 每条高亮笔记包含原字幕时间戳  
- 相同时间戳的高亮内容会自动聚合  

重要建议：

如果一个视频分多次观看，在完全结束之前不要修改笔记名称，否则可能导致重复创建笔记。

---

## 安装方式

1. 进入 Obsidian Vault 的 plugins 文件夹  
2. 新建文件夹 `video assistant`  
3. 下载并放入以下文件：  
   - main.js  
   - manifest.json  
   - styles.css  
4. 打开 Obsidian → Community Plugins  
5. 找到 Video Assistant  
6. 配置大模型（如需翻译与语法功能）  
7. 启用插件  
