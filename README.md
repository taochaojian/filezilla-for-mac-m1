# filezilla-for-mac-m1
Build FileZilla for Macos on ARM64


ARM64  MAC only

mac filezilla  M1

# 应用签名
## 1.先安装Command Line Tools 工具
打开终端工具输入如下命令:

xcode-select --install

## 2.应用签名：
打开终端工具输入并执行如下命令:


sudo codesign --force --deep --sign - /Applications/FileZilla.app


出现 「replacing existing signature」 提示即成功！
