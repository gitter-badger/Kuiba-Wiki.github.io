---
title: 快速开始
date: 9999-12-31 23:59:59
comments: false
---

<div id="page_start_point"></div>
<script>
    document.getElementById('page_start_point').parentElement.parentElement.children[3].style.margin = '0';
    document.getElementById('page_start_point').parentElement.parentElement.children[3].children[1].style.display = "none";
</script>

此页将快速地教会你在站内发表/编辑文章。

<!--more-->

# 新手教程

此教程适用于没有计算机编程经验的用户，此教程可以简便操作流程。但如果你有一定的计算机编程经验我推荐你使用下方的[高级教程](#高级教程)。

## 发表文章

1. 进入站点首页，点击文章顶部发帖链接。如图: ![发表文章 步骤一](111.png)
1. 进入发帖页面，点击 Gitee 或 Github 链接。如图: ![发表文章 步骤二](112.png)
1. 进入托管平台，如图所示操作:
    1. Gitee: ![发表文章 步骤三](1131.png)
    1. Github: 如果为首次发表，需 Fork 本仓库后方可继续操作 ![发表文章 步骤三](1132.png) ![发表文章 步骤三](1133.png) ![发表文章 步骤三](1134.png) ![发表文章 步骤三](1135.png)
    1. 示例:
    ```txt 文件名称
    蛮吉.md
    ```
    ```md 文本内容
    ---
    title: 蛮吉
    categories:
    - 人物
    ---

    蛮吉是第六代魁拔...

    <!--more-->

    # 人物生平
    ...

    ```
    ```txt 提交信息
    发表《蛮吉》
    ```
    ```txt 扩展信息
    发表人物介绍文章《蛮吉》。
    ```
1. 等待仓库管理员审核:
    1. Gitee: ![发表文章 步骤四](1141.png)
    1. Github: ![发表文章 步骤四](1142.png)

## 编辑文章

基本流程与发表文章类似，入口是文章页右上角的钢笔图标。详细教程待更。

# 高级教程

详细教程待更。

<style>
    .post-footer, .post-edit-link {
        display: none;
    }
</style>