# Quick-Tools

## 功能简介

**Quick-Tools** 是一款多功能的系统管理工具，集成了关机、重启、网络测试、定时任务、文件同步等实用功能，同时提供详细的操作日志记录和管理界面，帮助用户快速高效地操作和管理计算机。此外，软件还具备授权验证机制，确保合法使用，并支持开机自动运行与后台托盘操作，提供更便捷的用户体验。

## 功能特点

### 1. 一键关机
- **快速执行关机**：点击“关机”按钮即可立即触发系统关机操作，支持立即关闭系统并终止所有任务，适用于紧急关机场景。
- **自动关机倒计时**：勾选“自动关机”选项，可在 3 秒倒计时后自动关机，提供更灵活的控制。

### 2. 系统重启
- **快速重启**：点击“重启”按钮即可立即触发系统重启操作，确保在不影响当前任务的情况下实现高效系统重启。
- **自动重启倒计时**：类似关机功能，支持在倒计时后自动重启系统。

### 3. Ping 测试
- **网络连通性测试**：通过预设的 IP 地址进行网络连通性测试，实时显示网络连接状态，适合进行网络故障排查。
- **支持自定义测试 IP**：可在软件安装目录的 `IP.xml` 文件中修改预设的测试 IP，满足不同网络环境需求。
- **显示本地网络信息**：自动检测并显示本地网络接口的详细信息，包括 IP 地址、网关等。

### 4. 定时任务
- **一次性定时关机**：设置一个具体时间，系统将在指定时间关机。
- **每日定时关机**：每天在指定时间自动执行关机任务。
- **独立执行**：定时任务支持独立执行，即使关闭程序，任务仍会按计划执行，不占用后台资源。

### 5. 文件同步
- **设置同步任务**：用户可选择源文件夹和目标文件夹，添加文件同步任务，确保文件在两个位置保持一致。
- **开机自动运行**：支持设置开机自动运行同步任务，确保系统启动后立即进行文件同步。

### 6. 授权验证
- **授权验证机制**：软件内置授权验证机制，确保软件合法使用。
- **机器标识绑定**：授权信息绑定到具体机器，防止在其他设备上未经授权使用。
- **加密保护**：采用 AES 加密技术保护授权信息，增强安全性。

## 软件界面预览

![软件界面预览](https://zero001.us.kg/webdav/document/2025-01-05.png)
<small>图片已是最新，同步更新完成。</small>

## 下载与安装

- **软件下载地址**：[点击下载](https://github.com/boy86001/Quick-Tools/releases)
- **安装要求**：
  - 支持 Windows 系统，需运行在 .NET Framework 4.8 环境下。
  - 如果系统未安装 .NET 4.8 环境，软件将自动跳转到 [.NET Framework 4.8 下载页面](https://dotnet.microsoft.com/download/dotnet-framework/net48)，请按照指引完成安装。
  - 安装过程需输入密码：`3004`

## 使用说明

### 1. 快速关机与重启
- **快速关机**：
  1. 点击“关机”按钮即可立即触发系统关机操作。
  2. 若勾选“自动关机”选项，系统将在 3 秒倒计时后自动关机。
- **系统重启**：
  1. 点击“重启”按钮即可立即触发系统重启操作。
  2. 若勾选“自动关机”选项，系统将在倒计时后自动重启。

### 2. 定时任务管理
1. 在“选择关机时间”中设置目标时间。
2. 选择“一次性”或“每日执行”模式。
3. 点击“设定定时关机”完成任务创建。即使关闭程序，定时关机任务仍会按计划执行，无需软件常驻后台。

### 3. Ping 测试
- **执行 Ping 测试**：
  1. 点击“Ping 测试”按钮，系统将自动读取 `IP.xml` 文件中的 IP 地址并依次进行 Ping 测试。
  2. 实时显示测试结果，包括延迟时间和连接状态。
- **更改测试 IP**：
  1. 打开软件安装目录，找到 `IP.xml` 文件。
  2. 编辑文件中的 `<ip>` 节点，添加或修改要测试的 IP 地址。
  3. 保存文件后重新启动软件，即可测试自定义的目标 IP。

### 4. 文件同步
- **设置同步任务**：
  1. 点击“文件同步”按钮进入文件同步界面。
  2. 点击“选择源文件夹”按钮，选择要同步的源文件夹。
  3. 点击“选择目标文件夹”按钮，选择目标文件夹。
  4. 点击“添加同步任务”按钮，将源文件夹与目标文件夹添加到同步任务列表。
- **查看与取消同步任务**：
  1. 在文件同步界面，点击“加载同步任务”按钮查看当前所有同步任务。
  2. 选择要取消的同步任务，点击“删除任务”按钮即可取消选中的同步任务。
- **开机自动运行**：
  1. 在文件同步界面，勾选“开机自动运行”选项。
  2. 软件将在系统启动后自动运行，并开始执行同步任务。

### 5. 授权验证
- **授权验证机制**：
  - 软件内置授权验证机制，确保软件合法使用。
- **授权验证**：
  - 软件通过安全的授权验证机制进行验证，确保软件仅在授权机器上运行。

### 6. 托盘图标与后台运行
- **最小化到托盘**：
  - 当软件最小化时，会隐藏主窗口并显示托盘图标，继续在后台运行文件同步任务。
- **托盘菜单**：
  - 右键点击托盘图标，可选择“显示主界面”或“退出”程序。
  - 双击托盘图标也可快速还原主界面。

## 注意事项

- **权限要求**：
  - 运行前请确保拥有系统管理员权限，部分功能（如关机、重启、定时任务、文件同步）可能无法在普通用户模式下执行。
- **自动关机与重启**：
  - 自动关机和重启功能将强制关闭未保存的任务，请确保提前保存工作。
- **文件同步**：
  - 在设置文件同步任务时，请确保源文件夹和目标文件夹的路径正确，避免数据丢失。
- **授权验证**：
  - 请勿非法修改授权信息，确保软件正常授权运行。

## 作者：YiSanYuan

感谢您使用 **Quick-Tools**！您的支持是我们不断优化和改进的动力。如果您有任何问题或建议，欢迎通过 GitHub Issues 或作者主页与我们联系。