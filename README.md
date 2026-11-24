<div align="center">
    <img src="resources/icon-app.png"
        title="Whisper" alt="Whisper logo" width="120" />
</div>
<div align="center">
    <img src="resources/title-white.png"
        title="Whisper" alt="Whisper title" width="300" />
</div>

<div align="center">
    <h3>弦歌未歇，辞章已见。</h3>
    <h3>为桌面音乐播放器提供实时歌词、翻译与沉浸式覆盖层。</h3>
</div>

## 下载与运行

1. 打开最新版本页面：https://github.com/Whisper-Lyrics/Whisper-Release/releases/latest
2. 下载 `Whisper.exe`。
3. 双击运行，无需安装。
4. 程序启动后会显示设置主窗口和歌词覆盖层。

## 系统要求

- Windows 10 64 位
- Windows 11 64 位
- 播放器需要提供 Windows SMTC 媒体信息
- 网易云音乐、QQ音乐如需完整能力，请按指引安装歌词同步组件

## 开始使用

1. 在播放器中开始播放歌曲。
2. 打开 Whisper 设置窗口，确认已识别到媒体源。
3. 在预览区域调整积木位置和尺寸。
4. 在“外观”中调整字体、字号、辉光、阴影和对齐。
5. 在“动效”中调整歌词入场、退场、扫光和粒子。
6. 在“窗口”中调整覆盖层背景、锁定状态和启动行为。
7. 打开 OBS，添加“窗口捕获”，选择 `Whisper Overlay`。

OBS 窗口采集建议选择 `Windows 10 (1903 or newer)`。

## 覆盖层

覆盖层分为本机显示和推流显示。锁定后鼠标点击会穿透覆盖层；解锁后可以拖动覆盖层并调整位置。

如果使用 OBS，请选择覆盖层窗口，**不要选择** Whisper 设置主窗口。

## 数据目录

配置和歌词缓存默认保存在：

`%APPDATA%\Whisper`

备份或迁移数据前，请先退出 Whisper，再复制整个目录。

## 更新

Whisper 会从本仓库的 GitHub Releases 检查新版本。

发行资产使用单文件 `Whisper.exe`。新版本发布后可直接下载替换旧文件，用户设置不会因为替换程序而丢失。

## 校验发行包

每个版本可附带对应的 SHA256 校验文件。下载后可在 PowerShell 中运行：

```powershell
Get-FileHash .\Whisper.exe -Algorithm SHA256
```

将结果与 Release 页面或 `checksums` 目录中的校验值比较。

## 反馈

问题反馈：https://github.com/Whisper-Lyrics/Whisper-Release/issues

或 QQ 群：85121371

## 赞赏

若您认为 Whisper 是一个不错的项目，可以请我们喝杯咖啡！
<div align="center">
    <img src="resources/rewards.JPG"
        title="Whisper" alt="rewards code" width="300" />
</div>
