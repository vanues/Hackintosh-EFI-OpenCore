# Hackintosh-EFI-OpenCore

| Item           | Model                                |
| -------------- | ------------------------------------ |
| Motherboard    | Gigabyte z390 i aorus pro wifi (F8C) |
| CPU            | i7-9700                              |
| Memory         | Asgard 16Gx1                         |
| Storage        | Crucial MX500 1T                     |
| WIFI-Bluetooth | Default                              |
| GPU            | iGPU (UHD630)                        |
| OpenCore       | 0.59                                 |

MacOS: Catalina 10.15.6



Not working:

- Airdrop
- Handoff



TODO:

- Update BIOS setting files



Warnning:

​	Thanks to [@lerencao](https://github.com/lerencao/opencore-z390p-9600k) , Delete framebuffer-stolenmem then reboot, 4k resolution will be available in settings

- > framebuffer-stolenmem 这个属性最好不加，直接在 BIOS 中设置 iGPU 的 memory。我在这里踩了坑：安装 macos 后，外接的4K显示器只能展示出 2k 的分辨率。后来把这个属性删掉了，才正常。

