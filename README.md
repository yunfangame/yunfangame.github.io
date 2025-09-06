# NavPage-Insiders 导航站点

本项目是基于 [NavPage-Hugo-Theme](https://github.com/PagesX/NavPage-Hugo-Theme) 静态响应式网址导航主题，打造的的**示例版本站点**。

### 安装部署

下载更新，更新子模块。

```
$ git clone https://github.com/PagesX/NavPage-Hugo-Demo.git
$ cd NavPage-Hugo-Demo
$ git submodule update --init --recursive
$ cd themes/NavPage-Hugo-Theme
$ git pull https://github.com/PagesX/NavPage-Hugo-Theme.git
```

### 静态资源

本站点的所有静态资源，包括导航站点 logo 图片等均已开源，详情请参考 [PagesX/NavPage-Assets](https://github.com/PagesX/NavPage-Assets)。

### 发布与修改站点

增删导航站点信息，你可以直接在 GitHub 页面直接在 `data/webstack.yml` 中进行修改，修改完成后通过 GitHub Actions - [HugoAction.yml](https://github.com/PagesX/NavPage-Hugo-Demo/blob/main/.github/workflows/HugoAction.yml) 触发自动构建，生成可以直接部署的静态站点文件 (默认保存在 **`public`** 目录)，并发布到指定的仓库。


本仓库动构建的静态文件自动发布至 GitHub **[NavPage-Hugo-Website](https://github.com/PagesX/NavPage-Hugo-Website)** 仓库的 [main](https://github.com/PagesX/NavPage-Hugo-Website/tree/main) 分支：

- [main](https://github.com/PagesX/NavPage-Hugo-Website/tree/main) 分支部署至 [Netlify](https://app.netlify.com/)，同时绑定 [https://navpage.pagex.top](https://navpage.pagex.top)，**国内访问相对快一些！**
