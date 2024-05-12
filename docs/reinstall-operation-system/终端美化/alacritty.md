---
hide_title: true
---

> 官方网址: https://alacritty.org
> 
> Github: https://github.com/alacritty/alacritty

### 下载地址

> alacritty：https://github.com/alacritty/alacritty/releases

### 配置文件

> 配置文档：https://alacritty.org/config-alacritty.html

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