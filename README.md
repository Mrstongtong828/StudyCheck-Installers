# StudyCheck Windows 安装包

- [下载 StudyCheck 0.2.10 修复版](https://github.com/Mrstongtong828/StudyCheck-Installers/releases/download/v0.2.10/StudyCheckSetup-v0.2.10.exe)
- [发布说明与 SHA-256 校验文件](https://github.com/Mrstongtong828/StudyCheck-Installers/releases/tag/v0.2.10)

v0.2.10 修复 v0.2.9 的 QtCore DLL 启动错误，并增加原生依赖兼容检查。

## 安装与升级

首次安装：下载安装包，按向导安装，打开后由本人登录学校账号。

已有旧版：保存工作，退出软件及托盘进程；先备份 user_data，再将安装位置选择为原 StudyCheck 根目录。不要先卸载旧版，不要选择 system 或 user_data 子目录。更新保留本地配置和学习记录。

## 校验

文件：`StudyCheckSetup-v0.2.10.exe`，186,533,454 字节。

SHA-256：`d3f6fee8e667bcba828d63ed954668cead77319575440977b3b57df34cf5a8aa`

```powershell
Get-FileHash .\StudyCheckSetup-v0.2.10.exe -Algorithm SHA256
```

本仓库仅分发安装包与说明，不含开发者账号、Cookie、学习记录或数据库。
