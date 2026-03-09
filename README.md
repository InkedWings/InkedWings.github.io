# Personal Academic Website (GitHub Pages)

这个仓库已经是一个可直接部署的静态个人主页。

## 1) 修改你的信息

编辑以下文件：

- `index.html`：姓名、学校、研究方向、论文、联系方式、GitHub 链接
- `styles.css`：颜色、字体、页面风格
- 直接新增 `assets/profile.jpg`（或 `assets/profile.png`），页面会自动显示你的照片

## 2) 推送到 GitHub

```bash
git init
git add .
git commit -m "Init personal webpage"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

## 3) 开启 GitHub Pages

在 GitHub 仓库：

1. 打开 `Settings` -> `Pages`
2. `Build and deployment` 选择 `Deploy from a branch`
3. 分支选 `main`，目录选 `/ (root)`，保存

## 4) 访问地址

- 如果仓库名是 `<your-username>.github.io`，地址是：  
  `https://<your-username>.github.io/`
- 如果是普通仓库名（例如 `personal_webpage`），地址是：  
  `https://<your-username>.github.io/<your-repo>/`
