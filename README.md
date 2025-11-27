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
- **支持平台**：适配 Rockchip、x86 设备
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
|openwrt-24.10| ![编译状态](https://github.com/QuickWrt/ZeroWrt/actions/workflows/build-release.yml/badge.svg) | [下载链接](https://github.com/QuickWrt/ZeroWrt/releases/tag/v24.10.4) |

---

## 近期更新 [![](https://img.shields.io/badge/-近期固件更新-FFFFFF.svg)](#近期更新-)
🤣努力修复中……

## 定制固件 [![](https://img.shields.io/badge/-项目基本编译教程-FFFFFF.svg)](#定制固件-)
1. 首先要登录 Gihub 账号，然后 Fork 此项目到你自己的 Github 仓库
2. 修改 `configs` 目录对应文件添加或删除插件，或者上传自己的 `xx.config` 配置文件
3. 插件对应名称及功能请参考恩山网友帖子：[Applications 添加插件应用说明](https://www.right.com.cn/forum/thread-3682029-1-1.html)
4. 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `diy-script.sh` 文件内修改
5. 添加或修改 `xx.yml` 文件，最后点击 `Actions` 运行要编译的 `workflow` 即可开始编译
6. 编译大概需要3-5小时，编译完成后在仓库主页 [Releases](https://github.com/haiibo/OpenWrt/releases) 对应 Tag 标签内下载固件
<details>
<summary><b>&nbsp;如果你觉得修改 config 文件麻烦，那么你可以点击此处尝试本地提取</b></summary>

1. 首先装好 Linux 系统，推荐 Debian 11 或 Ubuntu LTS

2. 安装编译依赖环境

   ```bash
   sudo apt update -y
   sudo apt full-upgrade -y
   sudo apt install -y ack antlr3 asciidoc autoconf automake autopoint binutils bison build-essential \
   bzip2 ccache cmake cpio curl device-tree-compiler fastjar flex gawk gettext gcc-multilib g++-multilib \
   git gperf haveged help2man intltool libc6-dev-i386 libelf-dev libglib2.0-dev libgmp3-dev libltdl-dev \
   libmpc-dev libmpfr-dev libncurses5-dev libncursesw5-dev libreadline-dev libssl-dev libtool lrzsz \
   mkisofs msmtp nano ninja-build p7zip p7zip-full patch pkgconf python2.7 python3 python3-pyelftools \
   libpython3-dev qemu-utils rsync scons squashfs-tools subversion swig texinfo uglifyjs upx-ucl unzip \
   vim wget xmlto xxd zlib1g-dev
   ```

3. 下载源代码，更新 feeds 并安装到本地

   ```bash
   git clone https://github.com/coolsnowwolf/lede
   cd lede
   ./scripts/feeds update -a
   ./scripts/feeds install -a
   ```

4. 复制 diy-script.sh 文件内所有内容到命令行，添加自定义插件和自定义设置

5. 命令行输入 `make menuconfig` 选择配置，选好配置后导出差异部分到 seed.config 文件

   ```bash
   make defconfig
   ./scripts/diffconfig.sh > seed.config
   ```

7. 命令行输入 `cat seed.config` 查看这个文件，也可以用文本编辑器打开

8. 复制 seed.config 文件内所有内容到 configs 目录对应文件中覆盖就可以了

   **如果看不懂编译界面可以参考 YouTube 视频：[软路由固件 OpenWrt 编译界面设置](https://www.youtube.com/watch?v=jEE_J6-4E3Y&list=WL&index=7)**
</details>


## 特别提示 [![](https://img.shields.io/badge/-个人免责声明-FFFFFF.svg)](#特别提示-)

- **因精力有限不提供任何技术支持和教程等相关问题解答，不保证完全无 BUG！**

- **本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任！**

- **本固件禁止用于任何商业用途，请务必严格遵守国家互联网使用相关法律规定！**


## 鸣谢 [![](https://img.shields.io/badge/-跪谢各大佬-FFFFFF.svg)](#鸣谢-)
| [ImmortalWrt](https://github.com/immortalwrt) | [coolsnowwolf](https://github.com/coolsnowwolf) | [P3TERX](https://github.com/P3TERX) | [Flippy](https://github.com/unifreq) |
| :-------------: | :-------------: | :-------------: | :-------------: |
| <img width="100" src="https://avatars.githubusercontent.com/u/53193414"/> | <img width="100" src="https://avatars.githubusercontent.com/u/31687149"/> | <img width="100" src="https://avatars.githubusercontent.com/u/25927179"/> | <img width="100" src="https://avatars.githubusercontent.com/u/39355261"/> |
| [Ophub](https://github.com/ophub) | [SuLingGG](https://github.com/SuLingGG) | [QiuSimons](https://github.com/QiuSimons) | [IvanSolis1989](https://github.com/IvanSolis1989) |
| <img width="100" src="https://avatars.githubusercontent.com/u/68696949"/> | <img width="100" src="https://avatars.githubusercontent.com/u/22287562"/> | <img width="100" src="https://avatars.githubusercontent.com/u/45143996"/> | <img width="100" src="https://avatars.githubusercontent.com/u/44228691"/> |


<a href="#readme">
<img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" title="返回顶部" align="right"/>
</a>
