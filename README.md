<div align="center">
  <img width="768" src="https://cdn.jsdelivr.net/gh/haiibo/OpenWrt/images/openwrt.png"/>
  <h1>ZeroWrt — 基于 OpenWrt 的极致性能固件</h1>

  <img src="https://img.shields.io/github/downloads/QuickWrt/ZeroWrt/total.svg?style=for-the-badge&color=32C955"/>
  <img src="https://img.shields.io/github/stars/QuickWrt/ZeroWrt.svg?style=for-the-badge&color=orange"/>
  <img src="https://img.shields.io/github/forks/QuickWrt/ZeroWrt.svg?style=for-the-badge&color=ff69b4"/>
  <img src="https://img.shields.io/github/license/QuickWrt/ZeroWrt.svg?style=for-the-badge&color=blueviolet"/>

  [![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) 
  [![](https://img.shields.io/badge/-项目介绍-FFFFFF.svg)](#项目介绍) 
  [![](https://img.shields.io/badge/-固件特色-FFFFFF.svg)](#固件特色)
  [![](https://img.shields.io/badge/-固件下载-FFFFFF.svg)](#固件下载)
  [![](https://img.shields.io/badge/-插件预览-FFFFFF.svg)](#插件预览)
  [![](https://img.shields.io/badge/-编译指南-FFFFFF.svg)](#编译指南)
  [![](https://img.shields.io/badge/-鸣谢-FFFFFF.svg)](#鸣谢)
</div>

---

## 📚 项目介绍 [![](https://img.shields.io/badge/-项目说明-FFFFFF.svg)](#项目介绍)
**ZeroWrt** 是一款基于 **原生 OpenWrt** 深度优化的高性能固件，致力于为用户提供 **更快、更稳定、更强大的网络体验**。无论你是家庭用户还是专业用户，ZeroWrt 都能为你提供极致的网络性能。

- **构建来源**：[OpenWrt](https://github.com/openwrt/openwrt)  
- **支持平台**：适配 ARMv8、Rockchip、树莓派、x86 等多平台设备
- **优化特性**：采用全新内核、增强的硬件加速、系统优化、无缝 OTA 更新等

---

## 🔧 固件特色 [![](https://img.shields.io/badge/-固件亮点-FFFFFF.svg)](#固件特色)
ZeroWrt 打破了传统固件的局限，提供了前所未有的性能提升与稳定性：

- 🚀 **kmod 内核模块完整支持**：保证设备兼容性。
- 🔥 **全锥型 NAT (NFT & BCM 双方案)**：提供极速网络转发。
- ⚡ **SS AES 硬件加速**：极大提升代理速度，保障网络畅通无阻。
- 🧠 **LTO & O3 构建优化**：多维度提升固件性能。
- 🎮 **GPU 硬件加速**：解锁图形处理与视频加速功能。
- 🖥 **HDMI 终端输出**：支持图形化查看日志、控制台输出。
- 🌐 **BBRv3 / TCP Brutal 拥塞控制**：更适合高流量场景。
- 🔧 **LLVM-BPF 支持**：提供 eBPF 程序的强大支持。
- 📦 **Docker 支持**：在 OpenWrt 内部署 Docker 应用，增强灵活性。
- ⏱ **硬件 RTC 时钟支持**：精准的时间同步与管理。

---

## 💾 插件预览 [![](https://img.shields.io/badge/-插件展示-FFFFFF.svg)](#插件预览)
ZeroWrt 内置了多个功能强大的插件，帮助你更好地管理网络和设备：

### 常见插件列表：

| **内置插件**               | **状态** | **内置插件**         | **状态** |
|----------------------------|:--------:|----------------------|:--------:|
| PassWall                   | ✅       | Docker               | ✅       |
| HomeProxy                  | ✅       | TTY 终端             | ✅       |
| FileBrowser                | ✅       | NetData 监控         | ✅       |
| qBittorrent                | ✅       | DiskMan 磁盘管理     | ✅       |
| MosDNS                     | ✅       | CPU 性能调节         | ✅       |
| 动态 DNS                   | ✅       | SQM 列队管理         | ✅       |
| Watchcat                   | ✅       | nlbw 宽带监控        | ✅       |
| KMS 服务器                 | ✅       | Socat                | ✅       |
| FRP 客户端                 | ✅       | 应用过滤             | ✅       |
| 网络唤醒                   | ✅       | 访问控制             | ✅       |
| 网络共享（Samba）          | ✅       | UPnP                 | ✅       |
| 锐捷认证                   | ✅       | IP 限速              | ✅       |
| Aria2                      | ✅       | WireGuard            | ✅       |
| Alist 文件列表             | ✅       | L2TP                 | ✅       |
| USB 打印服务器             | ✅       | ZeroTier             | ✅       |
| 隔空播放（AirConnect）     | ✅       | WebDav               | ✅       |
| 自定义命令                 | ✅       | AirPlay 2            | ✅       |
| 网速测试                   | ✅       | NATMap               | ✅       |

---

## 📥 固件下载 [![](https://img.shields.io/badge/-固件下载-FFFFFF.svg)](#固件下载)
点击下表中的下载链接，轻松获得你所需的固件版本。

| **固件版本**   | **固件编译状态**     | **固件下载**              |
|:---------------------:|:--------------------:|:-------------------------:|
| [固件版本](https://github.com/QuickWrt/ZeroWrt/releases/tag/v24.10.4) | ![编译状态](https://github.com/QuickWrt/ZeroWrt/actions/workflows/build-release.yml/badge.svg) | [下载链接](https://github.com/QuickWrt/ZeroWrt/releases/tag/v24.10.4) |

---

## ⚙️ 编译指南 [![](https://img.shields.io/badge/-编译指南-FFFFFF.svg)](#编译指南)
1. **Fork 项目**：首先在 GitHub 上 Fork 该项目到你自己的仓库。
2. **修改配置**：根据需要修改 `configs` 目录中的配置文件，或者上传自己的 `.config` 配置文件。
3. **添加插件**：根据需求添加插件和功能。
4. **运行编译**：进入 GitHub Actions，启动对应的编译工作流。
5. **下载固件**：编译完成后，你可以在 [Releases](https://github.com/QuickWrt/ZeroWrt/releases) 页面下载最新固件。

---

## ⚠️ 特别提示 [![](https://img.shields.io/badge/-免责声明-FFFFFF.svg)](#特别提示)
- 本项目提供的固件不保证完全无 BUG，用户在使用过程中请自行评估风险。
- 不提供任何技术支持，若遇到问题请参考相关文档或社区。
- **请勿将本固件用于任何商业用途。**

---

## 🙏 鸣谢 [![](https://img.shields.io/badge/-致谢-FFFFFF.svg)](#鸣谢)
感谢以下社区和开发者的贡献，ZeroWrt
