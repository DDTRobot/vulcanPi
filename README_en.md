<p align="center"><strong>vulcanPi</strong></p>
<p align="center"><a href="https://github.com/DDTRobot/vulcanPi/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-orange"/></a>
<img alt="language" src="https://img.shields.io/badge/language-c++-red"/>
<img alt="platform" src="https://img.shields.io/badge/platform-X3Pi-l"/>
</p>
<p align="center">
    语言：<a href="./docs/docs_en/README_EN.md"><strong>English</strong></a> / <strong>中文</strong>
</p>

In order to enrich the software ecology of horizon `x3pi` , `vulcanpi` provides users with a way to use `C++` to drive GPIO.

---

## Installation 

At present, the project has only been tested on the `x3pi` hardware platform. You can also try to compile and use it on other horizon hardware platforms.

```bash
#clone API source code
git clone https://github.com/DDTRobot/vulcanPi.git

cd vulcanPi && mkdir build
cd build && cmake ..
make
sudo make install
```



## Function support 

- Support serial communication
- Support spi communication
- Support GPIO control



## Update plan

1. Add IIC communication



## Taste 更多版本

If you want to try more new functions, please refer to [vulcanPi (beta)](https://github.com/Vulcan-YJX/vulcanPi)。

