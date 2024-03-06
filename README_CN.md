## 分支说明

main: 自用默认分支
master: 同步上游分支


## 安装
如果目标目录已存在 需要先删除或者重命令

```sh
git clone https://github.com/anaer/kickstart.nvim.git %userprofile%\AppData\Local\nvim\
```


## 安装msys2, C编译环境
https://github.com/msys2/msys2-installer/releases

```
aria2c --check-certificate=false --max-connection-per-server=5 --max-concurrent-downloads=10 --split=100 --min-split-size=1M --continue=true --optimize-concurrent-downloads=true --connect-timeout=10 --timeout=10 --lowest-speed-limit=1K --allow-overwrite=true  https://git.814560.xyz/https://github.com/msys2/msys2-installer/releases/download/2024-01-13/msys2-x86_64-20240113.exe https://dl.ghpig.top/https://github.com/msys2/msys2-installer/releases/download/2024-01-13/msys2-x86_64-20240113.exe https://ghproxy.liuzhicong.com/https://github.com/msys2/msys2-installer/releases/download/2024-01-13/msys2-x86_64-20240113.exe https://gh.ddlc.top/https://github.com/msys2/msys2-installer/releases/download/2024-01-13/msys2-x86_64-20240113.exe https://git.xfj0.cn/https://github.com/msys2/msys2-installer/releases/download/2024-01-13/msys2-x86_64-20240113.exe https://kkgithub.com/msys2/msys2-installer/releases/download/2024-01-13/msys2-x86_64-20240113.exe
```

## 配置VSCode Open-in-vim插件
将VSCode中的当前文件 在TERMINAL中使用Neovim打开

```json
    "open-in-vim.useNeovim": true,
    "open-in-vim.integrated-terminal.pathToShell": "D:\\msys64\\usr\\bin\\bash.exe",
```