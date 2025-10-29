# ImmortalWrt 24.10 for Amlogic S922X (eMMC)

## 固件特点
- 适配 **Amlogic S922X / A311D**
- 支持 **eMMC 启动 + 升级**
- LuCI 中文界面
- 6.6 内核

## 刷机步骤（eMMC）

1. 下载 `openwrt-meson-g12b-a311d-squashfs-sysupgrade.img.gz`
2. 解压 → `.img`
3. 写入 U 盘：
   ```bash
   sudo dd if=openwrt-*.img of=/dev/sdX bs=4M conv=fsync status=progress
