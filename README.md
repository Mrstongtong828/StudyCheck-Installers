# StudyCheck Windows 安装包

本公开仓库用于分发 StudyCheck 学生桌面端安装包与版本说明。

- [下载 StudyCheck 0.2.9 安装包](https://github.com/Mrstongtong828/StudyCheck-Installers/releases/download/v0.2.9/StudyCheckSetup-v0.2.9.exe)
- [查看发布说明与 SHA-256 校验文件](https://github.com/Mrstongtong828/StudyCheck-Installers/releases/tag/v0.2.9)

下载 `StudyCheckSetup-v0.2.9.exe` 后，由使用者自行运行安装向导。
更新安装保留 `user_data` 中的学习进度、配置和文件。建议更新前关闭软件。

## 0.2.9 更新

- 根据实际空闲时间安排学习量，支持课表、可用时段和日期例外。
- 学生预览并本人确认后，个人提交期限与周期排程一起生效。
- 教师开放的练习任务支持受教师硬截止约束的自主延期。
- 改进离线草稿、重试与请求恢复，正式提交以服务端回执为准。

## 文件校验

```powershell
Get-FileHash .\StudyCheckSetup-v0.2.9.exe -Algorithm SHA256
```

SHA-256：`299be5dc1c06a6a26d43bbae2e47a86caada0b396402b9443c0f901ef428fbb8`

安装包仅包含程序、依赖、系统资源和公开默认配置，不包含开发者的账号、Cookie、学习记录或数据库。
