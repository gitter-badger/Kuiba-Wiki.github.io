---
title: 编辑
---
<div id="page_edit_point">
<script>
    var path;
    try {
        path = document.URL.split('://')[1].split(document.domain)[1].split('/edit/?')[1];
    } catch(e) {}
    if(path == undefined) {
        document.getElementById('page_edit_point').parentElement.parentElement.parentElement.style.display = 'none';
    }
</script>

<!--more-->

|<a href="javascript:;" onclick="gitee()"><i class="fab fa-git fa-fw"></i> 在 Gitee 上编辑</a>|<a href="javascript:;" onclick="github()"><i class="fab fa-github fa-fw"></i> 在 Github 上编辑</a>|
|-|-|
|暂不支持自动部署，等待[仓库镜像管理](https://gitee.com/help/articles/4336)服务上线。|支持自动部署，基于 Github Actions 服务实现。|
|使用此种方式编辑页面适用于几乎所有大陆地区用户，**使用此种方式请确保拥有一个 Gitee 账号，并保持登录状态。** |使用此种方式编辑页面大陆地区可能存在无法访问的情况，**使用此种方式请确保拥有一个 Github 账号，并保持登录状态。**|
|Gitee 是一个主要面向中国大陆地区用户的代码开源平台，本 Wiki 依赖开源项目 Hexo + Gitee Pages / Github Pages 服务搭建。|Github 是一个面向全球用户的代码开源平台，本 Wiki 依赖开源项目 Hexo + Gitee Pages / Github Pages 服务搭建。|

<script>
    if(path == undefined) {
        window.location.href = '/';
    }
    function gitee() {
        window.location.href = 'https://gitee.com/kuiba-wiki/kuiba-wiki/edit/master/source/' + path;
    }
    function github() {
        window.location.href = 'https://github.com/Kuiba-Wiki/Kuiba-Wiki.github.io/edit/master/source/' + path;
    }
</script>

<style>
    .post-header, .post-footer, .post-edit-link {
        display: none;
    }
</style>