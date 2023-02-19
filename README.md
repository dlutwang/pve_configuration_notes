# Proxmox VE 折腾手记

## 介绍
PVE 虚拟化平台的安装以及折腾手记。  

- PVE ISO 版本：7.2-1 (Last update: 04 May 2022)

- 演示机：
    - CPU：N5105
    - 内存：16G
    - 硬盘：SSD 512G

- 内部网络：
    - IPv4 网络
        - IP 地址：172.16.1.250
        - 子网掩码：255.255.255.0
        - 网关：172.16.1.1
        - DNS：172.16.1.1
    - IPv6 网络
        - 前缀：fc00::/60
        - 前缀长度：64
        - IP 地址：fc00::fa
        - DNS：fc00::1

### 系列章节

0.  [硬件BIOS配置](./0.硬件BIOS配置.md)
1.  [PVE系统安装](./1.PVE系统安装.md)
2.  [PVE初始化配置](./2.PVE初始化配置.md)
3.  [PVE系统调整](./3.PVE系统调整.md)
4.  [PVE创建模板虚拟机](./4.PVE创建模板虚拟机.md)
5.  [PVE制作虚拟机模板](./5.PVE制作虚拟机模板.md)
6.  [PVE用模板克隆虚拟机](./6.PVE用模板克隆虚拟机.md)
7.  [PVE自动备份虚拟机](./7.PVE自动备份虚拟机.md)
8.  [PVE开启硬件直通功能](./8.PVE开启硬件直通功能.md)

### 文章说明

1.  本系列文章涉及的部分参数需要手动调整来符合切实使用需求。
2.  随着 PVE 系统的迭代更新，截图中的内容和实际页面显示可能存在差异。
3.  如需引用，请注明本文出处。
