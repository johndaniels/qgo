
## qGo 

[![OS X Build Status](https://travis-ci.org/johndaniels/qgo.svg?branch=master)](https://travis-ci.org/johndaniels/qgo) 
[![Windows Build status](https://ci.appveyor.com/api/projects/status/txmk019ss2c37fcb/branch/master?svg=true)](https://ci.appveyor.com/project/johndaniels/qgo/branch/master)

qGo is a Go Client based on Qt 5.
It supports playing online at IGS-compatible servers (including some special tweaks for WING and LGS, also NNGS was reported to work) and locally against gnugo (or other GTP-compliant engines).
It also has rudimentary support for editing SGF files and parital support for CyberORO/WBaduk, Tygem, Tom, and eWeiqi (developers of these backends are currently inactive, everybody is welcome to take them over).

Go is an ancient Chinese board game. It's called "圍棋(Wei Qi)" in Chinese, "囲碁(Yi Go)" in Japanese, "바둑(Baduk)" in Korean.


## Instalation

If you are using OS X or Windows, you should be able to download and run the latest 'release' from [the releases page](https://github.com/johndaniels/qgo/releases). On OS X, you can unpack the DMG and copy the application bundle to your applications folder. On Windows, you can simply unzip the release wherever you wish and run the executable found in the extracted folder.

## Compiling from source
Qt 5.7 is or newer is required to build qgo.

```sh
git clone https://github.com/pzorin/qgo.git
cd qgo
qmake -qt=5 src
make
sudo make install
```
