---
title: "SpaceVim lang#vim 模块"
description: "这一模块为 SpaceVim 提供了 Vimscript 的开发支持，包括代码补全、语法检查、代码格式化等特性。"
lang: zh
---

# [可用模块](../../) >> lang#vim

<!-- vim-markdown-toc GFM -->

- [模块简介](#模块简介)
- [启用模块](#启用模块)
- [模块选项](#模块选项)
- [快捷键](#快捷键)

<!-- vim-markdown-toc -->

## 模块简介

这一模块为 SpaceVim 提供了 Vimscript 的开发支持，包括代码补全、语法检查、代码格式化等特性。

## 启用模块

可通过在配置文件内加入如下配置来启用该模块：

```toml
[[layers]]
  name = "lang#vim"
```

## 模块选项

- `auto_generate_doc`: 保存 vim 脚本文件时，自动生成对应的帮助文档，这一功能依赖外部命令 [vimdoc](https://github.com/google/vimdoc)。

## 快捷键

| 快捷键    | 功能描述                 |
| --------- | ------------------------ |
| `SPC l e` | 打印光标下函数值         |
| `SPC l v` | 打印光标下函数的版本信息 |
