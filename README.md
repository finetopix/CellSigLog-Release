# CellSigLog Release

[English](#english) | [中文](#中文)

## 中文

CellSigLog 是一款 Android 蜂窝网络信号记录与地图可视化工具，适合路测、站点核查、覆盖观察和信号日志采集。这个仓库用于发布可下载安装的 APK。

### 下载

- 所有版本：[GitHub Releases](https://github.com/finetopix/CellSigLog-Release/releases)

### 主要功能

- 双 SIM 信号监测：分别查看 SIM1 / SIM2 的服务小区、邻区和信号强度。
- 地图显示：支持 OpenStreetMap，也可按设置切换 Google Maps。
- 小区扇区显示：在地图上显示站点扇区、方向角、覆盖范围和匹配连线。
- 信号轨迹记录：记录 GPS 位置、蜂窝网络信息和信号质量，并以 CSV 保存。
- 回放已保存日志：在 Settings -> Replay Saved Log 中选择 CSV，查看完整路线、方向箭头、播放/暂停、前后点切换、速度选择和单点详情。
- 拍照水印：拍照时可叠加当前位置信息和蜂窝信号信息。
- 外部 GPS 与上传设置：支持外部 GPS 配置、服务器上传配置和待上传队列。
- 应用内检查更新：Settings -> Check New Version 会读取本仓库最新 Release。

### 安装要求

- Android 10+，最低 SDK 29。
- 首次安装 GitHub 下载的 APK 时，Android 可能需要允许“安装未知来源应用”。
- 为了完整使用记录功能，需要授予位置、电话状态和前台定位服务等权限。
- 地图瓦片和更新检查需要网络连接。

### 基本使用

1. 安装 APK 并打开 CellSigLog。
2. 授予位置和电话状态权限。
3. 在 SIM1 或 SIM2 页面查看实时信号和地图轨迹。
4. 点击 Start Logging 开始记录，Stop Logging 停止并保存 CSV。
5. 在 Settings 中可切换地图、调整刷新/图例/上传设置。
6. 如需查看旧日志，进入 Settings -> Replay Saved Log，选择之前保存的 CSV 文件。
7. 电脑端地理化显示：https://signal.finetopix.com/map

### 隐私说明

CellSigLog 处理的数据可能包含位置、时间、运营商、小区标识和信号强度。请只在你有权采集和分享的位置使用本工具。对外分享 CSV 或截图前，请确认其中不包含敏感位置或个人信息。

### 反馈

- Forum: https://forum.finetopix.com
- Topic: Internal Testing Users - Drive Test Tool
- Email: finetopix@gmail.com

---

## English

CellSigLog is an Android cellular signal logging and map visualization tool for drive testing, site checks, coverage observation, and signal log collection. This repository publishes installable APK releases.

### Download

- All versions: [GitHub Releases](https://github.com/finetopix/CellSigLog-Release/releases)

### Features

- Dual SIM monitoring: inspect serving cells, neighbor cells, and signal strength for SIM1 and SIM2.
- Map display: supports OpenStreetMap, with Google Maps available through map settings.
- Cell sector visualization: show tower sectors, azimuth, range, and matching connection lines on the map.
- Signal track logging: record GPS position, cellular network details, and signal quality to CSV.
- Saved log replay: use Settings -> Replay Saved Log to open a CSV and replay the route with direction arrows, play/pause, previous/next navigation, speed control, and point details.
- Camera watermark: capture photos with current location and cellular signal information overlaid.
- External GPS and upload settings: configure external GPS, server upload, and queued retry behavior.
- In-app update check: Settings -> Check New Version reads the latest release from this repository.

### Requirements

- Android 10+; minimum SDK 29.
- Installing an APK downloaded from GitHub may require enabling installation from unknown sources on Android.
- Full logging requires location, phone state, and foreground location service permissions.
- Map tiles and update checks require network access.

### Quick Start

1. Install the APK and open CellSigLog.
2. Grant location and phone state permissions.
3. Use the SIM1 or SIM2 tab to view live signal data and map tracks.
4. Tap Start Logging to record data, then Stop Logging to save a CSV.
5. Use Settings to change map provider, refresh interval, legend thresholds, and upload behavior.
6. To inspect an old log, open Settings -> Replay Saved Log and select a saved CSV file.
7. PC Map view URL: https://signal.finetopix.com/map

### Privacy Note

CellSigLog data may include location, timestamps, operator information, cell identifiers, and signal strength. Use it only where you are authorized to collect such data. Before sharing CSV files or screenshots, check that they do not expose sensitive locations or personal information.

### Feedback

- Forum: https://forum.finetopix.com
- Topic: Internal Testing Users - Drive Test Tool
- Email: finetopix@gmail.com
