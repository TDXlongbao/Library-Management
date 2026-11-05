# 拾页 · 图书管理系统

一个轻量的个人图书管理页面，无需安装依赖或启动服务器。用浏览器打开 `index.html` 即可使用。

## 功能

- 添加、编辑和删除图书
- 按书名、作者和分类搜索
- 记录阅读状态、评分和简短笔记
- 查看馆藏总数、正在阅读和已读完数量
- 自动将数据保存在当前浏览器的本地存储中
- 适配手机和电脑屏幕

## 开始使用

下载或克隆项目后，双击 `index.html`，选择浏览器打开即可。书单只保存在当前设备和浏览器中，不会自动同步到其他设备。

## 上传到 GitHub

在 GitHub 新建一个 **Public** 仓库，然后在本项目文件夹打开终端并运行：

```bash
git init
git add .
git commit -m "Add personal book library"
git branch -M main
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```

将最后的仓库地址替换成 GitHub 新建仓库页面提供的地址。
