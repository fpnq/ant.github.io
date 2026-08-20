# Ant / Notes

一个用于记录乒乓球训练、模型和心得的静态站点。

## 发布到 GitHub Pages

1. 将本目录中的全部文件上传到 `fpnq/ant.github.io` 仓库。
2. 在仓库的 `Settings → Pages` 中，将发布来源设为 `GitHub Actions`。
3. 等待 Actions 完成后访问：`https://fpnq.github.io/ant.github.io/`。

如果希望使用根地址 `https://fpnq.github.io/`，需要把仓库重命名为 `fpnq.github.io`，并同步修改首页底部的仓库链接。

## 添加内容

- 文章：复制 `notes/` 中的 HTML 文件，修改标题和正文。
- 图片：放入 `assets/`，再在文章中使用相对路径引用。
- 样式：统一修改 `assets/style.css`。
