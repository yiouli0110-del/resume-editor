# 简历工坊 Resume Editor

一个隐私优先、无需登录的在线简历编辑器。所有简历数据默认保存在用户自己的浏览器中。

## 功能

- 直接点击简历文字进行编辑
- 调整字体、字号、行距和段落间距
- 使用 LocalStorage 自动保存
- JSON 备份与恢复
- 导出 A4 PDF
- 支持桌面端和移动端

## 在线使用

打开 `index.html` 即可本地使用，无需安装依赖或运行构建命令。

## 部署到 GitHub Pages

1. 创建一个公开 GitHub 仓库。
2. 将本文件、`.gitignore` 和 `index.html` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 选择 `main` 分支和 `/ (root)` 目录，然后保存。

部署完成后，网站地址通常为：

```text
https://你的GitHub用户名.github.io/仓库名称/
```

## 隐私说明

简历内容存储在访问者当前浏览器的 LocalStorage 中，不会自动上传到服务器。清除浏览器数据可能删除本地简历，请使用“备份”功能定期导出 JSON 文件。

## 技术栈

HTML、CSS、JavaScript、LocalStorage、浏览器打印/PDF。

