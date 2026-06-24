# igweekindex

Gweek 的纯静态个人主页，无需构建工具，直接部署目录即可。

## 项目结构

```text
├── index.html
├── ads.txt
└── assets/
    ├── fonts/
    │   └── DancingScript-VariableFont_wght.ttf
    └── images/
        ├── avatar-240.jpg
        ├── avatar.jpg
        └── favicon.webp
```

## 本地预览

```bash
python3 -m http.server 4173
```

然后访问 `http://127.0.0.1:4173/`。

## 部署

这是纯静态页面，可直接部署到 GitHub Pages、Cloudflare Pages、Netlify 或任意静态文件服务器。
