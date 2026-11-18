# Git

`D:\Git` 的仓库起点 —— 一个干净的空项目骨架，用来放后续的代码与文档。

## 结构

```
.
├── README.md        # 本文件
├── .gitignore       # 忽略规则（按需增补语言相关条目）
└── .gitattributes   # 行尾与二进制文件规范
```

## 开始使用

```bash
# 放好文件后
git add .
git commit -m "描述这次改动"
git push
```

## 约定

- 默认分支为 `main`。
- 行尾由 `.gitattributes` 统一：仓库内一律 LF，工作区按平台自动转换。
- 密钥、令牌、本地环境配置不要提交，已在 `.gitignore` 中排除。
