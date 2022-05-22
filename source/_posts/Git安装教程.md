title: Git安装教程
author: ChaiZhaoyuan
tags:
  - Git
date: 2020-08-18 21:40:14
---

## Git安装教程

下载地址： https://git-scm.com/downloads<br>
1.下载完成后双击“Git-2.28.0-64-bit.exe”，点击Next
![](https://i.loli.net/2020/08/18/C63vcsxa5wozfSU.png)

2.选择安装位置，然后Next
![](https://i.loli.net/2020/08/18/ohgiErj2Xk6uZGQ.png)

3.如果以前安装过，会提示已存在文件夹，点击“是”
![](https://i.loli.net/2020/08/18/6dl4OT3F87mCvRA.png)

4.选择组件安装
![](https://i.loli.net/2020/08/18/pW4LrByNgDC7Yds.png)
如不确定，请全部勾选<br><br>
5.开始菜单快捷方式目录，如不需要，可选择"Don't create a Start Menu folder"
![](https://i.loli.net/2020/08/18/S5mgTJDMrsBXZL4.png)

6.选择编辑器，默认选择vim
![](https://i.loli.net/2020/08/18/3rVAy5mEROB74PW.png)

7.设置环境变量
![](https://i.loli.net/2020/08/18/OgMrAc5qJ1CjzQB.png)
选择命令行工具，默认使用Git Bash即可：<br>
（1）Git自带：使用Git自带的Git Bash命令行工具。<br>
（2）系统自带CMD：使用Windows系统的命令行工具。<br>
（3）二者都有：上面二者同时配置，但是注意，这样会将windows中的find.exe 和 sort.exe工具覆盖，如果不懂这些尽量不要选择。<br><br>
8.选择HTTPS传输后端，默认OpenSSL，点击Next
![](https://i.loli.net/2020/08/18/CuTv4atmQENJbfp.png)

9.选择提交的时候换行格式
![](https://i.loli.net/2020/08/18/CJrnPD69oy3AU8g.png)
（1）检查出windows格式转换为unix格式：将windows格式的换行转为unix格式的换行再进行提交。<br>
（2）原来格式转为unix格式：不管什么格式，一律转为unix格式的换行再进行提交。<br>
（3）不进行格式转换:不进行转换，检查出什么，就提交什么。<br>

10.点击Next
![](https://i.loli.net/2020/08/18/JI68vabViuYNwFQ.png)

11.点击Next
![](https://i.loli.net/2020/08/18/6pxSR5u1hLIV2nH.png)

12.证书凭证管理，默认Git证书管理器，点击Next
![](https://i.loli.net/2020/08/18/83JcAkD7GVoqZSF.png)

13.点击Next
![](https://i.loli.net/2020/08/18/aephOBl6Y3Z7URw.png)

14.点击Next
![](https://i.loli.net/2020/08/18/XYwSsTHolR2i91m.png)

15.正在安装
![](https://i.loli.net/2020/08/18/aXCjp5GBhNJDfQi.png)

16.安装完成
![](https://i.loli.net/2020/08/18/MuS7w1tgyoiRAU2.png)

17.在桌面右键，如果有Git的相关命令，即安装成功
![](https://i.loli.net/2020/08/18/dGpH6JBlCXE18cQ.png)

18.第二种验证方式<br>
Windows搜索命令提示符，然后以管理员身份运行
![](https://i.loli.net/2020/08/18/L3b1hwjnRdOq2l8.png)
输入<br>
```
git --version
```
如果有版本信息，即安装成功