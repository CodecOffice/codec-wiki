---
hide_title: true
---

> starship：https://starship.rs/
> 
> starship：https://github.com/starship/starship

### 下载地址

> starship：https://github.com/starship/starship/releases

### 配置文件

```shell
$PSDefaultParameterValues['Out-File:Encoding'] = 'utf8'
mkdir -p ~/.config
echo "" | Out-File ~/.config/starship.toml
```

### 主题美化

```shell
starship preset tokyo-night -o ~/.config/starship.toml
```

### 集成 nushell

在环境文件的最后（%APPDATA%）添加以下内容：

```shell
mkdir ~/.cache/starship
starship init nu | save -f ~/.cache/starship/init.nu
```

在您的配置文件的最后（%APPDATA%）加以下内容：

```shell
use ~/.cache/starship/init.nu
```

### 个人配置