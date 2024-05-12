---
hide_title: true
---

### 下载地址

> nushell：https://github.com/nushell/nushell/releases

使用 winget 快速安装



### 配置文件

> 官方配置：https://alacritty.org/config-alacritty.html

在指定路径新建配置文件（文件编码需要修改为 UTF-8）

```shell
$PSDefaultParameterValues['Out-File:Encoding']='utf8'
mkdir $env:APPDATA/alacritty
echo "" | Out-File $env:APPDATA/alacritty/alacritty.toml
```

### 主题美化

> 配色方案：https://github.com/alacritty/alacritty-theme

### 个人配置

```toml

```