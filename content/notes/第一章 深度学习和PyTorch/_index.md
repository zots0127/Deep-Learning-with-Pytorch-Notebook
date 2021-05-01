---
# Title, summary, and page position.
linktitle: 第一章 深度学习和PyTorch库
summary: 本章我们会接触并了解到什么是PyTorch。并且会介绍它到底解决了什么问题，同时还会介绍PyTorch与其他深度学习框架之间的关系。
weight: 1
icon: book
icon_pack: fas

# Page metadata.
title: 第一章 深度学习和PyTorch库
date: "2021-05-01T00:00:00Z"
type: book  # Do not modify.
---

## 内容简介

本章内容主要包括

* **深度学习改变了我们对机器学习的看法**
* **了解为什么应该用PyTorch进行深度学习**
* **介绍一个具体的深度学习项目**
* **实例中你可能用到的硬件**

The `courses` folder may be renamed. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## Delete courses

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
