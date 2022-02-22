---
title: 发帖
date: 9999-12-31 23:59:59
comments: false
---

<div id="page_post_point"></div>
<script>
    document.getElementById('page_post_point').parentElement.parentElement.children[3].style.margin = '0';
    document.getElementById('page_post_point').parentElement.parentElement.children[4].style.display = "none";
    document.getElementById('page_post_point').parentElement.parentElement.children[3].children[1].style.display = "none";
</script>

<!--more-->

<script>
    document.getElementById('page_post_point').parentElement.parentElement.children[4].style = "";
</script>

|<a href="https://gitee.com/kuiba-wiki/kuiba-wiki/new/master/source/_posts"><i class="fab fa-git fa-fw"></i> 在 Gitee 上发帖</a>|<a href="https://github.com/Kuiba-Wiki/Kuiba-Wiki.github.io/new/master/source/_posts"><i class="fab fa-github fa-fw"></i> 在 Github 上发帖</a>|
|-|-|
|暂不支持自动部署，等待[仓库镜像管理](https://gitee.com/help/articles/4336)服务上线。|支持自动部署，基于 Github Actions 服务实现。|
|使用此种方式编辑页面适用于几乎所有大陆地区用户，**使用此种方式请确保拥有一个 Gitee 账号，并保持登录状态。** |使用此种方式编辑页面大陆地区可能存在无法访问的情况，**使用此种方式请确保拥有一个 Github 账号，并保持登录状态。**|
|Gitee 是一个主要面向中国大陆地区用户的代码开源平台，本 Wiki 依赖开源项目 Hexo + Gitee Pages / Github Pages 服务搭建。|Github 是一个面向全球用户的代码开源平台，本 Wiki 依赖开源项目 Hexo + Gitee Pages / Github Pages 服务搭建。|

<style>
    .post-header, .post-footer, .post-edit-link {
        display: none;
    }
</style>