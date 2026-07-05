# FlowUs 图床

用于存储 FlowUs 息流笔记中的图片。

## 目录结构

```
image-bed/
├── assets/         # 笔记图片
│   ├── math/       # 数学
│   ├── english/    # 英语
│   └── ...
└── ...
```

## 配合 PicGo 使用

1. 下载安装 PicGo: https://picgo.github.io/PicGo-Doc/
2. 图床设置 → GitHub图床:
   - 仓库: zn5p74r82y-lang/image-bed
   - 分支: main
   - Token: 你的 GitHub PAT
   - 存储路径: assets/
   - 自定义域名: https://raw.githubusercontent.com/zn5p74r82y-lang/image-bed/main
3. 上传快捷键: Ctrl+Shift+E（粘贴后自动上传）
