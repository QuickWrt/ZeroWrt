# 🔥 ZeroWrt —— 基于原生 OpenWrt 深度优化的高性能固件

ZeroWrt 是一款基于 **原生 OpenWrt** 深度优化、精心打磨的固件版本，旨在为用户提供 **更高效、更稳定、更极致** 的使用体验。  
无论是家用网络、软路由、NAS 还是高性能场景，ZeroWrt 都能带来超越原版的表现。

---

## ✨ ZeroWrt 特性亮点

ZeroWrt 融合了性能、稳定性与可玩性，加入大量增强补丁与优化能力：

- 🚀 **kmod 内核模块完整支持**  
- 🔥 **全锥型 NAT（NFT、BCM 双方案）**  
- ⚡ **SS AES 硬件加速**（显著提升代理性能）  
- 🧠 **构建优化：O3 优化 + LTO 全链接时优化**  
- 🎮 **GPU 硬件加速**  
- 🖥️ **HDMI 终端输出支持**（部分设备可图形化查看日志 / 控制台）  
- 📦 **在线 OTA 升级（squashfs）**  
- ⏱ **硬件 RTC 时钟支持（HYM8563）**  
- ♻️ **固件一键重置（squashfs）**  
- 🌐 **BBRv3 / TCP Brutal 拥塞控制算法**（网络优化更激进、更高速）  
- 🔧 **LLVM-BPF 支持（可用于 eBPF 程序）**  
- 🚀 **Shortcut-FE（含 UDP 入站加速）**  
- 🖥️ **KVM 虚拟化支持**  
- 🔒 **LRNG v57 高质量随机数系统**  
- ⚡ **NGINX & CURL HTTP/3 / QUIC 全面支持**  
- ❄️ **PWM 风扇控制（适配相关硬件）**  

---

### 🧩 ZeroWrt 插件（App）列表

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

✅ 可用

❌ 不可用

⏳ 计划中

特别说明：

* *AirPlay 2：一款简单易用的 AirPlay 音频播放器，需要外接 USB 声卡使用。*

---

## 🔧 默认登录信息

```
管理地址：http://10.0.0.1  
          http://openwrt.lan  
账户：root  
密码：password
```

---

## 📥 下载 & 在线升级

ZeroWrt 支持 **squashfs 在线升级（OTA）**，可一键保持配置升级。  
（此处可放入你的固件下载地址）

---

## 🎯 总结

ZeroWrt 不是简单的 OpenWrt，而是在原生基础上进行了  
**性能极限优化、硬件能力完全释放、稳定性工程级打磨** 的高端固件版本。  
无论你是发烧友还是专业用户，ZeroWrt 都将为你的网络环境带来极致体验。

欢迎体验 ZeroWrt ——让性能飞起来！🚀

