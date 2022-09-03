<p align="center"><strong>vulcanPi</strong></p>
<p align="center"><a href="https://github.com/DDTRobot/vulcanPi/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-orange"/></a>
<img alt="language" src="https://img.shields.io/badge/language-c++-red"/>
<img alt="platform" src="https://img.shields.io/badge/platform-X3Pi-l"/>
</p>
<p align="center">
    语言：<a href="./README_en.md"><strong>English</strong></a> / <strong>中文</strong>
</p>

为丰富地平线 `X3Pi` 的软件生态，`vulcanPi` 为用户提供使用 `C++` 驱动 GPIO 的方法。

---

## Installation 安装

目前该项目仅在 `X3Pi` 硬件平台进行了测试，您也可以尝试在其他地平线的硬件平台中编译使用。

```bash
#clone API source code
git clone https://github.com/DDTRobot/vulcanPi.git

cd vulcanPi && mkdir build
cd build && cmake ..
make
sudo make install
```



## Function support 功能支持

- 支持串口通信
- 支持 SPI 通信
- 支持 GPIO 控制



## Update plan 更新计划

1. 增加 IIC 通信



## Taste 更多版本

 如果您想要尝试更多的新功能，请参考 [vulcanPi (beta版本)](https://github.com/Vulcan-YJX/vulcanPi)。

