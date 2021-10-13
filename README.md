# tool-set
A set of utilities used in the development process
## 1. caching_sha2_password.dll
|  类别   | 描述  |
|  ----  | ----  |
| 适用软件  | Navicat Premium 12 |
| 解决问题  | 由于MySQL8加密方式改变导致的连接时2059报错 |
| 原理  | 低版本的navicat不支持MySQL8的新版加密方式，因此需要增加dll支持 |
| 使用方式  | 将此dll复制到navicat.exe所在的安装目录，重启即可 |
