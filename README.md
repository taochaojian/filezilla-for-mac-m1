# filezilla-for-mac-m1
ARM64  MAC only

# 应用签名
## 先安装Command Line Tools 工具，打开终端工具输入如下命令：
xcode-select --install
弹出安装窗口后选择继续安装，安装过程需要几分钟，请耐心等待。

## 打开终端工具输入并执行如下命令对应用签名：

sudo codesign --force --deep --sign - (应用路径)
注意：应用路径是「访达（Finder）->应用程序」找到应用将其拖进终端命令 - 的后面，然后按下回车键，输入macOS的密码然后按回车(输入过程中密码是不显示的，输入完密码直接按回车键即可！)

出现 「replacing existing signature」 提示即成功！
