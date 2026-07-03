# Liu Jun Personal Academic Website

这是一个可部署到 GitHub Pages 的个人学术/技术风格双语静态网页，使用纯 HTML、CSS 和 JavaScript 构建。

## 文件结构

```text
.
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── profile.jpg
│   └── project-video.mp4
└── README.md
```

## 本地预览

方式一：直接双击 `index.html` 在浏览器中打开。

方式二：使用本地静态服务器预览：

```bash
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## 替换图片和视频

- 个人照片：替换 `assets/profile.jpg`
- 项目视频：替换 `assets/project-video.mp4`

保持文件名和路径不变，网页会自动引用新的资源。

## 部署到 GitHub Pages

1. 新建一个 GitHub 仓库，例如 `personal-website`。
2. 将本文件夹中的 `index.html`、`style.css`、`script.js`、`assets/` 和 `README.md` 上传到仓库根目录。
3. 在 GitHub 仓库页面进入 `Settings`。
4. 打开 `Pages`。
5. 在 `Build and deployment` 中选择 `Deploy from a branch`。
6. Branch 选择 `main`，目录选择 `/root`，点击保存。
7. 等待 GitHub Pages 构建完成后，即可访问生成的网址。

## 内容说明

页面内容根据当前文件夹中的 `CV-LiuJun.pdf` 整理生成，并已排除成绩信息。
