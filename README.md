# ImmortalWrt 24.10 for Amlogic S922X (eMMC)

## 特点
- 适配 S922X / A311D
- eMMC 支持
- LuCI 中文 + 插件
- 6.6 内核

## 刷机 (eMMC)
1. 下载 `.img.gz` → 解压 `.img`
2. dd 写入 U盘：
   ```bash
   sudo dd if=openwrt-*.img of=/dev/sdX bs=4M conv=fsync
