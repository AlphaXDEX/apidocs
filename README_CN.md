# API 文档项目

## 项目介绍

这是官方 API 文档项目。本 README 将介绍该项目的整体结构以及如何进行维护和修改。


### **推荐的 CI 修改方式**

* 只需要在指定分支中修改 `./source/index.html.md` 并提交代码，后续两个步骤将由 CI 自动完成。


### 修改某个指定版本的文档

1. 切换到目标版本对应的分支
   例如：如果你要更新 v1 的中文文档，请切换到 `v1_cn` 分支

2. 在该分支中修改 `source/index.html.md` 并提交

3. 运行 `deploy.sh` 脚本，将修改部署到网站

4. 在网页上确认效果无误后，推送代码


### 修改公共文件（Logo、样式、布局等）

1. 切换到 `master` 分支

2. 修改公共文件

3. 提交并推送代码

4. 依次切换到各个版本分支，进行 merge 或 cherry-pick，然后运行 `deploy.sh`


## 修改说明

修改主要分为两大类：**外观修改** 和 **内容修改**。

### 外观修改

* 修改 Logo：
  [https://github.com/lord/slate/wiki/Changing-the-Logo](https://github.com/lord/slate/wiki/Changing-the-Logo)

* 自定义样式：
  [https://github.com/lord/slate/wiki/Custom-Slate-Themes](https://github.com/lord/slate/wiki/Custom-Slate-Themes)


### 内容修改

* 修改文档内容（Markdown 语法）：
  [https://github.com/lord/slate/wiki/Markdown-Syntax](https://github.com/lord/slate/wiki/Markdown-Syntax)


## 构建与部署 API 文档

### 本地搭建 Slate 构建与部署环境

[https://github.com/lord/slate/wiki/Installing-Slate](https://github.com/lord/slate/wiki/Installing-Slate)


### 发布 API 文档

[https://github.com/lord/slate/wiki/Deploying-Slate](https://github.com/lord/slate/wiki/Deploying-Slate)
