# Scoop RunningCheese Bucket

[![Scoop Bucket](https://img.shields.io/badge/Scoop-Bucket-blue.svg)](https://scoop.sh)

奔跑中的奶酪（RunningCheese）定制版便携浏览器 Scoop Bucket。

## 📦 包含的应用

- **RunningCheese Chrome** (`runningcheesechrome`) - RunningCheese Chrome 定制版便携浏览器
- **RunningCheese Firefox** (`runningcheesefirefox`) - RunningCheese Firefox 定制版便携浏览器
- **RunningCheese Zen** (`runningcheesezen`) - RunningCheese Zen 定制版便携浏览器

## 🚀 安装方法

### 1. 添加 Bucket

```pwsh
scoop bucket add runningcheese https://github.com/TuringRiff/scoop-runningcheese
```

### 2. 安装浏览器

```pwsh
# 安装 Chrome 定制版
scoop install runningcheese/runningcheesechrome

# 安装 Firefox 定制版
scoop install runningcheese/runningcheesefirefox

# 安装 Zen 定制版
scoop install runningcheese/runningcheesezen
```

## 🔄 更新方法

```pwsh
scoop update runningcheesechrome
scoop update runningcheesefirefox
scoop update runningcheesezen
```

> **提示**：更新时 Scoop 会自动保持并迁移用户配置（Profiles / Data / Tools），无需手动备份。
