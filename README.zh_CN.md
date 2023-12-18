## ROG MAXIMUS XII HERO WiFi Hackintosh OpenCore

![image](ScreenShot/Motherboard.jpg)

### [English](https://github.com/hackintosh-efi/ROG-STRIX-B760-I-GAMING-OpenCore)

### OpenCore

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)

### 支持的系统版本

- macOS Monterey 12.x
- macOS Ventura  13.x
- macOS Sonoma   14.x 

### 硬件

- 主板: Z490芯片组
- BIOS版本: 2701（2023/03/21）
- CPU: 英特尔 i9-10900K
- 内存: 海盗船 128GB（32GB*4）DDR4 3200MHz
- 固态硬盘: 1. KINGSTON SFYRDK2000G MacOS
- 固态硬盘: 2.Flashwar SSD W300 Pro 256GB Windows
- 核显: 英特尔超核心显卡630 
- 独显: 蓝宝石 Radeon RX5700XT
- 声卡: 瑞昱 ALC1220
- 网卡: Intel L219V 
- 网卡: Aquantia AQC111C （只能在Windows中使用）
- 无线网卡: BCM94360CD
- CPU散热器: 九州风神大霜塔 AG620
- 电源: 长城金牌GX850W 金牌全模组
- 机箱: 乔斯伯 U4 Plus

### 注意事项

 - 使用[OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/)修改SMBIOS，重新生成三码

### Bios Setup

```
Advanced
     
  |-- System Agent(SA)Configuration
     |-- VT-D ：Disabled
     |-- Control Iommu Pre-boot Behavior ：Disable IOMMU
	   
  |--PCI Subsystem Settings
     |-- Above 4G Decoding ：Enabled
     |-- Resize BAR Support ：Disabled
     |-- SR-IOV Support ：Disabled
   
Boot

  |-- Secure Boot
    |-- OS Type ：Other OS
    |-- Secure Boot Mode ：Custom
      
  |-- Boot Configuration
    |-- Fast Boot ：Disabled
      
  |-- CSM (Compatibility Support Module)
    |-- Launch CSM  ：Disabled
```




### 联系我们

 - QQ群: 23304408

![image](ScreenShot/QRCode.png)