# RAX3000M-EMMC 237 精简版固件

RAX3000M-EMMC 237 精简版固件

RAX3000M-NAND 固件移步仓库上游
[https://github.com/jiehuihui/immortalwrt24.10-6.6-cmcc_rax3000m-237](https://github.com/jiehuihui/immortalwrt24.10-6.6-cmcc_rax3000m-237)

## 🔧 固件特性

### 系统配置

- **后台地址**: `192.168.6.1`
- **登录账号**: `root`
- **登录密码**: 无（首次登录请设置密码）
- **默认主题**: Argon
- **编译源码**: [immortalwrt-mt798x-6.6](https://github.com/qcgzxw/immortalwrt-mt798x-6.6) - 使用ASUS闭源Wi-Fi驱动

### 固件文件说明

编译后生成的文件：

| 文件名 | 说明 | 用途 |
|--------|------|------|
| `initramfs-kernel.bin` | 内存引导固件 | 首次刷入测试、救砖使用 |
| `squashfs-sysupgrade.bin` | 系统升级固件 | 写入EMMC永久存储 |
| `sha256sums` | 校验文件 | 验证固件完整性 |

---

## 📦 集成插件

### 核心功能

- **mtwifi-cfg** - WiFi驱动配置工具
- **argon-config** - Argon主题配置界面
- **passwall** - 科学上网工具（含SingBox支持）
- **OpenClash** - OpenClash代理工具

### 网络工具

- **aria2** - 多协议下载工具
- **ksmbd** - SMB文件共享服务
- **frpc** - frp内网穿透客户端
- **Bandix** - 多功能网络工具

### 系统管理

- **diskman** - 磁盘管理工具（支持Btrfs）
- **hd-idle** - 硬盘休眠管理
- **autoreboot** - 定时重启计划任务

### 命令行工具
- **coremark** - CPU性能基准测试
- **iperf3** - 网络性能测试工具
- **Ruby** - Ruby编程语言（带YJIT支持）


---

## 🙏 致谢

感谢以下项目和开发者：
- [cmcc_rax3000m-237](https://github.com/jiehuihui/immortalwrt24.10-6.6-cmcc_rax3000m-237) CMCC-RAX3000M NAND版
- [immortalwrt-mt798x](https://github.com/padavanonly/immortalwrt-mt798x-6.6) - MT798x设备支持
- [Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt) - GitHub Actions 在线云编译

---

## 📄 License

本项目基于 MIT 协议开源。

固件包含的开源组件遵循各自的开源协议。
