# 爱心弹窗网页

一个可直接部署到静态网站的单文件页面项目。

## 文件说明

- `index.html`：页面入口文件，可直接用于 GitHub Pages、Netlify、Vercel 等静态托管平台。

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages

先在 GitHub 上新建一个空仓库，然后在项目目录执行下面的命令：

```powershell
git init
git branch -M main
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```

推送完成后，到 GitHub 仓库页面开启 Pages：

1. 打开 `Settings`
2. 打开 `Pages`
3. `Source` 选择 `Deploy from a branch`
4. `Branch` 选择 `main` 和 `/ (root)`
5. 保存

发布成功后，访问地址通常是：

```text
https://你的用户名.github.io/你的仓库名/
```

## 备注

如果本机还没有安装 Git，需要先安装 Git for Windows，并确保 `git` 命令可在终端中使用。
